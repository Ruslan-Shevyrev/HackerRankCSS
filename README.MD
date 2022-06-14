# :one:
```
<style>
div{
	height:50px;
	width:50px;
	background:red;
	border-radius:50%;
}
</style>
<div class="grayBall"></div>
```
:x: .greyBall:hover {transform: scale(2); animate: 500ms;}\
:heavy_check_mark: .greyBall:hover {transform: scale(2); transition: 500ms transform;}\
:heavy_check_mark: .greyBall:hover {transform: scale(2); transition: 0.5s;}\
:x: .greyBall:focus {transform: scale(2); transition: 0.5s;}

<img src="/Answer_images/Answer_1.png" title="answer_1">

# :two: CSS Ellipsis

## Which of the following are true about CSS property 'object-fit'?

:x: 'object-fit: contain;' does not preserve the aspect ratio of the image; it stretches the image to civer the entry width and height of the container.\
:heavy_check_mark: 'object-fit: contain;' preserve the aspect ratio of the image and makes sure no clipping happens to the whole image.\
:heavy_check_mark: 'object-fit: cover;' avoids the image getting squeezed, but it could end up clipping the image.\
:x: 'object-fit: cover;' avoids clipping the image by sacrificing the aspect ratio.

<img src="/Answer_images/Answer_2.png" title="answer_2">

# :three: CSS object-fit

## If an element extends beyond the allocated width, how do you truncate the sentence with an ellipsis (...) using CSS?

## For example, "Hello! I am an element, and my width is larger than the container..."

:x: {white-space: pre-wrap; overflow: ellipsis; }\
:x: {text-overflow: ellipsis; white-space: wrap; visibility: hidden;}\
:heavy_check_mark: {white-space: nowrap; overflow: hidden; text-overflow:ellipsis}\
:x: None of the above

<img src="/Answer_images/Answer_3.png" title="answer_3">

# :four: CSS Text Coloring

## WHich of the following renders the text red?

```
<p id="tagID">Please color me red</p>
```
:x: :root{--test-color: red;} p{color:--test-color;}\
:x: :root{--test-color: red;} p{color:var(--test-color);}\
:heavy_check_mark: #tagId {color: red;}p{color:blue;}\
:heavy_check_mark: p{colorLred !important;} #tagId{color:blue;}

<img src="/Answer_images/Answer_4.png" title="answer_4">

# :five: CSS selection

## How do you prevent the user from selecting the text rendered insidethe following element?

```
<p> should not be selectable</p>
```

:x: p{cursor-event: none;}\
:x: p{pointer-events: none;}\
:heavy_check_mark: p{user-select: none;}\
:x: None of the above

<img src="/Answer_images/Answer_5.png" title="answer_5">

# :six: CSS input Placeholder

## How do yiu hide the "placeholder" text of an <input> field?

:x: input::placeholder{visibility:clip;}\
:heavy_check_mark: input::placeholder{color: transparent;}\
:x: input::placeholder{display: none;}\
:x: input::placeholder{visibility:hidden};

<img src="/Answer_images/Answer_6.png" title="answer_6">

# :seven: CSS Centering

## Which of the following options can position the div with the class name "child" exactly at the center of the page?

```
<div class="parent" style="width: 100vw; height: 100vh;">
	<div class="child" style="height: 100px; width: 100px; background: black"></div>
</div>
```

:x: .parent{display: flex; justify-content: center; align-items: center;}\
:x: .parent{display: flex; justify-content: center; align-self: center;}\
:x: .parent{position: relative;}.child{position: absolute; top: 50%; ;left: 50%;}\
:heavy_check_mark: .parent{position: relative;}.child{position: absolute; top: 50%; ;left: 50%; transform-translate(-50%, -50%);}

<img src="/Answer_images/Answer_7.png" title="answer_7">

# :eight: CSS Vertical-align

## Which of the following are true about the CSS property 'vertical-align'?

```
<p>
	Let's
	<span class="heroWord">Hack</span>
	<img src=""/>
</p>
```

:x: .heroWord{vertical-align: 25px;} moves the word "Hack" to the bottom, 25px lower then ```<p>``` tag.\
:x: .heroWord{vertical-align: 25px;} moves the word "Hack" to the top, 25px higher then ```<p>``` tag.\
:heavy_check_mark: p img{vertical-align: text-bottom;} moves the image to the bottom with respect to the ```<p>``` tag.\
:x: p img{vertical-align: text-bottom;} has no effect on the ```<img>``` tag.

<img src="/Answer_images/Answer_8.png" title="answer_8">

<table>
  <tr>
    <td valign="center" width="49%"><img src="https://github.com/Ruslan-Shevyrev/Ruslan-Shevyrev/blob/main/logoRS/logo_mini.gif" title="logo"></td>
    <td valign="center" width="49%"><img src="https://github.com/Ruslan-Shevyrev/Ruslan-Shevyrev/blob/main/logoRS/logoRS_FULL.png" title="RuslanShevyrev"></td>
  </tr>
</table>