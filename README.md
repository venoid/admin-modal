# Venoid Admin Modal Component

Modal component for your administration provides you good options how to show your modal with any content.

![screenshot-example]()

## Props
| Props         | Type    | Default   |                                      |
|---------------|---------|-----------|--------------------------------------|
| actions       | Array   | []        | Array of objects with options. Represent buttons in a footer.    |
| active        | Boolean | false     | Shows or hides modal.                |
| close-button  | Boolean | true      | Shows cross button at top right of an overlay. |
| header        | String  | 'Modal name' | Text of a header. |

#### actions options
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
