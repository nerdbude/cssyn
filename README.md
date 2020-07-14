# cssyn (alpha_ver.0.2)

*A syntax highlighter written in CSS without any JavaScript*

![cpp_hello_world](/images/code_cpp.png)

I don´t want any JS on my website but I want a syntax-highlighter with all the funky colors of the iwtb-colorscheme. So here is the cssyn (or css syntax highlighter). 

It doesn´t highlight full automatic. You want syntax-highlighting - you have to do it yourself. Yes it is a bit more work on your website but it is totally worth it ... or not ... your decision.

## Installation

Just copy the cssyn.css to your /css folder and link it in your html-file with:

``` 
<link rel="stylesheet" type="text/css" href="/cssyn.css"> 
```

or copy the CSS Code in your existing *style.css* file.

## classes

The highlighting itself is defined in classes:

* .unixshell (if you want to show a terminal command)
* .comment
* .url
* .header-file
* .selector
* .subselector
* .value
* .unit


## how to use it

Before you highlight the code you can set a small label for the codebox.
Just use `<span class="label">C++</span>` and the language you choose will appear in a small flag on the top of the box.

You can use the syntax-highlighting within the `<div id="cssyn"> </div>` tag.
This contain the code block.

You define the lines included in numbering with te following ln-tag.
Every line between these text within the cssyn div container get a line number.
`<ln>   </ln>`

Now you can hightlight the code with a `<span>` tag and an class name:
`<span class="selector"> int </span>`


*example:*
```
<span class="label"> C++ </span>
<div id="cssyn">
	<ln><span class="comment"> /* HELLO WORLD */ </span></ln>
</div>

```

## want to do

[x] add linenumbers
[x] iwtb color-scheme

[ ] add more colorschemes
[ ] add more classes for highlighting
[ ] add single language classes

