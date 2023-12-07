# BharatPe UI/UX (HTML/CSS)

BharatPe Website clone Project,
Following concepts are used....

# HTML Tags

HTML (Hypertext Markup Language) is the standard language for creating web pages. It consists of tags that define the structure and content of a web page. In Markdown, you can include HTML tags to enhance your document.

## Types of HTML Tags

### 1. **Block-level Tags:**

Block-level tags define the structure of the document and typically start on a new line. Examples include:

```html
<div>
  - Defines a division or a section.
  <p>- Defines a paragraph.</p>
  <h1>
    ,
    <h2>
      , ...,
      <h6>
        - Define headings of different levels.
        <ul>
          - Defines an unordered list.
          <ol>
            - Defines an ordered list.
            <li>
              - Defines a list item.

              <a>
                - Defines a hyperlink.
                <strong>
                  - Defines strong importance (bold).
                  <em>
                    - Defines emphasized text (italic).
                    <span>
                      - Defines a section in a document. <img /> - Defines an
                      image.</span
                    ></em
                  ></strong
                ></a
              >
            </li>
          </ol>
        </ul>
      </h6>
    </h2>
  </h1>
</div>
```

# Semantic HTML Tags

Semantic HTML tags provide information about the structure and content of the document, making it more accessible and meaningful for both browsers and developers.

Examples of Semantic Tags

## 1. <header>

The <header> tag represents the header of a section or a page. It can contain headings, logos, navigation menus, etc.

## 2. <nav>

The <nav> tag defines a set of navigation links.

## 3. <article>

The <article> tag represents a self-contained piece of content that could be distributed and reused independently, such as a news article.

## 4. <section>

The <section> tag defines a section in a document, often used with the <h1> to <h6> tags to define the heading for that section.

## 5. <aside>

The <aside> tag represents content that is tangentially related to the content around it, like a sidebar.

## 6. <footer>

The <footer> tag represents the footer of a section or a page. It can contain metadata, copyright information, etc.

Semantic tags enhance the document's structure and help assistive technologies and search engines better understand the content.

# Cascading Style Sheets (CSS)

CSS is a stylesheet language used for describing the look and formatting of a document written in HTML or XML. It enables the separation of content and presentation, allowing developers to style web pages.

## Selectors

Selectors in CSS are patterns that select and style HTML elements. They define which elements in the HTML document will be affected by the style rules.

### 1. **Universal Selector (`*`)**

The universal selector selects all elements on a page.

```css
* {
  margin: 0;
  padding: 0;
}

2. Type Selector Selects elements of a specific type. p {
  color: #333;
}

3.
  Class
  Selector
  (.classname)
  Selects
  elements
  with
  a
  specific
  class
  attribute.
  .button {
  background-color: #007bff;
  color: #fff;
}

4.
  ID
  Selector
  (#id)
  Selects
  a
  single
  element
  with
  a
  specific
  id
  attribute.
  #header {
  font-size: 24px;
}

5.
  Descendant
  Selector
  Selects
  all
  elements
  that
  are
  descendants
  of
  a
  specified
  element.
  article
  p {
  font-style: italic;
}

6.
  Attribute
  Selector
  Selects
  elements
  based
  on
  their
  attribute
  values.
  input[type="text"] {
  border: 1px solid #ccc;
}
```

# CSS Pseudo-classes and Pseudo-elements

CSS pseudo-classes and pseudo-elements are selectors that allow you to style elements based on their state or position in the document. They provide a way to select and style elements that cannot be expressed with regular element selectors.

## Pseudo-classes

Pseudo-classes are used to define styles for specific states of elements. They are prefixed with a colon (`:`) in CSS.

### 1. **`:hover`**

The `:hover` pseudo-class is used to select and style an element when the user hovers over it.

```css
a:hover {
  color: #ff4500; /* Change text color when hovering over a link */
}

2.
  :active
  The
  :active
  pseudo-class
  selects
  and
  styles
  an
  element
  when
  it
  is
  being
  activated
  (clicked or pressed).
  button:active {
  background-color: #008000; /* Change button color when clicked */
}

4.
  :nth-child()
  The
  :nth-child()
  pseudo-class
  allows
  you
  to
  select
  and
  style
  elements
  based
  on
  their
  position
  in
  a
  parent
  element.
  li:nth-child(odd) {
  background-color: #f2f2f2; /* Style odd list items with a background color */
}

li:nth-child(odd) {
  background-color: #f2f2f2; /* Style odd list items with a background color */
}
```

## Pseudo-elements

Pseudo-elements are used to style specific parts of an element. They are also prefixed with a colon (:) in CSS.

```css
1.
  ::before
  and
  ::after
  The
  ::before
  and
  ::after
  pseudo-elements
  are
  used
  to
  insert
  content
  before
  and
  after
  the
  content
  of
  an
  element,
respectively. p::before {
  content: "» "; /* Add a double angle quote before each paragraph */
}

2.
  ::first-line
  and
  ::first-letter
  The
  ::first-line
  pseudo-element
  selects
  the
  first
  line
  of
  a
  block-level
  element,
and
  ::first-letter
  selects
  the
  first
  letter
  of
  a
  block-level
  element.
  p::first-line {
  font-weight: bold; /* Make the first line of a paragraph bold */
}

p::first-letter {
  font-size: 150%; /* Increase the font size of the first letter */
}

3.
  ::selection
  The
  ::selection
  pseudo-element
  allows
  you
  to
  style
  the
  portion
  of
  text
  that
  is
  selected
  by
  the
  user.
  ::selection {
  background-color: #ffff66; /* Change the background color of selected text */
}

::selection {
  background-color: #ffff66; /* Change the background color of selected text */
}
```

# Screen Shots

![alt text](./screenshots/2.png)
![alt text](./screenshots/3.png)
![alt text](./screenshots/4.png)
![alt text](./screenshots/5.png)
![alt text](./screenshots/6.png)
![alt text](./screenshots/7.png)
![alt text](./screenshots/8.png)
![alt text](./screenshots/9.png)
![alt text](./screenshots/10.png)
![alt text](./screenshots/11.png)
![alt text](./screenshots/12.png)
![alt text](./screenshots/13.png)
![alt text](./screenshots/14.png)
![alt text](./screenshots/15.png)
![alt text](./screenshots/16.png)
![alt text](./screenshots/17.png)
![alt text](./screenshots/18.png)
![alt text](./screenshots/19.png)
![alt text](./screenshots/21.png)
![alt text](./screenshots/22.png)
![alt text](./screenshots/23.png)
![alt text](./screenshots/24.png)
![alt text](./screenshots/25.png)
![alt text](./screenshots/26.png)
![alt text](./screenshots/27.png)
![alt text](./screenshots/28.png)
![alt text](./screenshots/1.png)
