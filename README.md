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
### Style1
![style1](https://user-images.githubusercontent.com/31176739/29673587-5e29ba80-88f8-11e7-824b-66e7672e81a7.PNG)

Put this code into your page to use Style1:
```
<div class="style1">
    <label>
        <input type="radio" name="style1">
        <span>Style1</span>
    </label>
</div>
```
#### Style1 Modifiers
To modify Style1 buttons you have a variety of color classes available to use with it: `.blue`, `.green`, `.yellow`, `.pink`, `.purple`, `.customColor`. Place any of these modifiers as a class on the label tag.
### Style2
![style2](https://user-images.githubusercontent.com/31176739/29673588-5e2c2e00-88f8-11e7-9066-c4e1b1afcc76.PNG)

Put this code into your page to use Style2:
```
<div class="style2">
    <label>
        <input type="radio" name="style2">
        <span>Style2</span>
    </label>
</div>
```
#### Style2 Modifiers
To modify Style2 buttons you have a variety of color classes available to use with it: `.blue`, `.green`, `.yellow`, `.pink`, `.purple`, `.customColor`. Place any of these modifiers as a class on the label tag.
### Style3
![style3](https://user-images.githubusercontent.com/31176739/29673589-5e2e52ac-88f8-11e7-8a2d-683c625fcc39.PNG)

Put this code into your page to use Style3:
```
<div class="style3">
	<input type="radio" name="style3" id="option1" value="option1">
	<label for="option1">Option 1</label>
	<input type="radio" name="style3" id="option2" value="option2">
	<label  for="option2">Option 2</label>
</div>
```
### Style4
![style4](https://user-images.githubusercontent.com/31176739/29673590-5e307b04-88f8-11e7-8400-9ab2508d78dd.PNG)

Put this code into your page to use Style4:
```
<div class="style4">
    <input id="radio-1" name="style4" type="radio" checked>
    <label for="radio-1">Checked</label>
    <input id="radio-2" name="style4" type="radio">
    <label  for="radio-2">Unchecked</label>
    <input id="radio-3" name="style4" type="radio" disabled>
    <label for="radio-3">Disabled</label>
</div>
```
### Style5
![style5](https://user-images.githubusercontent.com/31176739/29673594-62662980-88f8-11e7-9e6d-4793cbe5719c.PNG)

Put this code into your page to use Style5:
```
<div class="style5">
	<label>
		<input type="radio" name="style5" checked/>
		<div class="icon1">
			<span>Option 1</span>
		</div>
	</label>
	<label>
		<input type="radio" name="style5"/>
		<div class="icon2">
			<span>Option 2</span>
		</div>
	</label>
</div>
```
Then in your css file add this:
```
.style5 .icon1 span:before {
  content: '\f121'; }

.style5 .icon2 span:before {
  content: '\f1c0'; }
```
and replace the content selector with a font awesome unicode
### Style6
![style6](https://user-images.githubusercontent.com/31176739/29673596-62702c78-88f8-11e7-835a-828314efad89.PNG)

Put this code into your to use Style6:
```
<div class="style6">
	<label>
		<input type="radio" name="style6" checked />
		Radio option
	</label>
	<label>
		<input type="radio" name="style6" />
		Radio option
	</label>
	<label>
		<input type="radio" name="style6" />
		Radio option
	</label>
</div>
```
# W.I.P 
## This version of styledradio.css is using all new classes and IDs and won't be compatible with version 1.1.0 or previous versions
