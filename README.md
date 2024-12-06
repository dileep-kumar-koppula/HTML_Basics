# HTML Basics

## HTML Version 5

### Heading 1
This is an example of **Heading 1**.

### Heading 4
This is an example of **Heading 4**.

### Heading 6
This is an example of **Heading 6**.

#### My first paragraph
This is an example of the first paragraph in HTML.

---

### Links

- [Duckduckgo](https://duckduckgo.com/)
- [Visit W3Schools!](https://www.w3schools.com/)

---

### Absolute URLs

- [W3C](https://www.w3.org/)
- [Google](https://www.google.com/)

---

### Relative URLs

- [HTML Images](html_images.asp)
- [CSS Tutorial](css/default.asp)

---

### Images

![HTML tutorial](smiley.gif)
![Italian Trulli](pic_trulli.jpg)
![Girl in a jacket](img_girl.jpg)
![Flowers in Chania](img_chania.jpg)

- ![Alternate Text](url)
- ![Flowers in Chania](img_chania.jpg)
- ![Girl with a jacket](img_girl.jpg)
- ![Flowers in Chania](img_chania.jpg)
- ![Flowers in Chania](wrongname.gif)
- ![Girl in a jacket](img_girl.jpg){:style="width:500px;height:600px;"}
- ![Girl in a jacket](img_girl.jpg){:width="500" height="600"}

---

### Button Example

- [HTML Tutorial](default.asp)

---

### Styling Example

- **Right-aligned Image**  
  ![Smiley face](smiley.gif){:style="float:right;width:42px;height:42px;"}
  The image will float to the right of the text.

- **Left-aligned Image**  
  ![Smiley face](smiley.gif){:style="float:left;width:42px;height:42px;"}
  The image will float to the left of the text.

---

### Text Styles

- This is a **red** paragraph.
- This is a paragraph with a **tooltip**.

---

### Additional Styles

- `This is bold text`
- **This is important text!**
- *This is italic text*
- _This is emphasized text_
- Smaller text: `This is some smaller text.`
- Do not forget to buy **milk** today.
- My favorite color is ~~blue~~ red.
- My favorite color is ~~blue~~ **red**.
- This is `subscripted` text.

---

## Body Styling Examples

```html
<body style="background-color:powderblue;">
    <p>This is a paragraph</p>
    <p>This is another paragraph</p>
    <h1 style="background-color:powderblue;">This is a heading</h1>
    <p style="background-color:tomato;">This is a paragraph.</p>
    <h1 style="font-family:verdana;">This is a heading</h1>
    <p style="font-family:courier;">This is a paragraph.</p>
    <h1 style="font-size:300%;">This is a heading</h1>
    <p style="font-size:160%;">This is a paragraph.</p>
    <h1 style="text-align:center;">Centered Heading</h1>
    <p style="text-align:center;">Centered paragraph.</p>
    <b>This text is bold</b>
    <strong>This text is important!</strong>
    <i>This text is italic</i>
    <em>This text is emphasized</em>
    <small>This is some smaller text.</small>
    <p>Do not forget to buy <mark>milk</mark> today.</p>
    <p>My favorite color is <del>blue</del> red.</p>
    <p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
    <p>This is <sub>subscripted</sub> text.</p>
</body>
