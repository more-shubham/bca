# Web Programming - Lab Notes

#### 1. `<title>` Tag
- **Description**: Specifies the title of the document, shown in the browser's title bar or tab.
- **Usage**: `<title>Your Page Title</title>`

#### 2. `<body>` Tag
- **Description**: Contains the content of an HTML document, such as text, images, links, and other elements.
- **Usage**: 
  ```html
  <body>
    <!-- Your content here -->
  </body>
  ```

#### 3. `<font>` Tag (Deprecated in HTML5)
- **Attributes**:
  - `size`: Specifies the font size.
  - `color`: Specifies the font color.
  - `face`: Specifies the font typeface.
- **Usage**: 
  ```html
  <font size="4" color="red" face="Arial">Sample Text</font>
  ```

#### 4. `<p>` Tag
- **Description**: Defines a paragraph.
- **Attribute**:
  - `align`: Specifies the alignment of the paragraph (left, right, center, justify).
- **Usage**:
  ```html
  <p align="center">This is a centered paragraph.</p>
  ```

#### 5. Text Formatting Tags
- **Bold**: `<b>Bold Text</b>`
- **Italic**: `<i>Italic Text</i>`
- **Subscript**: `<sub>Subscript Text</sub>`
- **Superscript**: `<sup>Superscript Text</sup>`

#### 6. `<center>` Tag (Deprecated in HTML5)
- **Description**: Centers the content.
- **Usage**:
  ```html
  <center>This text is centered.</center>
  ```

#### 7. `<img>` Tag
- **Description**: Embeds an image in the document.
- **Attributes**:
  - `src`: Specifies the path to the image.
  - `alt`: Provides alternative text for the image.
  - `width` and `height`: Specifies the dimensions of the image.
- **Usage**:
  ```html
  <img src="image.jpg" alt="Description" width="500" height="300">
  ```

#### 8. `<a>` Tag
- **Description**: Defines a hyperlink.
- **Attribute**:
  - `href`: Specifies the URL of the linked document.
- **Usage**:
  ```html
  <a href="http://www.example.com">Visit Example</a>
  ```

#### 9. `<table>` Tag
- **Description**: Creates a table.
- **Related Tags**:
  - `<tr>`: Defines a row.
  - `<td>`: Defines a cell.
  - `<th>`: Defines a header cell.
- **Usage**:
  ```html
  <table border="1">
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
  </table>
  ```

#### 10. `<frameset>` and `<frame>` Tags (Deprecated in HTML5)
- **Description**: Used to divide the browser window into multiple frames.
- **Usage**:
  ```html
  <frameset cols="50%,50%">
    <frame src="frame_a.html">
    <frame src="frame_b.html">
  </frameset>
  ```

#### 11. Definition List (`<dl>`, `<dt>`, `<dd>` Tags)
- **Description**: Used for a list of terms and their definitions.
- **Usage**:
  ```html
  <dl>
    <dt>Term 1</dt>
    <dd>Definition of Term 1</dd>
    <dt>Term 2</dt>
    <dd>Definition of Term 2</dd>
  </dl>
  ```

#### 12. Nested List
- **Description**: Lists within lists.
- **Usage**:
  ```html
  <ul>
    <li>Item 1
      <ul>
        <li>Subitem 1</li>
        <li>Subitem 2</li>
      </ul>
    </li>
    <li>Item 2</li>
  </ul>
  ```

#### 13. Ordered List (`<ol>`)
- **Description**: Creates a list with numbered items.
- **Usage**:
  ```html
  <ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
  </ol>
  ```

#### 14. Unordered List (`<ul>`)
- **Description**: Creates a list with bullet points.
- **Usage**:
  ```html
  <ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
  </ul>
  ```

These notes cover the essential HTML tags and attributes you mentioned. You can add more details or examples as needed.
