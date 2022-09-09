Common block elements are:
<p> Paragraph Element
<h1> - <h6> Heading Element
<div> Container ELement
<ol>, <ul> <li> List Element
<form> Form Element
Block element takes the width of whole page 
<span> tag can be used in block element to do something 
<span> is inline display element
	inline display element only takes space that needs to

Common Inline elements are:
<span></span>
<a href=""></a>
<img src="">

We cannot change the size of the inline element.

We can change the display value of in element
like we can change the 
display:inline;
of any paragraph but we will lose the ability to change size.

There is another type of dicplay element with is called inline block.

p{

	display: inline-block;
}

it will allow us to chnage the width and maintain in same line.

We can also change the display type to none
.second-p{
	display: none;
}

It willl remove the element from the website like it does not exist.



We can hide the answer from the quiz page like it never existed by using display none
.answer{
	display: none;
}

or by using another property called visibility hidden

.answer{
	visibility: hidden;
}



To centering the elements
https://developer.mozilla.org/en-US/docs/Web/CSS/margin
margin: 0 auto 0 auto; also for center
h1{
	width: 10%;
	margin: 0 auto;
}  for centre
