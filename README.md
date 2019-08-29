# Venoid Admin Modal Component

Modal component for your administration provides you good options how to show your modal with any content.

![gif-example](https://bitbucket.org/venoid/admin-modal/raw/b409125ba5cbba59865005f299696e3b60226669/images/example2.gif)

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
