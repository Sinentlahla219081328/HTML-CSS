# HTML-CSS
#INTRODUCTION TO HTML
It is the language that allows you to make sure your content is understandable to both people and computers.
The are three web programming languages : HTML, CSS and Javascript. HTML-HyperText Markup Language: It is used for structure and content of the web page,
CSS- Cascading Style Sheet is used for stylling and layout of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.
Javascript allow us to manipulte the behaviour of HTML and CSS dynamical.javascript used for Client-Side, Event handling , Animations and Effect sand, Form handling.
The web or browser programming broken up into three parts to be resilient to changes in technology. JavaScript is the most powerful and fragile of the browser programming languages. The browser guesses what you meant, and does its best to fix the bug itself when HTML is broken because of a bug in the code.

#HTML TEXT FORMATTING
html uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. 
Tags come in two types:opening tags and closing tags.
we can have paragraph that uses emphasized text for effect.
It is a separate element that nested inside a paragraph with em and em tag
We use h1 to h6 tags to define Headlines and Subheadings where h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing.

HTML Bold and Italics:There are four HTML elements related to this, two for bold and two for italic.
Using italic elements : em to add emphasis and i to apply visual italics .
The are two elements to emphasize or make something bold in HTML.The first one is the "strong" element,which is used to show importance,seriousness, or urgency.
This element adds meaning to the text. On the other hand, the "b" element is more generic and neutral.
It does not carry any specific meaning;it simply allows us to make something bold visually and does not imply any alternative voice or mood.

HTML lists are unordered lists, ordered lists, and definition lists. 
Using unordered list to define the entire list and specify its type,we wrap all the items in a ul element. Each item in the list is enclosed in an li element, which represents a list item.
Using ordered list to define the entire list and specify its type,we wrap all the items in a ol element.Each item in the list is enclosed in an li element, which represents a list item.
Using definition or description list elements it is used when we want to create a list that resembles a key-value pair in computer science.To create a definition list, we use specific elements.The term or key is enclosed in a dt tag, which stands for definition term. The description or value is enclosed in a dd tag, which stands for definition description. You can have multiple descriptions for each term by using multiple  tags. 
The entire list is wrapped in a dl tag, representing the definition list. Interestingly, the  tags and  tags are placed side by side without any additional wrapper around them. lang and dir are also global attributes.

HTML Quotes
To distinguish the quote from the surrounding text, we can wrap the whole thing in a blockqoute element, and use cite element to attribute the qoute. These two element serve a semantic purpose.They inform other computers, "Hey, this is what this is." Additionally, they provide a convenient way to apply custom styling.
Using inline quotes :  we can use the "q" element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us.
Add lang= "fr"  or lang = "bg".

Date element -  the datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this: less-than time datetime="2025-05-08"greather -than May 8, 2025 then cloce the time tag.
Time Element  write it like this: less-than time datetime="DT2H30M"greather -than 2h 30m then cloce the time tag.

HTML Code, pre and br.
Using code element - if you want to showcase the code on a webpage , Put an opening code tag before the CSS snippet and a closing code tag afterward. 
When you want to add a html element you write code then put &lt; displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign. In between you put the element like H4 or P for example.
Using br tag to break at the end of each lines. The br element is a simple tag without an opening or closing tag. it just indicates where a line break should happen.
Using pre element: Pre and code elements are often combined to display a code block with proper indentation. To let the browser know that this is a block of code, you wrapped the entire content in a code element and to preserve the formatting and spacing,you further wrapped in a pre element.

HTML Superscripts, Subscripts and Small Text. 
Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters that are set below the normal baseline for text.Superscripts are characters that are set above the normal baseline of text. you can use small to convey that something has very little prominence. 

HTML Global attributes : class and id attribute.
class attribute allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. 
id come in handy when we need to address specific elements in JavaScript or targeted links. The uniqueness of an ID name ensures that there will always just be one element with that ID, making it useful for interacting with JavaScript or links. Regardless of the use case, class and ID attributes provide a way to name HTML elements and reference them in other parts of the code stack. lang and dir are also global attributes.

ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent.
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex interface in an app. The sort of efforts require the use and understanding of ARIA attributes involving accessibility issues.

Using non breaking space in HTML to create multiple spaces between words. if you want to keet the first name "Lebron" and the last name "James" together in a sentence. We can use the code "and non breaking space;" to insert a non-breaking space between the two names, ensuring they stay on the same line. 
