A pseudo-class is used to define a special state of an element. For example, it can be used to:
- Style an element when a user moves over it
- Style visited and unvisited links differently
- Style an element when it gets focus
- Style valid/invalid/required/optional form elements
# Syntax

![[Pasted image 20241020023300.png]]

# Anchor Pseudo-Classes
Links can be displayed in different ways:
![[Pasted image 20241020023605.png]]
### Note: `a:hover` must come after `a:link` and `a:visited` in the CSS definition in order to be effective! `a:active` must come after `a:hover` in the CSS definition in order to be effective! Pseudo-class names are not case-sensitive.
# Pseudo-classes and HTML Classes
Pseud-classes can be combined with HTML classes: 
![[Pasted image 20241020030109.png]]
# The :first-child Pseudo-class
The `:first-child` pseudo-class matches a specified element that is the first child of another element. In the following example, the selector matches any `<p>` element that is the first child of any element:
![[Pasted image 20241020030447.png]]
# The :lang Pseudo-class
The `:lang` pseudo-class allows you to define special rules for different languages. In the example below, `:lang` defines the quotation marks for `<q>` elements with `lang="no"`:
![[Pasted image 20241020031354.png]]
# The :focus Pseudo-class
![[Pasted image 20241020031703.png]]
