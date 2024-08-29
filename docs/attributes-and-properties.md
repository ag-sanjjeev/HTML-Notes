## &#9873; Attributes and Properties
The HTML attributes are additional values, That can be added to an HTML Tag. This will modify the default behavior of the HTML Tag. Here, Tag attributes also known as Tag Properties.

*Global Attributes will applicable to all standard HTML elements. But some elements will not.*

### &#9780; List of global attributes:
1. [aria](#-aria),
2. [accesskey](#-accesskey),
3. [anchor](#-anchor),
4. [autocapitalize](#-autocapitalize),
5. [autofocus](#-autofocus),
6. [class](#-class),
7. [contenteditable](#-contenteditable),
8. [data](#-data),
9. [dir](#-dir),
10. [draggable](#-draggable),
11. [enterkeyhint](#-enterkeyhint),
12. [exportparts](#-exportparts),
13. [hidden](#-hidden),
14. [id](#-id),
15. [inert](#-inert),
16. [inputmode](#-inputmode),
17. [is](#-is),
18. [itemid](#-itemid),
19. [itemprop](#-itemprop),
20. [itemref](#-itemref),
21. [itemscope](#-itemscope),
22. [itemtype](#-itemtype),
23. [lang](#-lang),
24. [nonce](#-nonce),
25. [part](#-part),
26. [popover](#-popover),
27. [role](#-role),
28. [slot](#-slot),
29. [spellcheck](#-spellcheck),
30. [style](#-style),
31. [tabindex](#-tabindex),
32. [title](#-title),
33. [translate](#-translate),
34. [virtualkeyboardpolicy](#-virtualkeyboardpolicy),
35. [writingsuggestions](#-writingsuggestions)

---
### &#10022; Aria: 
- ARIA stands for **A**ccessible **R**ich **I**nternet **A**pplications.
- It is a set of attributes that can be added to HTML Tag Elements. 
- This makes web page or application to be more accessible to users with disabilities.

See this [`ARIA Reference`](./aria-attributes.md)

### &#10022; Accesskey:
- This is generating keyboard shortcut hint for the current element.
- This will allow space-separated list of characters. 
- The browser takes first one of the list that exist on computer keyboard layout.

See this [`Accesskey Reference`](./accesskey-attributes.md)

### &#10022; Anchor:
- This associates a positioned element and used with [anchor tag](../tags/a-tag.md).

See this [`Anchor Reference`](./anchor-attributes.md)

### &#10022; Autocapitalize:
- This can controls whether input text is automatically capitalized and in what type of manner.

See this [`Autocapitalize Reference`](./autocapitalize-attributes.md) 

### &#10022; Autofocus:
- This will focus current element when on page load or dialog load. Based on where it was placed.
- It is boolean value. Either **True** or **False**. By-default this attribute value is **false**. 

See this [`Autofocus Reference`](./autofocus-attributes.md)

### &#10022; Class:
- This will add list of class elements which is space separated to the current element.
- This class list can be used as selector for the current element to apply CSS Styles and Processed with JavaScript.

See this [`Class Reference`](./class-attributes.md)

### &#10022; Contenteditable:
- This attribute will set the possibilities to the current element for user editable.
- This has three different value. 
- **True** value or an **empty string** value can gives possibility as editable for the user with rich text editing features.
- **Plaintext-only** value can gives possibility of plain text editing without rich text editing feature.
- By-default this attribute value is **false**.

See this [`Contenteditable Reference`](./contenteditable-attributes.md)

### &#10022; Data:
- This forms a different set of attributes followed by `data-`.
- This data attributes will give possibilities to add custom data to the current element.
- This custom data will allow to exchange data between HTML elements and DOM representation that may used by scripts. 

See this [`Data Reference`](./data-attributes.md)

### &#10022; Dir:
- This indicates the text direction of the element.
- This attribute accept three different value.
- **ltr** - which means left to right, To write the text in the direction of left side of the page to right side.
- **rtl** - which means right to left, To write the text in the direction of right side of the page to left side. 
- **auto** - which means the direction will be decided by the user agent.

See this [`Dir Reference`](./dir-attributes.md)

### &#10022; Draggable:
- This will make the current element to be draggable using the Drag and Drop functionality.
- The default value is **false**.
- **true** value will make the current element draggable.

See this [`Draggable Reference`](./draggable-attributes.md)

### &#10022; Enterkeyhint:
- This is will modifies the action label or icon to present for the enter key on virtual keyboards.
- This will supports for user input based HTML elements.

See this [`Enterkeyhint Reference`](./enterkeyhint-attributes.md)

### &#10022; Exportparts:
- This allows to select and style HTML elements existing in nested shadow trees, by exporting their part names.
- The shadow tree is an isolated structure which cannot be reached by identifiers, classes and styles with selectors or queries belonging to a regular DOM.

See this [`Exportparts Reference`](./exportparts-attributes.md)

### &#10022; Hidden:
- This attribute indicates to the browser that the current element to be hidden from the current web page.

See this [`Hidden Reference`](./hidden-attributes.md)

### &#10022; Id:
- This defines a unique identifier (ID). 
- The ID of HTML elements should be unique in the whole HTML document. 

See this [`Id Reference`](./id-attributes.md)

### &#10022; Inert:
- This attribute did not allow any of the event bind to the current element.
- To avoid any other interactions to the current element tree such as onclick, onfocus, etc.,
- This is mostly used in hidden dialog box or some special use cases.	

See this [`Inert Reference`](./inert-attributes.md)

### &#10022; Inputmode:
- This attribute allows or validates or requires to accept specific data-type mentioned in type attribute.
- This attribute primarily used on input tag, but usable on any element that accepts user input. 

See this [`Inputmode Reference`](./inputmode-attributes.md)

### &#10022; Is:
- This attribute modifies the standard HTML element to behave like registered custom built-in element.
- This allows to define standard HTML element with custom functionalities via script. 

See this [`Is Reference`](./is-attributes.md)

### &#10022; Itemid:
- The unique and global identifier of an item.
- This will give valid usage when used with both [Itemscope](#-itemscope) and [Itemtype](#-itemtype). 

See this [`Itemid Reference`](./itemid-attributes.md)

### &#10022; Itemprop:
- This attribute can add property as a name-value pair to the current HTML element.
- The group of one or more properties forms an item.
- The value of the named properties to be either string or url.

See this [`Itemprop Reference`](./itemprop-attributes.md)

### &#10022; Itemref:
- This attribute provides list of element ids but not [Itemid](#-itemid).
- This can used with [Itemscope](#-itemscope)

See this [`Itemref Reference`](./itemref-attributes.md)

### &#10022; Itemscope:
- This attribute works along with [itemtype](#-itemtype).
- This specifies that HTML contained block is about a particular item and defines the scope of the [itemtype](#-itemtype) associated with it. 

See this [`Itemscope Reference`](./itemscope-attributes.md)

### &#10022; Itemtype:
- This attribute specifies the URL of the vocabulary that can be used to define [Itemprop](#-itemprop) in the data structure.

See this [`Itemtype Reference`](./itemtype-attributes.md)

### &#10022; Lang:
- This attribute defines the language of the current HTML element which is not-editable element.
- The value of this attribute will be hyphen separated **Language Sub-tag**.

See this [`Lang Reference`](./lang-attributes.md)

### &#10022; Nonce:
- The nonce stands for **N**umber used **once**.
- This nonce used to protect private communications by preventing replay attacks.  
- This will be useful to white list to allow specific HTML element, such as a particular inline scripts or style elements.
- This will restrict the CSP unsafe-inline directive, to allow all inline scripts or styles at once. 

See this [`Nonce Reference`](./nonce-attributes.md)

### &#10022; Part:
- This attribute contains space separated list of part names like class list on the HTML element.
- This part names can allow CSS to select and style specific elements in shadow tree via `::part` pseudo element in CSS.

See this [`Part Reference`](./part-attributes.md)

### &#10022; Popover:
- This attribute is used to treat the current HTML element as popover element.

See this [`Popover Reference`](./popover-attributes.md)

### &#10022; Role:
- This attribute defines semantic meaning of the content in the HTML element.
- This is useful for screen reader and many other tools to present and support interactions.
- This role attribute value to be role type, which is the name of the role in the [ARIA](#-aria) specification.

See this [`Role Reference`](./role-attributes.md)

### &#10022; Slot:
- This attribute assigns the shadow tree to the HTML element.
- This will assign the created slot element whose name attribute value matches that slot attribute value.  
See this [`Slot Reference`](./slot-attributes.md)

### &#10022; Spellcheck:
- This attribute defines whether the element to be checked for spelling errors or not.
- The default value is **false**.
- **true** or **empty** value will check for the spelling errors to the current element.

See this [`Spellcheck Reference`](./spellcheck-attributes.md)

### &#10022; Style:
- This attribute assigns the immediate CSS to the current element.
- This is useful for quick styling and testing purpose.
- The best practice is to use separate CSS file.

See this [`Style Reference`](./style-attributes.md)

### &#10022; Tabindex:
- This attribute will assign and order of the position to be focusable via keyboard navigation if available.
- **0** value means immediate and first element in the keyboard navigation order.
- Positive value means the navigation arranged in the ascending order.
- Negative value means the elements is not to be focusable while keyboard navigation.
- If the attribute is not used in the HTML element, then relative order defined by the platform.

See this [`Tabindex Reference`](./tabindex-attributes.md)

### &#10022; Title:
- This attribute will representing the advisory and useful information to the current element.
- This will displays the information as tooltip on the element.
- This is not necessary but for informative purpose to the user.

See this [`Title Reference`](./title-attributes.md)

### &#10022; Translate:
- This attribute allows the browser to translate the content of the current element to their localization.
- **yes** value represents to translate the content.
- **no** value represents to prevent being translate the content.

See this [`Translate Reference`](./translate-attributes.md)

### &#10022; Virtualkeyboardpolicy:
- This attribute controls the on-screen virtual keyboard behavior for the devices.
- This is useful for the device which does not have any hardware keyboard support.
- This will helpful to prevent key-loging threads on the devices for the confidential information.
- **auto** or **empty string** value will automatically shows the virtual keyboard when the element is focused.
- **manual** value will decouples focus on the element from the virtual keyboard state.

See this [`Virtualkeyboardpolicy Reference`](./virtualkeyboardpolicy-attributes.md)

### &#10022; Writingsuggestions:
- This used to control the behavior of the browser writing suggestion in the input based HTML elements.
- **false** value will disable the writing suggestions for the current element.
- **true** or **empty string** value will enable the writing suggestions for the current element.

See this [`Writingsuggestions Reference`](./writingsuggestions-attributes.md)

---
[&#8682; To Top](#-attributes-and-properties)

[&#10094; Previous Topic](../void-elements.md) &emsp; [Next Topic &#10095;](./events.md)

[&#8962; Goto Home Page](../README.md) 