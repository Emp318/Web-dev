A CSS pseud-element is used to style specific parts of an element. It can be used to:
- Style the first letter or line, of an element
- Insert content before or after an element
- Style the markers of list items
- Style the view box behind a dialog box 
# Syntax
![[Pasted image 20241020032418.png]]
# The ::first-line Pseudo-element
The `::first-line` pseudo-element is used to add a special style to the first line of a text. The example below formats the first line of the text in all `<p>` elements:
![[Pasted image 20241020125927.png]]

### Note: The `::first-line` pseudo-element can only be applied to block-level elements. The following properties apply to the `::first-line` pseudo-element:
- font properties
- color properties
- background properties
- word-spacing
- letter-spacing
- text-decoration
- vertical-align
- text-transform
- line-height
- clear
# Pseudo-elements and HTML Classes
Pseudo-elements can be combined with HTML classes:
The example below display the first letter of paragraphs with `class="intro"`, in red and in a larger size.
![[Pasted image 20241020130638.png]]
# The ::before Pseudo-element
The `::before` pseudo-element can be used to insert some content before the content of an element. The example below inserts an image before the content of each `<h1>` element:
![[Pasted image 20241020131022.png]]
# The ::after Pseudo-element
The `::after` pseudo-element can be used to insert some content after the content of an element. Here an image is inserted after the content of each `<h1>` element:
![[Pasted image 20241020131312.png]]
# The ::marker Pseudo-element
The `::marker` pseudo-element selects the markers of list items. Here the markers of list items are styled:
![[Pasted image 20241020131604.png]]
# The ::selection Pseudo-element
The `::selection` pseudo-element matches the portion of an element that is selected by a user. The following CSS properties can be applied to be `::selection : color`, `background`, `cursor`, and `outline`. The example makes the selected text red on a yellow background:
![[Pasted image 20241020132020.png]]
