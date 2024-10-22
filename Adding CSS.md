When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet. There are three ways of inserting a style sheet:
- External CSS
- Internal CSS
- Inline CSS
# External CSS
With an external style sheet, you can change the look of an entire website by changing just one file! Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section. An external style sheet can be written in any text editor, and must be saved with `.css` extension. The external `.css` file should not contain any HTML tags. 
![[Pasted image 20241022213202.png]]
# Internal CSS
AN internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the `<style>` element, inside the head section.
![[Pasted image 20241022213233.png]]
# Inline CSS
An inline style may be used to apply a unique style style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
![[Pasted image 20241022213445.png]]
# Multiple Style Sheets
If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.
![[Pasted image 20241022213721.png]]
if the internal style is defined after the link to the external style sheet, the `<h1>` elements will be "orange":
![[Pasted image 20241022213856.png]]
However, if the internal style is defined before the link to the external style sheet, the `<h1>` elements will "navy";
![[Pasted image 20241022214218.png]]
# Cascading Order
When there is more than one style specified for an HTML element, all the styles in a page will "cascade" into a new "virtual" style sheet by following rules, where number one has the highest priority:
1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default
So, an inline style has the highest priority, and will override external and internal styles and browser defaults.