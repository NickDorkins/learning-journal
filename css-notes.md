## Chapter 10 Notes: Inroducing CSS

### Introduce you to how CSS works
### Teach you how to write CSS rules
### Show you how CSS rules apply to HTML pages

- Block level elements look
like they start on a new line. Examples include the `<h1>- <h6>, <p> and <div>` elements.
- Inline elements flow within the text and do not start on a new line. Examples include `<b>, <i>, <img>, <em> and <span>.`

#### Example Styles:
- **Boxes**
    - Width and height
    - Borders (color, width, and style) Background color and images
    - Position in the browser window.
- **text**
    - Typeface
    - Size
    - Color
    - Italics, bold, uppercase, lowercase, small-caps
- **Specific**
    - There are also specific ways in which you can style certain elements such as lists, tables, and forms.

- **Selectors** 
    - indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
- **Declarations** 
    - indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.
- **Properties** 
    - indicate the aspects of the element you want to change. For example, color, font, width, height and border.
- **Values** 
    - specify the settings you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be.
- **link**
    - The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the `<head>` element. It should use three attributes:
- **href**
    - This specifies the path to the CSS file (which is often placed in a folder called css or styles).
- **type**
    - This attribute specifies the type of document being linked to. The value should be text/css.
- **rel**
    - This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

- **style**
    - The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.

- **Last rule**
    - If the two selectors are identical, the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.
- **Specificty**
    - If one selector is more specific than the others, the more specific rule will take precedence over more general ones. 
- **Important**
    - You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

## Chapter 11: Color

### How to specify colors, as there are three common ways in which you can indicate your choice of colors (plus extra ways made available in CSS3)

### Color terminology, as there are some terms that are very helpful to understand when it comes to picking colors

### Contrast, and ensuring that your text is readable

### Background colors for behind either your entire page or parts of a page

- **rgb values**
    - These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
- **hex Codes**
    - These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
- **Color names**
T   - here are 147 predefined color names that are recognized
by browsers. For example: DarkCyan
- **Comments**
    - Anything between the /* symbols and the */ symbols will not be interpreted by the browser.
- **background-color**
    - CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
    - You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page).
    - We have also used the padding property to separate the text from the edges of the boxes.
- **Color**
    - Color picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B.
    - The hex value is provided next to the pound or hash # symbol. There is also a good color picking tool at: 
    - colorschemedesigner.com
    - color.adobe.com/create/color-wheel

    - **RGB Values**
        - Values for red, green, and blue are expressed as numbers between 0 and 255.
    - **Hex Codes**
        - Hex values represent values for red, green, and blue in hexadecimal code. 
    - **Color Names**
        - Colors are represented by predefined names. However, they are very limited in number.
    - **Hue**
        - Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as well as hue.
    - **satuRatioN**
        - Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.
    - **BRiGHtNess**
        - Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.
