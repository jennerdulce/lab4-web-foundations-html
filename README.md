# lab4-web-foundations-html

## Errors

(Line 21) ERROR!: A link element must not appear as a descendant of a body element unless the link element has an itemprop attribute or has a rel attribute whose value contains dns-prefetch, modulepreload, pingback, preconnect, prefetch, preload, prerender, or stylesheet. 
- Interesting that the link element in this case is NOT in a body element

(Line 24) ERROR!:  Element style not allowed as child of element body in this context. (Suppressing further errors from this subtree.)
 - Interesting that the element in this case is NOT in a body element

(Line 59) ERROR!: Stray end tag head
- End tag is not stray

(Line 62) ERROR!: Start tag body seen but an element of the same type was already open
- Body tags are aligned correctly

(Line 260) ERROR!: Element p not allowed as child of element dfn in this context. (Suppressing further errors from this subtree.)
- Used an exact example referenced on the following website.
- Ref: [DFN](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/dfn)

(Line 319) ERROR!: Stray end tag wbr.
- End tag is not stray

(Line 487) ERROR!: Element selectedcontent not allowed as child of element main in this context. (Suppressing further errors from this subtree.)
- Unsure why this comes up as an error