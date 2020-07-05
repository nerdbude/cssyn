# cssyn (alpha_ver.0.1)

*A syntax highlighter written in CSS without any JavaScript*

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

* .unixshell
* .comment
* .url
* .header-file
* .selector
* .subselector
* .value

*.unixshell*
If you want to show a terminal command you can use this class.

*.comment*
This class is for the comments.

*.url*
URL highlighting within code 

*.header-file*
i.e. the include in C++ code

*.selector*
the class for stuff like if, then, else etc.

*.subselector* 
for

## usage

You can use the syntax-highlighting with the `<div id="cssyn"> </div>` tag.
This contain the code block.

Within the code block you can use the `<span>` tag to highlight code.

*example:*

`<span class="comment"> /* simple hello world */ </span>`

This is how it looks like in HTML:

![unixshell class](/images/unix_shell.png)

![cpp_hello_world](/images/cpp_hello_world.png)

## want to do

* add more colorschemes
* add more classes for highlighting
* add single language classes

... a lot to do 
