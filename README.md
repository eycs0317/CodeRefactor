# codeRefactor

## Description

Refactor code to meets accessibility standards and clean code.

## Getting Started

git clone https://github.com/eycs0317/codeRefactor.git

## Build With
  HTML
  CSS

## Deployed Link

## Authors
Eddie Yeung

## Acceptance Criteria

GIVEN a webpage meets accessibility standards

1. WHEN I view the source code
   THEN I find semantic HTML elements

   * Using header , nav, footer, section, article, aside instead of div
   also refactor the css with it.

2. WHEN I view the structure of the HTML elements
   THEN I find that the elements follow a logical structure independent of styling and positioning

    * Using section tag to wrap the img tag instead of just using div for the image - line 28-29

3. WHEN I view the image elements
   THEN I find accessible alt attributes

    * Adding alt to all image tag

4. WHEN I view the heading attributes
   THEN they fall in sequential order

    * h2 tag inside the footer change it to h4 a well as the css

5. WHEN I view the title element
   THEN I find a concise, descriptive title

   * Change the title to "Horiseon Social Solution Services"

6. WHEN i click on the first link
   THEN i find the link is broken

   * Adding id to the section on line 30

7. FOUND a lot of duplicate CSS

   * Refactor style.css to maximize reusability




