# vue-mdc-adapter

> [VueJS](https://vuejs.org) wrapper arround 
Google's [Material Components](https://material.io/components/web/)

*under development, check the [wiki](https://github.com/stasson/vue-mdc-adapter/wiki) for more ...*

## Installation

- install vue-mdc-adapter

`npm install --save vue-mdc-adapter`

- Import google's Material font's and icons:

```
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" type="text/css">
```

_OR_ - Import icons with webpack and ES6

```
npm install material-design-icons
```

```
import 'material-design-icons/iconfont/material-icons.css'
```

- register the vue_mdc_adapter plugin

```
import Vue from 'vue'
import VueMdcAdapter from 'vue-mdc-adapter'

Vue.use(VueMdcAdapter)
```

_OR_

```
import Vue from 'vue'
import VueMdcButton from 'vue-mdc-adapter/button'

Vue.use(VueMdcButton)
```

 
## Documentation

Doc and Demo coming soon...

In the meantime you can have a look at the [preview](https://stasson.github.io/vue-mdc-adapter)

Or clone from [github](https://github.com/stasson/vue-mdc-adapter)

```
# get the repository
git clone https://github.com/stasson/vue-mdc-adapter.git
cd vue-mdc-adapter

# install dependencies
npm install
 
# serve at localhost:8080
npm run dev
```
