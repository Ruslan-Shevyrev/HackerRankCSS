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

<table>
  <tr>
    <td valign="center" width="49%"><img src="https://github.com/Ruslan-Shevyrev/Ruslan-Shevyrev/blob/main/logoRS/logo_mini.gif" title="logo"></td>
    <td valign="center" width="49%"><img src="https://github.com/Ruslan-Shevyrev/Ruslan-Shevyrev/blob/main/logoRS/logoRS_FULL.png" title="RuslanShevyrev"></td>
  </tr>
</table>