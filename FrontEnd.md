## Fundamental
- The Box Model : Every single thing on a webpage is a rectangular box. These boxes can have other boxes in them and can sit alongside one another.
- By default, block elements will appear on the page stacked atop each other, each new element starting on a new line.
- Inline elements do not start on a new line. They appear in line with whatever elements they are placed beside. A clear example of an inline element is a link, or <a> tag. If you stick one of these in the middle of a paragraph of text, it will behave like a part of the paragraph.In general, you do not want to try to put extra padding or margin on inline elements.
- Normal workflow : Elements on a webpage lay out in normal flow if you haven't applied any CSS to change the way they behave. And you can change how elements behave either by adjusting their position in normal flow or by removing them from it altogether. Starting with a solid, well-structured document that's readable in normal flow is the best way to begin any webpage. It ensures that your content is readable even if the user's using a very limited browser or a device such as a screen reader that reads out the content of the page. In addition, since normal flow is designed to make a readable document, by starting in this way you're working with the document rather than struggling against it as you make changes to the layout.

## HTML
- [HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- HTML and CSS are two languages that work together to create everything that people see  on the internet. 
- HTML is the raw data that a webpage is built out of. All the text, links, cards, lists, and buttons are created in HTML. 
- HTML is a markup language used to format/structure a web page.
- `<!DOCTYPE html> <html lang="en"> <head><meta charset="utf-8"> <link </head>  <body></body> </html>`
- Divs and Spans :
  - Div is a block-level element by default. It is commonly used as a container element to group other elements. Divs allow us to divide the page into different blocks and apply styling to those blocks.
  - Span is an inline-level element by default. It can be used to group text content and inline HTML elements for styling and should only be used when no other semantic HTML element is appropriate.


## CSS
- CSS is a design language that you use to make your web page look nice and presentable.
- CSS is what adds style to those plain elements. HTML puts information on a webpage, and CSS positions that information, gives it color, changes the font, and makes it look great!
- Many great resources out there keep referring to HTML and CSS as programming languages, but if you want to get technical, labeling them as such is not quite accurate, because they are only concerned with presenting information. They are not used to program any logic.
-  [Using the CSS overview feature in Chrome Developer Tools](https://www.freecodecamp.org/news/how-to-use-css-overview-in-chrome-developer-tools/)
- Flex : A way to arrange items into rows or columns.
  - A flex container is any element that has `display: flex` on it. 
  - A flex item is any element that lives directly inside of a flex container.Any element can be both a flex container and a flex item. Said another way, you can also put `display: flex` on a flex item and then use flexbox to arrange its children.
  - `Flex-Grow` expects a single number as its value, and that number is used as the flex-item’s “growth factor”. When we applied `flex: 1` to every div inside our container, we were telling every div to grow the same amount. The result of this is that every div ends up the exact same size. If we instead add `flex: 2 `to just one of the divs, then that div would grow to 2x the size of the others.
  - `Flex-Shrink` is similar to `flex-grow`, but sets the “shrink factor” of a flex item. `flex-shrink` only ends up being applied if the size of all flex items is larger than their parent container. For example, if our 3 divs had a width declaration like: `width: 100px`, and `.flex-container` was smaller than 300px, our divs would have to shrink to fit. The default shrink factor is `flex-shrink: 1`, which means all items will shrink evenly. If you do not want an item to shrink then you can specify flex-shrink: 0;. You can also specify higher numbers to make certain items shrink at a higher rate than normal.
  - An important implication to notice is that when you specify `flex-grow` or `flex-shrink`, flex items do not necessarily respect your given values for width. 
  - `Flex-basis` simply sets the initial size of a flex item, so any sort of `flex-grow` or `flex-shrink` starts from that baseline size. The shorthand value defaults to `flex-basis: 0%`. The reason we had to change it to auto  is that with the basis set to 0, those items would ignore the item’s width, and everything would shrink evenly. Using auto as a flex-basis tells the item to check for a width declaration.
  - [class uses of flex](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  
  
##  JavaScript
- A programming language because it’s used to make webpages do things. 
- Two ways to add JS into html files(both in the body):`<script> console.log("hello,world")<script>` or `<script src=javascript.js"> <script> `.
- `let` is a modern variable declaration.
- Variables declared using `const` are called “constants”. They cannot be reassigned.
- Here I will type something about JavaScript.
