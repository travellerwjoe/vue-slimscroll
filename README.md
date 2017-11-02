#vue-slimscroll
Vue-slimscroll is a directive plugin for Vue.js, which can transforms any div into a scrollable area with a nice scrollbar.
The original jQuery version is here[https://github.com/rochal/jQuery-slimScroll](https://github.com/rochal/jQuery-slimScroll).

##Install
1.Install it by using npm.

```
npm i vue-slimscroll
```

2.Import it at `vue` project.

```
import Vue rom 'vue'
import VueSlimScroll from 'vue-slimscroll'
...
Vue.use(VueSlimScroll)
```

##Usage

Using the `v-slimscroll` directive
```
<template>
    <div v-slimscroll>
        ...
    </div>
</template>
```

Using directive with options

```
<template>
    <div v-slimscroll="options">
    ...
    </div>
</template>
<script>
    export default {
        data:{
            return (){
                options:{
                    height:'100%',
                    size:0
                }
            }
        }
    }
</script>
```
> The `options` is same as jQuery version. See their [documentation](http://rocha.la/jQuery-slimScroll)

##License
[MIT](http://opensource.org/licenses/MIT)
