# HTML

### HTML Elements & Tags

### Header
- `<header>`: Defines a header for a document or section.
- `<h1>` to `<h6>`: Heading elements 
- `<nav>`: Navigation links.

### Navigation
- `<nav>`: Navigation links.
- `<a>`: Hyperlinks to other pages or content.
- `<ul>`, `<ol>`, `<li>`: Lists of items, often used for navigation menus.

### Main Content
- `<main>`: The main content of the document.
- `<section>`: Sections of content within `<main>`.
- `<article>`: A self-contained composition in a document that is independently distributable or reusable.
- `<p>`: Paragraphs.
- `pre`: Preformatted text.
- `<img>`: Images.
- `<video>`: Video files.
- `<audio>`: Audio files.
- `<canvas>`: Used for drawing graphics via scripting.

### Article
- `<article>`: A self-contained composition.
- `<h1>`, `<h2>`, ... `<h6>`: Headings within the article.
- `<p>`: Paragraphs.
- `<figure>`: Images, diagrams, photos, code listings, etc., that are referenced in the main flow of an article.
- `<figcaption>`: A caption or legend describing the figure.

### Aside
- `<aside>`: Content tangentially related to the content around the aside element.
- `<ul>`, `<ol>`: Lists that might summarize other content or link to related content.

### Figure
- `<figure>`: Self-contained content, frequently referenced as a single unit from the main content.
- `<figcaption>`: Caption that provides a description of the figure.

### Form
- `<form>`: Interactive controls for submitting information.
- `<input>`: Input fields.
- `<label>`: Labels for `<input>` elements.
- `<button>`: Buttons.
- `<select>`, `<option>`: Dropdown lists.
- `<textarea>`: Multi-line text input.
- `<fieldset>`: Groups related elements within a form.
- `<legend>`: Caption for the content of its `<fieldset>`.
- `<datalist>`: Specifies a list of pre-defined options for input controls.
- `<output>`: Defines the result of a calculation.

### Table
- `<table>`: Table element.
- `<thead>`: The header content of the table.
- `<tbody>`: The body content of the table.
- `<tfoot>`: The footer content of the table, often used for summarizing the data.
- `<tr>`: Table row.
- `<th>`: Table header cell.
- `<td>`: Table data cell.
- `<caption>`: Title or explanation for the table.

### Footers
- `<footer>`: Defines a footer for a document or section.

### HTML Attributes

1. **accept**:
   - Used with `<input type="file">` to specify the types of files that the server accepts, which helps the user by limiting the file selection to those types only.
   ```html
   <input type="file" accept=".jpg, .jpeg, .png">
   ```

2. **autocomplete**:
   - This attribute specifies whether a form or an input field should have autocomplete enabled. Autocomplete allows the browser to predict the value based on user inputs in similar fields.
   ```html
   <input type="text" name="email" autocomplete="email">
   ```

3. **capture**:
   - Used with `<input type="file">` to specify that the media input should be captured directly from the device's camera or microphone, bypassing the selection of existing files.
   ```html
   <input type="file" capture="user">
   ```

4. **crossorigin**:
   - This attribute is used on HTML `<img>`, `<script>`, `<link>`, and `<video>` elements to configure CORS (Cross-Origin Resource Sharing) requests for the element.
   ```html
   <img src="https://example.com/image.jpg" crossorigin="anonymous">
   ```

5. **dirname**:
   - When used with `<input>` or `<textarea>`, this attribute enables the submission of the directionality of the element, allowing the server to be aware of the text direction.
   ```html
   <input type="text" name="text" dirname="text.dir">
   ```

6. **disabled**:
   - Specifies that an input, select, button, or other form element is not interactive and should not be submitted with the form.
   ```html
   <input type="text" disabled>
   ```

7. **elementtiming**:
   - This attribute is used to include the element in the performance timeline API for more detailed monitoring of how elements are rendered on the page.
   ```html
   <img src="logo.png" elementtiming="header-logo">
   ```

8. **for**:
   - Used with `<label>` to specify which form element a label is bound to.
   ```html
   <label for="username">Username:</label>
   <input type="text" id="username">
   ```

9. **max**:
   - Specifies the maximum value for `<input>` elements of type `number`, `range`, `date`, etc.
   ```html
   <input type="number" max="100">
   ```

