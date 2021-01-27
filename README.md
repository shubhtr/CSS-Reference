# CSS Reference

## Background

Term                            |   Term 1
---                             |   ---
background                      |   <em>background-image</em>
&nbsp;                          |   <em>background-position</em>
&nbsp;                          |   <em>background-size</em>
&nbsp;                          |   <em>background-repeat</em>
&nbsp;                          |   <em>background-attachment</em>
&nbsp;                          |   <em>background-origin</em>
&nbsp;                          |   <em>background-clip</em>
&nbsp;                          |   <em>background-color</em>
&nbsp;                          |   &nbsp;
background-attachment           |   scroll \|\| fixed
&nbsp;                          |   &nbsp;
background-break                |   bounding-box \| each-box \| continuous
background-clip                 |   length
&nbsp;                          |   %
&nbsp;                          |   border-box \| padding-box \| content-box \| no-clip
&nbsp;                          |   &nbsp;
background-color                |   <em>color</em>
&nbsp;                          |   transparent
background-image                |   <em>url</em>
&nbsp;                          |   none
background-origin               |   border-box \| padding-box \| content-box
&nbsp;                          |   &nbsp;
background-position             |   top left \| top center \| top right \| center left \| center center \| center right \| bottom left \| bottom center \| bottom right
&nbsp;                          |   <em>x-% y-%</em>
&nbsp;                          |   <em>x-pos y-pos</em>
&nbsp;                          |   &nbsp;
background-repeat               |   repeat \| repeat-x \| repeat-y \| no-repeat
&nbsp;                          |   &nbsp;
background-size                 |   <em>length</em>
&nbsp;                          |   <em>%</em>
&nbsp;                          |   auto \| cover \| contain

## Table

Term                            |   Term 1
---                             |   ---
border-collapse                 |   collapse \| separate
border-spacing                  |   <em>length length</em>
caption-side                    |   top \| bottom \| left \| right
empty-cells                     |   show \| hide
table-layout                    |   table-layout-auto \| fixed

## Border

Term                            |   Term 1
---                             |   ---
border                          |   <em>border-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-break                    |   <em>border-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>color</em>
&nbsp;                          |   close
border-bottom                   |   <em>border-bottom-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-bottom-color             |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-bottom-style             |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-bottom-width             |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-collapse                 |   collapse \| separate
&nbsp;                          |   &nbsp;
border-image                    |   <em>image</em>
&nbsp;                          |   [ <em>number / % border-width </em> stretch \| repeat \| round ]
&nbsp;                          |   none
border-left                     |   <em>border-left-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-left-color               |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-left-style               |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-left-width               |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-right                    |   <em>border-right-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-right-color              |   <em>border-right-color</em>
&nbsp;                          |   &nbsp;
border-right-style              |   border-style
&nbsp;                          |   &nbsp;
border-right-width              |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
&nbsp;                          |   &nbsp;
border-top                      |   <em>border-top-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-top-color                |   <em>border-color<em>
&nbsp;                          |   &nbsp;
border-top-style                |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-top-width                |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-width                    |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-radius                   |   <em>border-top-right-radius</em>
&nbsp;                          |   <em>border-bottom-right-radius</em>
&nbsp;                          |   <em>border-bottom-left-radius</em>
&nbsp;                          |   <em>border-top-left-radius</em>
border-top-right-radius         |   <em>length</em>
&nbsp;                          |   &nbsp;
border-bottom-right-radius      |   <em>length</em>
&nbsp;                          |   &nbsp;
border-bottom-left-radius       |   <em>length</em>
&nbsp;                          |   &nbsp;
border-top-left-radius          |   <em>length</em>
&nbsp;                          |   &nbsp;
box-shadow                      |   inset \|\| [ <em>length</em>, <em>length</em>, <em>length</em>, <em>length</em> || `<color>` ]
&nbsp;                          |   none
border-style                    |   none \| hidden \| dotted \| dashed \| solid \| double \| groove \| ridge \| inset \| outset

## Transitions

Term                            |   Term 1
---                             |   ---
transition                      |   transition-property
&nbsp;                          |   transition-duration
&nbsp;                          |   transition-timing-function
&nbsp;                          |   transition-delay
&nbsp;                          |   &nbsp;
transition-delay                |   time
&nbsp;                          |   &nbsp;
transition-duration             |   time
&nbsp;                          |   &nbsp;
transition-property             |   none | all
&nbsp;                          |   &nbsp;
transition-timing-function      |   ease \| linear \| ease-in \| ease-out \| ease-in-out \| cubic-Bezier (number, number, number, number)
&nbsp;                          |   &nbsp;

## Box Model

