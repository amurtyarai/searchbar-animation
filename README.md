# searchbar-animation
Features
- Pure HTML + CSS implementation (no JavaScript)
- Smooth transition effects
- Expanding input field animation
- Morphing search → cancel icon
- Centered responsive layout

Working
When the search field (`input`) is focused:
- The input box smoothly expands from `50px` to `300px`
- The search icon transitions into a cancel (X) icon using pseudo-elements (`::before` and `::after`)
- Clicking outside or pressing `Esc` reverts it to the default circular icon
