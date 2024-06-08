---
layout: layouts/base.njk
eleventyNavigation:
  key: About Blog10
  order: 3
---
{% image "./headerPic2.png", "A Blog-One Logo" < 20 %}
I am a person that writes stuff and keeps a note of what I currently do or have done on the Web Design Course.


1. I shall add a logo to Blog10 page <br>
2. I shall add a table screenshot to Blog10 page <br>
3. I shall add a form screenshot to Blog10 page<br> 
4. I shall add a coffee page which has Bootstrap script and URL being used. (Under Construction).
5. I shall add a form into form page. (Under Construction)
6. My attempt of placing a form on a Bootstrap Card component for Task 4 (Page Bootrap Form).
7. Javascript and logo added onto Home Page. 
8. Codepen links added below. 

<div class="container" >
    <div class="item item-1" style="background-color: #fb7185;"> 

        <SELECT WIDTH=20 onChange="JumpToIt(this)">
        <OPTION VALUE="None"> Select a JavaScript resource from this list --->
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/mdYmaqO/">JavaScript Addition
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/GRammJQ/">JavaScript OnClick Test
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/ExzWRBo/">JavaScript Template Literals
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/dyEveLW/">JavaScript String Concatenation
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/gOJmzjo/">JavaScript Basic Arithmetic
        <OPTION VALUE="https://codepen.io/Mehzabeen/pen/OJYpZMg/">JavaScript More Scripts</OPTION>
        </SELECT>
        
    Select Codepen Link
    </div> 
    

<SCRIPT LANGUAGE ="JavaScript">

    function JumpToIt(list)
    {
    var selection = list.options[list.selectedIndex].value
    if (selection !="None")
    location.href = selection
    }
    
    </SCRIPT>


