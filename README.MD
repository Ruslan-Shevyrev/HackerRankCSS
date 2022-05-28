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

# :two: CSS object-fit
## Which of the following are true about CSS property 'object-fit'?

:x: 'object-fit: contain;' does not preserve the aspect ratio of the image; it stretches the image to civer the entry width and height of the container.\
:heavy_check_mark: 'object-fit: contain;' preserve the aspect ratio of the image and makes sure no clipping happens to the whole image.\
:heavy_check_mark: 'object-fit: cover;' avoids the image getting squeezed, but it could end up clipping the image.\