10. **maxlength**:
    - Defines the maximum number of characters that the user can enter into `<input>` or `<textarea>`.
    ```html
    <input type="text" maxlength="10">
    ```

11. **min**:
    - Specifies the minimum value for `<input>` elements of type `number`, `range`, `date`, etc.
    ```html
    <input type="number" min="1">
    ```

12. **minlength**:
    - Defines the minimum number of characters required in `<input>` or `<textarea>`.
    ```html
    <input type="text" minlength="5">
    ```

13. **multiple**:
    - Indicates whether multiple values can be entered in an `<input type="email">` or `<input type="file">`.
    ```html
    <input type="file" multiple>
    ```

14. **pattern**:
    - Defines a regular expression against which the `<input>` value is checked.
    ```html
    <input type="text" pattern="[A-Za-z]{3}">
    ```

15. **placeholder**:
    - Provides a hint to the user about what kind of information is expected in the input field.
    ```html
    <input type="text" placeholder="Enter your name">
    ```

16. **readonly**:
    - Indicates that the input field is not editable, but unlike `disabled`, it will still be submitted with the form.
    ```html
    <input type="text" readonly value="Read-only text">
    ```

17. **rel**:
    - Specifies the relationship between the current document and the linked document/resource. Commonly used with `<a>` and `<link>` elements.
    ```html
    <a href="https://example.com" rel="noopener noreferrer">Link</a>
    ```

18. **required**:
    - Indicates that the input field must be filled out before submitting the form.
    ```html
    <input type="text" required>
    ```

19. **size**:
    - Specifies the visible width, in characters, of an `<input>` element.
    ```html
    <input type="text" size="10">
    ```

20. **step**:
    - Defines the legal number intervals for an `<input>` element of type `number` or `range`.
    ```html
    <input type="number" step="5">
    ```

### Global Attributes

1. **accesskey**:
   - Provides a hint for generating a keyboard shortcut for the current element. The browser typically uses this attribute to enable keyboard navigation.
   ```html
   <button accesskey="h">Help</button>
   ```

2. **anchorExperimentalNon-standard**:
   - This is not a standard attribute and may refer to experimental or proprietary features specific to certain browsers or environments.

3. **autocapitalize**:
   - Controls whether and how text input is automatically capitalized as it is entered/edited by the user.
   ```html
   <input type="text" autocapitalize="words">
   ```

4. **autofocus**:
   - This Boolean attribute lets you specify that an element should automatically get focus when the page loads.
   ```html
   <input type="text" autofocus>
   ```

5. **class**:
   - Used to specify one or more classnames for an element, which can be used by CSS and JavaScript to perform various tasks.
   ```html
   <div class="container"></div>
   ```

6. **contenteditable**:
   - Indicates whether the content of the element can be edited directly by the user.
   ```html
   <div contenteditable="true">Edit me!</div>
   ```

7. **data-***:
   - Allows us to store custom data private to the page or application, on any HTML element.
   ```html
   <div data-user="12345" data-status="active"></div>
   ```

8. **dir**:
   - Specifies the text directionality of the element's content.
   ```html
   <p dir="rtl">This is a paragraph in a right-to-left language.</p>
   ```

9. **draggable**:
   - Defines whether the element can be dragged.
   ```html
   <img src="logo.png" draggable="true">
   ```

10. **enterkeyhint**:
    - Provides a hint to the browser on what the enter key could do. It helps in optimizing the keyboard interface.
    ```html
    <input enterkeyhint="send">
    ```

11. **exportparts**:
    - This attribute allows a custom element to expose CSS Shadow Parts in a way that they can be styled directly with stylesheets.
    ```html
    <my-element exportparts="partname"></my-element>
    ```

12. **hidden**:
    - Indicates that the element is not yet, or is no longer, relevant.
    ```html
    <div hidden>This content is hidden.</div>
    ```

13. **id**:
    - Defines a unique identifier for the element.
    ```html
    <div id="header"></div>
    ```

14. **inert**:
    - Indicates that the element and all of its focusable descendants are not focusable.
    ```html
    <div inert>Content not interactive.</div>
    ```

15. **inputmode**:
    - Provides a hint to browsers for devices with on-screen keyboards to help them decide which keyboard to display.
    ```html
    <input inputmode="numeric">
    ```

