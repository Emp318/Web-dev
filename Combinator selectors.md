A combinator is  something that explains the relationship between the selectors.
A CSS selector can contain one simple selector. Between the simple selectors, we can include a combinator.
There are four different combinators in CSS:
- Descendant combinator (space)
- Child combinator (`>`)
- Next sibling combinator (`+`)
- Subsequent-sibling combinator 

## [[Descendant combinator]]
The descendant combinator matches all elements that are descendants of a specified element. The following example selects all `<p>` elements inside `<div>` elements.
![[Pasted image 20241020000357.png]]
## [[Child Combinator]]
The child combinator selects all elements that are the children of a specified element. The following example selects all `<p>` elements that are chidden of a `<div>` element:
![[Pasted image 20241020005109.png]]
# [[Next-sibling Combinator]]
The next sibling combinator is used to select an element that is directly after another specific element. Sibling elements must have the same parent element, and "adjacent"("Immediately following").
![[Pasted image 20241020022301.png]]
# [[Subsequent-sibling Combinator]]
The subsequent-sibling combinator selects all elements that are next sibling of a specified element. The following example selects all `<p>` elements that are next siblings of `<div>` elements:
![[Pasted image 20241020022848.png]]
