
[Live Demo](https://tulinho.github.io/paper-rotation-card/paper-rotation-card/)

# &lt;paper-rotation-card&gt;

> This is an element based on Material Design that displays a card able to perform three dimensional rotations.
Use `rotation-trigger` attribute to determine the element that will trigger the rotation animation.

## How-to
```html
<paper-rotation-card>
  <front>
    <p>Card face content goes here!</p>
    <button rotation-trigger>Click me to rotate</button>
  </front>
  <back>
    <p>Card back content goes here!</p>
    <button rotation-trigger>Click me to rotate</button>
  </back>
</paper-rotation-card>
```
## Styling

The following custom properties and mixins are available for styling:


Custom property | Description | Default
----------------|-------------|----------
`--paper-rotation-card-height` | The card height | `250px`
`--paper-rotation-card-width` | The card width | `500px`
`--paper-rotation-card-front` | Mixing applied to the front face | `{}`
`--paper-rotation-card-back` | Mixin applied to the front face | `{}`


## License
Licensed under the MIT license.
