# SourceJS Live templates

Live templates for WebStorm / Idea. Accelerate and simplify the development of specs in the IDE.


## Includes

* CG.xml - Code Guide set


### CG.xml
<table>
    <tr>
        <td>//*</td>
        <td>code delimiter with '*'</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>//-</td>
        <td>code delimiter with '-'</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>//=</td>
        <td>code delimiter with '='</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>au</td>
        <td>author comment code</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>ch1</td>
        <td>CSS comment level 1</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>ch2</td>
        <td>CSS comment level 2</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>ch3</td>
        <td>CSS comment level 3</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>ch4</td>
        <td>CSS comment level 4</td>
        <td>CSS</td>
    </tr>
    <tr>
        <td>cl</td>
        <td>console log</td>
        <td>JS</td>
    </tr>
    <tr>
        <td>fu</td>
        <td>function declaration</td>
        <td>JS</td>
    </tr>
    <tr>
        <td>hc1</td>
        <td>HTML comment level 1</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>hc2</td>
        <td>HTML comment level 2</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>hc3</td>
        <td>HTML comment level 3</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>hc4</td>
        <td>HTML comment level 4</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>ph</td>
        <td>img placeholder</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>ph:k</td>
        <td>img placeholder with kittens</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>ph:kk</td>
        <td>another img placeholder with kittens</td>
        <td>HTML</td>
    </tr>
    <tr>
        <td>ref</td>
        <td>refactor comment</td>
        <td>CSS</td>
    </tr>
     <tr>
         <td>todo</td>
         <td>todo comment</td>
         <td>CSS</td>
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
