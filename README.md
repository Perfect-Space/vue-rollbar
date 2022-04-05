# vue-rollbar-ps

[![npm (scoped with tag)](https://img.shields.io/npm/v/@perfect-space/vue-rollbar-ps/latest.svg?style=flat-square)](https://npmjs.com/package/@perfect-space/vue-rollbar-ps)
[![npm](https://img.shields.io/npm/dt/@perfect-space/vue-rollbar-ps.svg?style=flat-square)](https://npmjs.com/package/@perfect-space/vue-rollbar-ps)
[![js-standard-style](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com)

> Rollbar plugin for Vue.js

## Installation

```bash
npm install @perfect-space/vue-rollbar-ps --save
```

### Usage

```javascript
var Vue = require('vue');
var Rollbar = require('@perfect-space/vue-rollbar-ps');

Vue.use(Rollbar, {
  accessToken: 'YOUR_ROLLBAR_FRONT_TOKEN',
  ...options
});
```

You can now use Rollbar anywhere in your Vue app.

```javascript
Vue.rollbar.debug('Yohyo!');
// or in a vue component
this.$rollbar.debug('Yohyo!')
```

See [Rollbar javascript documentation](https://rollbar.com/docs/notifier/rollbar.js/) for options
