# 🥞 Pancake UIkit

[![Version](https://img.shields.io/npm/v/@secousse/yieldlab-uikit)](https://www.npmjs.com/package/@secousse/yieldlab-uikit) [![Size](https://img.shields.io/bundlephobia/min/@secousse/yieldlab-uikit)](https://www.npmjs.com/package/@pancakeswap-libs/uikit)

YieldLab UIkit is a set of React components and hooks used to build pages on YieldLab's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @secousse/yieldlab-uikit`

## Setup

### Theme

Before using YieldLab UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@secousse/yieldlab-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@secousse/yieldlab-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://secousseclama.github.io/yieldlab-uikit/)
