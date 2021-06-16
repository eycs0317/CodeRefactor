# codeRefactor

## Description

Refactor code to meets accessibility standards and clean code.

## Acceptance Criteria

GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title


change the title to "Horiseon Social Solution Services"

using header , nav, footer, section, article, aside instead of div
also refactor the css with it.

using section to wrap the img tag instead of just using div for the image - line 28-29

adding id to the section on line 30.

adding alt to all image tag

found alot of repeat css class. refactor to maximize reusability

h2 tag inside the footer change it to h4 a well as the css