|Term                               |   Term 1 |
|---                                |   ---    |
clear                               |   left \| right \| both \| none
display                             |   none \| inline \| block \| inlineblock \| list-item \| run-in \| compact \| table \| inlinetable \| \|table-row-group \| table-header-group \| tablefooter-group \| table-row \| table-column-group \| tablefooter-group \| table-row \| table-column-group \| tablecolumn \| table-cell \| tablecaption \| ruby \| ruby-base \| ruby-text \| ruby-base-group \| ruby-text-group
float                               |   left \| right \| none
height                              |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
max-height                          |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
max-width                           |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
min-height                          |   none \| inherit
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
min-width                           |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
width                               |   auto
&nbsp;                              |   <em>%</em>
&nbsp;                              |   <em>length</em>
margin                              |   <em>margin margin-top</em>
&nbsp;                              |   <em>margin-right</em>
&nbsp;                              |   <em>margin-bottom</em>
&nbsp;                              |   <em>margin-left</em>
margin-bottom                       |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-left                         |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-right                        |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-top                          |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding                             |   <em>padding padding-top</em>
&nbsp;                              |   <em>padding-right</em>
&nbsp;                              |   <em>padding-bottom</em>
&nbsp;                              |   <em>padding-left</em>
padding-bottom                      |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-left                        |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-right                       |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-top                         |   <em>length</em>
&nbsp;                              |   <em>%</em>
marquee-direction                   |   forward \| reverse
marquee-loop                        |   infinite
&nbsp;                              |   <em>number</em>
marquee-play-count                  |   infinite
&nbsp;                              |   <em>integer</em>
marquee-speed                       |   slow \| normal \| fast
marquee-style                       |   scroll \| slide \| alternate
overflow                            |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
&nbsp;                              |   <em>overflow-x</em>
&nbsp;                              |   <em>overflow-y</em>
overflow-style                      |   auto \| marquee-line \| marqueeblock
overflow-x                          |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
overflow-y                          |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
rotation                            |   <em>angle</em>
rotation-point                      |   <em>position (paired value offset)</em>
visibility                          |   visibility visible \| hidden \| collapse

## Font

|Term                               |   Term 1 |
|---                                |   ---    |
font                                |   font-style
&nbsp;                              |   font-variant
&nbsp;                              |   font-weight
&nbsp;                              |   font-size/line-height
&nbsp;                              |   font-family
&nbsp;                              |   caption \| icon \| menu \| message-box \| smallcaption \| status-bar
font-family                         |   <em>family-name</em>
&nbsp;                              |   <em>generic-family</em>
&nbsp;                              |   inherit
font-size                           |   xx-small \| x-small \| small \| medium \| large \| x-large \| xx-large \| smaller \| larger \| inherit
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
font-size-adjust                    |   none \| inherit
&nbsp;                              |   <em>number</em>
font-stretch                        |   normal \| wider \| narrower \| ultra-condensed \| extracondensed \| condensed \| semi-condensed \| semiexpanded \| expanded \| extra-expanded \| ultraexpanded \| inherit
font-style                          |   normal \| italic \| oblique \| inherit
font-variant                        |   normal \| small-caps \| inherit
font-weight                         |   normal \| bold \| bolder \| lighter \| 100 \| 200 \| 300 \| 400 \| 500 \| 600 \| 700 \| 800 \| 900 \| inherit

## Color
|Term                               |   Term 1 |
|---                                |   ---    |
color                               |   inherit
&nbsp;                              |   <em>color</em>
opacity                             |   inherit
&nbsp;                              |   <em>number</em>

## Text
|Term                               |   Term 1 |
|---                                |   ---    |
direction                           |   ltr \| rtl \| inherit
hanging-punctuation                 |   none \| [ start \| end \| endedge ]
letter-spacing                      |   normal
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
punctuation-trim                    |   none \| [start \| end \| adjacent]
text-align                          |   start \| end \| left \| right \| center \| justify
text-align-last                     |   start \| end \| left \| right \| center \| justify
text-decoration                     |   none \| underline \| overline \| line-through \| blink
text-emphasis                       |   none \| [ [ accent \| dot \| circle \| disc] [ before \| after ]? ]
text-indent                         |   <em>length</em>
&nbsp;                              |   <em>%</em>
text-justify                        |   auto | inter-word | interideograph | inter-cluster | distribute | kashida | tibetan
text-outline
text-shadow
text-transform
text-wrap
unicode-bidi
white-space
white-space-collapse
word-break
word-spacing
word-wrap










none
color
length
none
color
length
none | capitalize | uppercase
| lowercase
normal | unrestricted | none
| suppress
normal | embed | bidioverride
normal | pre | nowrap | prewrap
| pre-line
preserve | collapse | preservebreaks
| discard
normal | keep-all | loose |
break-strict | break-all
normal
length
%

## Column
|Term                               |   Term 1 |
|---                                |   ---    |
normal | break-word
column-count
column-fill
column-gap
column-rule
column-rule-color
column-rule-style
column-rule-width
columns
column-span
column-width
auto
number
auto | balance
normal
length
column-rule-width
column-rule-style
column-rule-color
color
border-style
thin | medium | thick
length
column-width
column-count
1 | all
auto
length