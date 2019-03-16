# vue-shiny-button

> The shiniest Vuejs button component

![vue-shiny-button in use](https://user-images.githubusercontent.com/38357771/54468459-13246f00-4763-11e9-8f46-f9fe0abda720.gif)

[![Try it on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/ol9q8jyw4q?fontsize=14)

## Installation

Install the package from npm by running `npm i vue-shiny-button` or `yarn add vue-shiny-button`.

## Usage

Import and register the component to use it in your app's templates.

```html
<template>
  <VueShinyButton @click="..." />
</template>
```

```js
import VueShinyButton from 'vue-shiny-button'

export default {
  components: {
    VueShinyButton,
  }
}
```

## Accessibility

Apply attributes, such as aria-labels, directly on the element to apply them to the button.

```html
<template>
  <VueShinyButton aria-label='Send message' />
</template>
```

## Contributing

This project is open to and encourages contributions! Feel free to discuss any bug fixes/features in the [issues](https://github.com/shwilliam/vue-shiny-button/issues). If you wish to work on this project:

1.  [Fork the project](https://github.com/shwilliam/vue-shiny-button/archive/master.zip)
2.  Create your feature branch (`git checkout -b new-feature-branch`)
3.  Commit your changes (`git commit -am 'add new feature'`)
4.  Push to the branch (`git push origin new-feature-branch`)
5.  [Submit a pull request!](https://github.com/shwilliam/vue-shiny-button/pull/new/master)

Note: Running dev script requires @vue/cli and @vue/cli-service-global to be installed.
Install globally by running `npm i --g @vue/cli @vue/cli-service-global` or `yarn add global vue/cli @vue/cli-service-global`.
