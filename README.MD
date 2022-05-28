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
:x: .greyBall:focus {transform: scale(2); transition: 0.5s;}\

# :two: CSS object-fit