# Venoid Admin Modal Component

[![npm](https://img.shields.io/npm/v/@venoid/admin-modal?color=green)](https://www.npmjs.com/package/@venoid/admin-modal)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@venoid/admin-modal)

Modal component for your administration provides you good options how to show your modal with any content.

![gif-example](https://raw.githubusercontent.com/venoid/admin-modal/master/images/example2.gif)

## Props
| Props         | Type    | Default   |                                      |
|---------------|---------|-----------|--------------------------------------|
| actions       | Array   | []        | Array of objects with [options](#action-options). Represent buttons in a footer.    |
| active        | Boolean | false     | Shows or hides modal.                |
| close-button  | Boolean | true      | Shows cross button at top right of an overlay. |
| header        | String  | 'Modal name' | Text of a header. |

#### action options
```
{
  label: 'Say hello' // String,
  onclick: () => { window.alert("Hello") }  // Function
}
```

## Slots

Modal has just one slot (without name) for its content.

| Name          | Purpose                       |
|---------------|-------------------------------|
|       --      | Put content of the modal body |

## Demo
To see demo run a project:

1. Install npm dependencies
2. Run with `npm run serve` / `yarn serve`