16. **is**:
    - Used for attaching custom behavior to an element.
    ```html
    <button is="custom-button"></button>
    ```

17. **itemid**, **itemprop**, **itemref**, **itemscope**, **itemtype**:
    - These attributes are part of the Microdata specification which allows you to nest metadata within existing content on web pages.
    ```html
    <div itemscope itemtype="http://schema.org/Person">
      <span itemprop="name">Jane Doe</span>
    </div>
    ```

18. **lang**:
    - Specifies the language of the element’s content.
    ```html
    <p lang="en">Hello, world!</p>
    ```

19. **nonce**:
    - A security feature in browsers that ensures that scripts are allowed to execute.
    ```html
    <script nonce="2726c7f26c">
    ```

20. **part**:
    - Allows for style encapsulation by letting an element expose one or more parts for styling purposes.
    ```html
    <my-widget part="header"></my-widget>
    ```

21. **popover**:
    - Not a standard attribute, possibly used in frameworks or libraries for UI enhancements.

22. **slot**:
    - Used in Web Components, it assigns a slot in a shadow DOM.
    ```html
    <span slot="header">This is a header.</span>
    ```

23. **spellcheck**:
    - Specifies whether the element is to have its spelling and grammar checked or not.
    ```html
    <textarea spellcheck="true"></textarea>
    ```

24. **style**:
    - Contains CSS styling declarations to be applied to the element.
    ```html
    <div style="color: blue;">This text is blue.</div>
    ```

25. **tabindex**:
    - Indicates if its element can be focused, and if/where it participates in sequential keyboard navigation.
    ```html
    <div tabindex="0">Focusable Div</div>
    ```

26. **title**:
    - Contains a text representing advisory information related to the element it belongs to.
    ```html
    <abbr title="Hypertext Markup Language">HTML</abbr>
    ```

27. **translate**:
    - Specifies whether the content of an element should be translated or not.
    ```html
    <p translate="no">Bonjour</p>
    ```

### Input Types

1. **button**
3. **color**
4. **date**
5. **datetime-local**
6. **email**
7. **file**
8. **hidden**
9. **image**
10. **month**
11. **number**
12. **password**
13. **radio**
14. **range**
15. **reset**
16. **search**
17. **submit**
18. **tel**
19. **text**
20. **time**
21. **url**
22. **week**

### References

