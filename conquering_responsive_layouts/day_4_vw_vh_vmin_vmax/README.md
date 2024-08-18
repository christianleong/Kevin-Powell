## Day 4 Viewport

https://www.youtube.com/watch?v=IWFqGsXxJ1E

### Key takeaways
1. Setting `vh` to 100% can be fine on the desktop, but can cause issues on mobile devices because the height is smaller. To fix this, you'd have to use media queries.
2. You can also add `vh` or `vw`to padding/font-size which automatically adjusts based on the viewport height/width. Making it responsive. But you would still want to use media queries, because it could get too small/big when the screen is shrunk/expanded. If you are going to be using it for text, it's better to use `vh` as it doesn't change as drastic.
3. `vmin` looks at the smaller of viewport height/width, so it will be responsive as long as the viewport width is smaller than height, but be aware it can still change when you adjust the viewport height.