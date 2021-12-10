
<h3>👉 inline vs inline-block vs block</h3>
inline: it don’t start on a new line, they appear on the same line as the content and tags beside them. Any height and width properties will have no effect. margin top and margin bottom have no effect as well. <span>, <a>, <img> are inline elements
inline-block: It’s essentially the same thing as inline, except that you can set height and width values. all side margins work as well. 
block: always starts on a new line, and fills up the horizontal space left and right on the web page. 'div', 'p', 'h1', 'li'

👉 CSS box model
The CSS box model is a rectangular layout paradigm for HTML elements that consists of the following:
Content - The content of the box, where text and images appear
Padding - A transparent area surrounding the content (i.e., the amount of space between the border and the content)
Border - A border surrounding the padding (if any) and content
Margin - A transparent area surrounding the border (i.e., the amount of space between the border and any neighboring elements)

👉 box-sizing: border-box
box-sizing property allows us to include the padding and border in an element's total width and height. By default, the width and height of an element is calculated like this:
width + padding + border = actual width of an element
height + padding + border = actual height of an element

👉 Pseudo classes vs Pseudo elements
A pseudo-class is a selector that selects elements that are in a specific state, e.g. they are the first element of their type, or they are being hovered over by the mouse pointer. They tend to act as if you had applied a class to some part of your document. Pseudo-classes are keywords that start with a colon: :first-child, :last-child, :hover, :focus, :visited
Pseudo-elements behave in a similar way. However, they act as if you had added a whole new HTML element into the markup, rather than applying a class to existing elements. Pseudo-elements start with a double colon :: ::before, ::after, ::first-line, ::selection
