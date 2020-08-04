# my-first-repo

!!! If you want to see your page in a browser
    1. open a new terminal
    2. type python3 -m http.server
    3. click on View in browser
    4. if an error appears use Try again 

1. .html:Create the a template
    Give it a h1
    If you have more then one page add the pages right now - lists
        a. nav, ul, li, a href a li ul nav
    Give it some text p - Whats the page about/ what do you want to achieve
        Give it some lists, you need always some listing

!!! If you want to see the changes on the road then add the following to your html file
    <link href="css/style.css" rel="stylesheet" type="text/css">

!!!DO NOT FORGET TO SAVE YOUR WORK IN BETWEEN OTHERWISE YOU WILL NOT SEE THE RESULT IN YOUR PREVIEW OR BROWSER

2. .css: Give the nav some style
    a. first the parent ul
        1. background color
        2. list style: none if you do not want to have dots
        3. text align: left right center?
        4. margine and padding
    b. second something for the li
        1. font size
        2. line height
        3. height
        4. display: how shall there appear 
            - beside: inline-block
            - or as is
        5. margin
    c. give the anchors some style
        1. if you want to get rid of the underline 
            text-decoration: none
        2. color
        3. display: block (nothing else is allowed on this line)
    d. give the links some action
        1. add nav a:hover
        2. change the background color
        3. change the font color = color

3. .html: At this moment change the p to a div as we want to have several images beside each other
    a. replace p with div and add a class so we can style it in the style.css
    b. add an anchor a and href for a link to a page
        !!! add the following to the href: "target: _blank" this will open the page in a new page
    c. add the img scr and alt

4. Give it some style to the div
    a. .card
        1. float: where do you want it left, right, center
        2. give it a width and a margin (right or left so it does not sit on the edge)
    b. .card a
        1. text-align: center (most time its will be in the center of the box .card)
    c. img 
        1. width: 100% (thats 100% of the box size .card)
        2. height
    d. h2
        1. text-align: center (should be the same as the .card a)

5. Do the same for the other pages

6. git add - this will SAVE all your files (the one you chose)
    a. git add . (all files from your current position)
    b. git add css/ stream-*.html (css directory and all files which start with "stream-" the asterisk is a wildcard or a placeholder for more then one character)

7. git commit -m "Here you write what you've done eg. Initial commit, Updated image javascrpt, Changed style of immage and so on..."

8. git push (all your files that have been added and commited witll be pushed to github)

