# HTML BASICS 
## SHORTCUTS : 
        ! + tab : to fill basic HTML Document 
        lorem + tab : Generate ramdom text content

        > :: child
        + :: sibling
        ^ :: climbup
                div+div>p>span+em^bq :: div+div>(p>span+em)+bq

                div+div>p>span+em^^bq :: div+(div>p>span+em)+bq

        .    classname
        #    id name

        [title="Hello world" width=200px] :: custom attributes


        {} :: Text/Element content
        Counter ::
            h$[title=topic$]{Headline $}*3
                <h1 title="topic1">Headline 1</h1>
                <h2 title="topic2">Headline 2</h2>
                <h3 title="topic3">Headline 3</h3>



## BASIC HTML Document
```
    <!DOCTYPE html>
    <html lang="en">

        <head>
                <link rel="icon" type="image/jpg" href="favicon.jpg"></link>

                <link rel="stylesheet" href="index.css"></link>
                <style> </style>
        </head>

        <body>
                <!-- Place script at last-->
                <script></script>
        </body>
    </html>
```
## Comments
        <!-- write your comments here -->

## Elements
        * Audio
        * Video
        * Button
        * Hyperlinks
        * Lists
                * Ordered List
                * Unordered List
                * Description List
        * Table
        * form
        * SPAN Vs DIV

## Text formatting
        * 

# CSS BASICS
```
# FOR FONT-SIZE only
ABSOLUTE LENGTH UNITS: px
Relative LENGTH UNITS: em | rem | % | vh | vw
        * em | % : relative to parent element font-size
        * rem : relative to root element(html) font-size

        larger | smaller --> relative to parents element fontsize
        xx-small | x-small | small | medium | large | x-large | xx-large : predefined sizes

# width, height
        * vh :: viewport height --> relative to browser height
        * vw :: viewport width  --> relative to browser width
        * vmin,vmax :: min/max of browsers (width,height)
                50vmin 50% relative to browser min dimension

# FOR width
        * width: 2em --> twice the font-size of the same element(not that of parent)
        * width: 2rem --> twice that of html font-size
```
## CSS COLOR TYPES
        * RGB / RGBA :: ()
        * HEXADECIMAL
                * SHORT HAND
                * 8-bit with transperency
        * COLOR NAMES
        * HSL / HSLA
                HUE :: int
                SATURATION :: %
                LIGHTNESS :: %

## FONTS
        font-family: verdana, arial; // fall back font-families if verdana is not available then arial is utilised

        font-size:
                2px // Absolute length units
                2em // Relative lengh units :: Relative to size of parent elements, 1em --> 100%
        font-weight:
                normal
                bold
        font-style:
                normal
                itallic

## Google FONTS
        REMOTE FONTS :: Can use <link> or @import

        LOCAL FONTS :: @font-face
                @font-face{
                        src: url(path to fonts .ttf file)
                        font-family: myCustomFont // rename to our convenience
                }
                Use Multiple font-faces for multiple fonts

## BORDERS
        border-style: solid | dashed | dotted | double | groove | ridge | outset | inset | none
        border-width: 5px;
        border-color: HSL/RGB/colornames/HEX;

        border-radius: px;

        # SHORT HAND
                ##For all sides
                        border: <width> <style> <color>;
                ##For specific sides
                        border-bottom : <width> <style> <color>;
                        border-top:
                        border-left:
                        border-right:
        
        Note : border-radius can not be included  in short hand
## SHADOWS
        * TEXT SHADOWS
        * BOX SHADOWS

## DISPLAY
        * display: block | inline-block | inline | flex
        * 
