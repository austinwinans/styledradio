# styledradio.css
A CSS framework to make radio buttons look like normal buttons
![screenshot](https://user-images.githubusercontent.com/31176739/29533055-bc167e2c-86b8-11e7-8c54-e025ba13fa1c.PNG)
## Getting Started
### Methods to download
- [Download the latest release](https://github.com/austinwinans/styledradio/archive/master.zip)
- Clone the repo: `git clone https://github.com/austinwinans/styledradio.git`
### How to use 
1. Move styledradio.css into your CSS folder
2. Import styledradio.css into your external CSS using `@import url("css/styledradio.css");`
    - Make sure to place this at the top of your stylesheet
3. Add this HTML to your page
```
<div id="buttons">
    <label class="colorStyle">
        <input type="radio" name="yourradiogroupname">
        <span>Your Text Goes Here</span>
    </label>
</div>
```
4. Replace the class `colorStyle` on the label tag with  `blueRectangle`, `greenRectangle`, `yellowRectangle`, `pinkRectangle`, `purpleRectangle`, `customcolorRectangle`,  `blueRounded`, `greenRounded`, `yellowRounded`, `pinkRounded`, `purpleRounded`, or `customcolorRounded`

This is what changes the color and shape of the button. The first half of the class is the color and the second half is the shape.
### Using `customcolorRectangle` and `customcolorRounded`
`customcolorRectangle` and `customcolorRounded` allow you to define your own colors that are not part of the presets. To use these add the following to your external CSS anywhere **after** the line where you've imported styledradio.css:
```
#buttons .customcolorRectangle {
    background-color: #f1c40f;
}
```
or
```
#buttons .customcolorRounded {
    background-color: #f1c40f;
}
```
Then replace the hex value of the `background-color` CSS property with a new color
## Advanced Usage
### Changing the `checked` color
To change the checked color add the following to your external CSS:
```
#buttons input:checked + span {
    background-color: #bdc3c7;
}
```
Then replace the `background-color` CSS property with a new color.
### Changing the button width
#### To make your buttons wider but still conform to the text length add the following to your external CSS
```
#buttons label span {
    padding: 8px 20px;
}
```
Then replace the 2nd `padding` CSS property pixel value to a larger value.
#### To make your buttons a fixed width disregarding text length add the following to your external CSS
```
#buttons label {
    width: 170px;
}
```
Then replace the `width` CSS property value with a new width.
### Manipulating the font
#### Changing the font
```
#buttons label span {
    font-family: sans-serif;
}
```
Then replace the `font-family` CSS property value with a different font.
#### Changing the font color
```
#buttons label span {
    color: #2c3e50
}
```
Then replace the `color` CSS property value with a new color.
#### Changing the font size
```
#buttons label span {
    font-size: 32px;
}
```
Then replace the `font-size` CSS property value to a smaller or larger value.