- [MDN Web Docs](https://developer.mozilla.org/)

---

# CSS

## CSS Guide for Frontend Developers not for Designers

### FONTS & TEXTS or TYPOGRAPHY

1. `text-align` - Aligns text horizontally within an 
```css
text-align : left / right / center;
```
2. `text-decoration` - Adds decoration to text (like underline, line-through).
```css
text-decoration : none / underline / overline / line-through;
```
3. `font-weight` - Sets the weight (or thickness) of the font.
```css
font-weight : normal / bold / bolder / lighter / 100 - 900;
```
4. `font-family` - Specifies the font for the text.
```css
font-family : Arial, sans-serif;
```
5. `text-transform` - Controls the capitalization of text.
```css
text-transform : none / capitalize / uppercase / lowercase;
```
6. `line-height` - Controls the space between lines of text.
```css
line-height : 2px / 2em / 2% / 2;
line-height : normal;
```
7. `font-size` - Defines the size of the font.
```css
font-size : 12px / 1em / 100%;
```
8. `font-style` - Specifies the style of the font (e.g., italic).
```css
font-style : normal / italic / oblique;
```
9. `text-shadow` - Adds shadow to text.
```css
text-shadow : 1px 1px 1px #000;
```
10. `letter-spacing` - Controls the space between characters.
```css
letter-spacing : 2px;
```
11. `word-spacing` - Controls the space between words.
```css
word-spacing : 2px;
```

---
### BOX MODEL

![Box model](https://upload.wikimedia.org/wikipedia/commons/7/7a/Boxmodell-detail.png)

- **Margin**
- **Padding**
- **Border**
- **Width**
- **Height**

```css
.box {
    -- clockwise --
    margin: 10px;  // margin: 10px 20px 30px 40px;  
    padding: 10px; // padding: 10px 20px 30px 40px;
    border: 1px solid #000;
    width: 100px/ 100% etc;
    height: 100px / 100% etc;
}
```

### COLORS 

- **HEX** `#000000`
```css
p {
    color: #000000;
}
```
- **RGB** `rgb(0, 0, 0)`
```css
p {
    color: rgb(0, 0, 0);
}
```
BONUS TIP:

- **Hue**: A pure color
- **Tint**: A pure color with
just white added
- **Shade**: a pure color with
just black added
4
- **Tone**: A pure color with
just grey added

### CSS UNITS

- **Absolute Units**
    - `in` - inches
    - `px` - pixels
    - `pt` - points
- **Relative Units**
    - `em` - relative to the font-size of the element
    - `rem` - relative to the font-size of the root element
    - `vw` - relative to 1% of the width of the viewport
    - `vh` - relative to 1% of the height of the viewport

### DISPLAY

- **inline** - Takes only the space required by the element. (no margin/ padding)
- **block** - Takes full space available in width.
- **inline-block** - Similar to inline but we can set margin & padding.
- **none** - To remove element from document flow.

```css
.box {
    display: inline / block / inline-block / none;
}
```

### POSITION

- **static** - Default position.
- **relative** - Relative to its normal position.
- **absolute** - Relative to the nearest positioned ancestor.
- **fixed** - Relative to the viewport.
- **sticky** - Based on user's scroll position.

```css
.box {
    position: static / relative / absolute / fixed / sticky;
}
```
- **z-index** - Specifies the stack order of an element.
```css
.box {
    z-index: 1;
}
```

### FLEXBOX & GRID
- **Flexbox** - For one-dimensional layout.
Reference: [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

![Flexbox](https://css-tricks.com/wp-content/uploads/2022/02/css-flexbox-poster.png)

- **Grid** - For two-dimensional layout.
Reference: [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

![Grid](https://css-tricks.com/wp-content/uploads/2022/02/css-grid-poster.png)

### DESIGN PRINCIPLES MOBILE FIRST & RESPONSIVE DESIGN FOR ALL DEVICES

![Design](design-ui-ux.svg "UI-UX Design")

### CSS Library and Framework

http://tailwindcss.com/

https://ui.shadcn.com/

https://daisyui.com/

 https://react-spectrum.adobe.com/

https://shoelace.style/

https://mui.com/

PRO - https://ant.design/
# JavaScript 

![Clear-code](clear-code.png "best pratice to write clean code")

### Essential Web APIs to Learn basic only then move on to Library and Framework

- **Graphics and Visualization or Document Manipulation**
    - DOM API : Connects web pages to scripts.
    - HTML DOM : Represents web pages.
    - History API : Manipulates browser history.
    - Canvas API  : Creates 2-D graphics and animations.
    - SVG : Handles scalable vector graphics.
    
    Alternative :
    
     Libraries and Frameworks   ⇒ React js, Fabric js , Snap svg
    
- **Network and Communication**
    - Fetch API : Performs network requests.
        
        Alternative → https://axios-http.com/docs/intro
        
    - Web Sockets API : Handles persistent connections for real-time communication
        
         Alternative → https://socket.io/ 
        
    - WebRTC : Handles real-time audio/video communication.
- **User Interaction and Notifications**
    - Geolocation API : Accesses user location data.
        
         https://leafletjs.com/ 
        
        https://mapsplatform.google.com/
        
    - Web Notifications API : Displays notifications.
        
        https://onesignal.com/
        
    - Pointer Events : Handles pointer events.
- **Storage and Data Management**
    - Web Storage API : Manages client-side storage.
- **Audio/Video and Media**
    - Audio/Video APIs : Handles audio and video processing.
    - Web Audio API : Processes and synthesizes audio.
    - WebRTC
        - Media Capture and Streams
        - MediaStream Recording

# **How to make Web App**

**User Interface** - how users will consume and interact with your application.

**Routing** - how users navigate between different parts of your application.

**Data Fetching** - where your data lives and how to get it.

**Rendering** - when and where you render static or dynamic content.

**Integrations** - what third-party services you use (for CMS, auth, payments, etc.) and how you connect to them.

**Infrastructure** - where you deploy, store, and run your application code (serverless, CDN, edge, etc.).

**Performance** - how to optimize your application for end-users.

**Scalability** - how your application adapts as your team, data, and traffic grow.

**Developer Experience** - your team's experience building and maintaining your application.