## Day 2 Relative Units

https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts/349964-day-2-getting-familiar-with-relative-units
https://www.youtube.com/watch?v=_-aDOAMmDHI

### Key takeaways
1. em 
    1. Based on the parent
    1. Be careful when using em because they compound on top of each other. For example, if the parent has `2em` and its child has `2em`, the child will end up with `64px` (`16px x 2 x 2`)
    1. However, it's safe to use em to set margins and paddings, because they will change depending on the font-size of the content. 
2.  rem
    1. Based on the root (`::root` or `html`)
    1. More consistent for font sizes.
    1. If we set margins and paddings using rem, they will remain the same margins and paddings, despite changing the font size of the content.
    1. It really depends, for example, if you are adding buttons and you want the spacing/margin to be the same, then you would use rem instead of em.

The reason we want to use `em` and `rem` over `px` is because they make our lives easier when it comes to media queries. We would set sizes of the html elements using `em` and `rem`, and we would only need to just the `px` of the html at different breakpoints and easily adjust the font sizes in one go.

