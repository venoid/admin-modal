# Venoid Admin Modal Component

![npm](https://img.shields.io/npm/v/@venoid/admin-modal?color=green)

Modal component for your administration provides you good options how to show your modal with any content.

![gif-example](https://camo.githubusercontent.com/1b1ce12b3ce310e27081d7b268035fb9976bbb52/68747470733a2f2f6269746275636b65742e6f72672f76656e6f69642f61646d696e2d6d6f64616c2f7261772f623430393132356261356362626135393836353030356632393936393665336236303232363636392f696d616765732f6578616d706c65322e676966)

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
