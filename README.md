## Bugs Identified and Fixed


###1. CSS Errors
  * issue
    - Missing semicolon after `align-items: center` in body section
    - Missing semicolon after `border: 2px solid black` in counter section

  *fix
    -Added the missing semicolons to ensure proper CSS parsing and prevent styling issues.


###2. JavaScript Error

document.getElementById("counter")
   Changed it to:
           document.getElementById("count")
