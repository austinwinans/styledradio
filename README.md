# styledradio.css
A CSS framework to make radio buttons look like normal buttons
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
    background-color:#f1c40f;
}
```
or
```
#buttons .customcolorRounded {
    background-color:#f1c40f;
}
```
Then replace the hex value of the `background-color` CSS property with whatever color you'd like
