# Vue Heroicons2

A package to easily make use of [Heroicons](https://github.com/refactoringui/heroicons) in your Vue components.

For a full list of available icons see [the SVG directory](resources/svg) or preview them at [heroicons.dev](https://heroicons.dev). Heroicons are originally developed by [Steve Schoger](https://twitter.com/steveschoger) and [Adam Wathan](https://twitter.com/adamwathan).

## Installation

```bash
// using npm
npm install vue-heroicons2

// using yarn
yarn add vue-heroicons2
```

## Usage

You can import whatever icons you want

```javascript
import { OAdjustments, OUsers } from "vue-heroicons2";
```

Icons can be used a self-closing Vue components which will be compiled to SVG icons:

```html
<o-adjustments/>
```

You can also pass classes to your icon components:

```html
<o-adjustments classes="w-6 h-6 text-gray-500"/>
```

The solid icons can be referenced like this:

```html
<s-adjustments/>
```

## Maintainers

Vue Heroicons is developed and maintained by [Mosab Ibrahim](https://miaababikir.me).