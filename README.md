# Tribute-page
 A tribute page for Sergey Yesenin as the first challenge of Responsive Web Design Projects on FreeCodeCamp.org

## Right of use
You can use HTML i CSS files from this repository to improve your Tribute page or from anything you like, without restrictions.

### Right of use assets
Images and background you can use only with contribution of their author

### Note
While code is running smoothly, there are two things that you should know:

1) I failed to override margin-block, following code snippet didn't' work

{
margin-block-start:0; margin-block-end:0; margin-inline-start:0; margin-inline-end:0;
padding-block-start:0; padding-block-end:0; padding-inline-start:0; padding-inline-end:0;
}

2) I'm not actually sure how I managed to center the button. Approach:

.parent {
    display: inline-block;
    position: realitive;
}

.child {
    position: absolute;
    margin-left: 50%;
    transform: translateX(-50%);
}

*also didn't work. But, when I set position relative to main div container (parent of all other elements in the body), button magically goes to the horizontal center of the page.