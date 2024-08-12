# HTML-CSS
# INTRODUCTION TO HTML
It is the language that allows you to make sure your content is understandable to both people and computers.
The are three web programming languages : HTML, CSS and Javascript. HTML-HyperText Markup Language: It is used for structure and content of the web page,
CSS- Cascading Style Sheet is used for stylling and layout of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.
Javascript allow us to manipulte the behaviour of HTML and CSS dynamical.javascript used for Client-Side, Event handling , Animations and Effect sand, Form handling.
The web or browser programming broken up into three parts to be resilient to changes in technology. JavaScript is the most powerful and fragile of the browser programming languages. The browser guesses what you meant, and does its best to fix the bug itself when HTML is broken because of a bug in the code.

# HTML TEXT FORMATTING
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


# HTML CAPABILITIES
HTML Global attributes : class and id attribute.
class attribute allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. 
id come in handy when we need to address specific elements in JavaScript or targeted links. The uniqueness of an ID name ensures that there will always just be one element with that ID, making it useful for interacting with JavaScript or links. Regardless of the use case, class and ID attributes provide a way to name HTML elements and reference them in other parts of the code stack. lang and dir are also global attributes.

ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent.
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex interface in an app. The sort of efforts require the use and understanding of ARIA attributes involving accessibility issues.

Using non breaking space in HTML to create multiple spaces between words. if you want to keet the first name "Lebron" and the last name "James" together in a sentence. We can use the code "and non breaking space;" to insert a non-breaking space between the two names, ensuring they stay on the same line. 


# HTML NAVIGATIONS AND LINKS
HTML Navigation and link: We use nav, ul,ol, a element in marking up navigation.When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference, a nerdy phrase from the past. Between the opening and closing A tags, we can place text or images, or both, to make them clickable.
Each link is wrapped in an element with the correct URL, and then enclosed in an "li" element to create a list of links. To maintain the order, wrap the whole list in a "ul" element, which represents an unordered list. Finally, encompass the entire menu in a "nav" element to indicate that it is the site's navigation.
breadcrumb trail. Similar to the main menu, wrap the breadcrumb links in a "nav" element, but this time use an ordered list ("ol") since the order of the links matters. However, do not assign the role "navigation" to this menu; instead, we add an "aria label" of "breadcrumb" to provide context when read aloud.

# HTML Working with Graphics and Images
Working with graphics and images: there are four attributes that need to be included for every image.
First, we have the source attribute (SRC), which tells the browser which image file to load. 
Then we have the alt attribute (ALT), which provides a text description of the image. 
Lastly, we have the width and height attributes, which determine the size of the image. 

Image Formats - There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it comes to compressing images. 
GIF-Simple animations, images with a limited color palette, and icons.
SVG- are perfect for logos, icons, and other types of illustrations. it is used to create a compact image that can display in large sizes without pixelation.
JPG-  are a popular choice for compressing photographs
PNG-Images with transparency, icons, logos, and graphics with sharp edges.

Working with the figure and figcaption elements:
First, show a picture of the dog and add a caption to it. Use the figcaption element to wrap the text and designate it as a caption. Then, put the image and the caption together in a figure element. 

# Working With Media
The audio element is different from the image element because it has both an opening and a closing tag. It uses a source element and src attribute to provide the URL of the audio file.
We also use controls to inform the browser that we want to add play button, timeline, and volume control.
we can also add attributes like loop to make the file repeat from the beginning once it reaches the end and "Autoplay" attribute can automatically play the audio as soon as the page loads.
Add type attributes to define the file type.

Working With Video: Just like the audio element, the video element has an opening and closing tag. To display a video, use the source element and src attribute to specify the video file and te type.
Add control attribute, Autoplay,mute and loop attributes. you can also make a video to be a hyperlink by adding "a" tag set hreg with URL.you can open a link to a new tab by adding target attribute and assign "_blank".
Working with video captions and subtitles :To display these captions or subtitles on the video, insert a track element within the video element,use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player. Additionally, use the source lang attribute to indicate the language and add a default attribute to make this track the default choice when captions are enabled.
Embedding Media via Iframes:Embedding refers to taking content from one site and placing it within the middle of another site's page. Inside a Body tag add IFrame element with width and hight, then go to you tube video press share button and embeded video to get a code and paste it inside body tag.

# HTML Content Identification
We can use lang attribute to specify the language of a webpage in the HTML element. Lang is assign to "en-US".
It is also important to specify the content's direction using "dir" attribute to indicate the direction left to right. you can apply dir to all the elements but when your content use the same direction you can just put dir once on the outer HTML element. dir value is ltr(left to right) or rtl(right to left).

The Meta Attribute : Add meta chartset tag within the head element and assign chartset to "UTF-8".it defines what kind of characters we use in our webpage.  
Discription meta tag explain what the website does. you just add a name and content attribute. Add a viewport ensure that if you want to have media code inside your css file to make website responsive.
Link element inside head It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute. href attribute is used to specify the URL  and the rel.
structure inside the body: main, header,footer,article,section and aside.
the difference between a head element and a header element is that the head element contains document metadata, and a header element contains text to be displayed.

HTML Generic Elements, Div and Span.   .
span tag is a inline container that groups elements for styling purposes.
div tag is a block container that groups elements for styling purposes. div tag takes the entire width.
These element they don't do nothing untill the CSS is applied to them.
# HTML Working with forms
# CSS
tylebg color, text color,text align,font size , font weight,font family"font name",set text to be uppercase using text transform, use span element add a class to style one line of a paragraph.

