# IDE cross-project live templates

> Live templates for
[WebStorm](https://www.jetbrains.com/webstorm/) /
[PhpStorm](https://www.jetbrains.com/phpstorm/) /
[Idea](https://www.jetbrains.com/idea/) /
Jetbrains IDE of choice.
> Boost development and follow common [code-guide](https://github.com/XOP/css-codeguide) in two simple steps!

## What live template is?

Extensive overview available [here](https://www.jetbrains.com/idea/help/live-templates.html) and the brief intro is [here](http://blog.jetbrains.com/webide/2012/10/high-speed-coding-with-custom-live-templates/).


## Includes

* CG-CSS.xml - CSS applicable set
* CG-JS.xml - JS applicable set
* CG-HTML.xml - HTML applicable set


### Common templates

<table>
    <tr>
        <td>//*</td>
        <td>code delimiter with '*'</td>
    </tr>
    <tr>
        <td>//-</td>
        <td>code delimiter with '-'</td>
    </tr>
    <tr>
        <td>//=</td>
        <td>code delimiter with '='</td>
    </tr>
    <tr>
        <td>ch1</td>
        <td>code comment level 1</td>
    </tr>
    <tr>
        <td>ch2</td>
        <td>code comment level 2</td>
    </tr>
    <tr>
        <td>ch3</td>
        <td>code comment level 3</td>
    </tr>
    <tr>
        <td>ch4</td>
        <td>code comment level 4</td>
    </tr>
</table>


### CSS templates

<table>
    <tr>
        <td>au</td>
        <td>author comment code</td>
    </tr>
    <tr>
        <td>ref</td>
        <td>refactor comment</td>
    </tr>
     <tr>
         <td>todo</td>
         <td>todo comment</td>
     </tr>
</table>


### JS templates

<table>
    <tr>
        <td>cl</td>
        <td>console log</td>
    </tr>
    <tr>
        <td>fu</td>
        <td>function declaration</td>
    </tr>
</table>


### HTML templates

<table>
    <tr>
        <td>ph</td>
        <td>img placeholder</td>
    </tr>
    <tr>
        <td>ph:k</td>
        <td>img placeholder with kittens</td>
    </tr>
    <tr>
        <td>ph:kk</td>
        <td>another img placeholder with kittens</td>
    </tr>
</table>


## How to use

1. Just copy files to templates directory and then restart IDE.

    Templates directory on Windows:
    
    	username//.WebIdeXX/config/templates/

    OS X:
    
    	~/Library/Preferences/IntelliJIdeaXX/templates

    
2. Create symlink for each file:

	    ln -s source.xml ~/Library/Preferences/IntelliJIdeaXX/templates
