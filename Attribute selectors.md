The `[attribute]` selector is used to select elements with a specified attribute. The example below selects all `<a>` elements with a target attribute.
![[Pasted image 20241022202950.png]]
# `[attribute="value"]` Selector
The `[attribute="value"]` selector is used to select elements with a specified attribute and value. The example selects all `<a>` elements with a `target="_blank"` attribute
![[Pasted image 20241022203315.png]]
# `[attribute~="value"]` Selector
The `[attribute~="value"]` selector is used to select elements with an attribute value containing a specified word. The example below selects all elements with a title attribute that contains a space-separated list of words, one of which is "flower"
![[Pasted image 20241022204107.png]]
The example above will match elements with `title="flower"`, `title="summer flower`, and `title="flower new"`, but not `title="my-flower"` or `title="flowers"`.
# `[attribute|="value"]` Selector
The `[attribute|="value"]` selector is used to select elements with the specified attribute, whose value can be exactly the specified value, or the specified value followed by a hyphen (-). The value has to be a whole word, either alone, like class="top", or followed by a hyphen( - ), like class="top-text".
![[Pasted image 20241022204705.png]]
# `[attribute^="value"]` Selector
The `[attribute^=value]` selector is used to select elements with the specified attribute, whose value starts with the specified value. The example below selects all elements with a class attribute value that starts with "top": 
![[Pasted image 20241022205713.png]]
The value does not have to a whole word!
# `[attribute$="value"]` Selector
The `[attribute$="value"]` selector is used elements whose attribute value ends with a specified value. The example below selects all elements with a class attribute value that ends with "test":
![[Pasted image 20241022210035.png]]
The value does not have to a whole word!
# `[attribute*="value"]` Selector
The `[attribute*="value"]` selector is used to select elements whose attribute value contains a specified value. The example below selects all elements with a class attribute value that ends with "te": 
![[Pasted image 20241022210446.png]]
The value does not have t be a whole word!
# Styling Forms
The attribute selectors can be useful for styling forms without class or ID:
![[Pasted image 20241022210609.png]]

