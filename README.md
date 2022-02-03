# week2-activity26

TASK:
User story:

As a developer, I want to manage CSS values that are used in multiple CSS rules in a more efficient manner.


Acceptance Criteria:

Any repeated color values are defined once as a CSS variable.


Any repeated border radius values are defined once as a CSS variable.

- colour
- border radius 





HOW TO DECLARE CSS VARIABLES

- variables need to be declared within a block
- example of block used here:
: root {

}

- next, name the variable using the following format
 key: value
 key = the name of the variable
 value = the colour


:root {
--white : value???
}

:root {

    --white: #fff;
}

-now you must identify #fff; in the CSS and edit the CSS.
-originally the layout looks like this in the CSS:

header {
  padding: 40px;
  text-align: center;
  background: #13293d;
  color: #fff;
}

- edit the colour in CSS to the following:

header {
  padding: 40px;
  text-align: center;
  background: #13293d;
  color: var ( --white);
}

- what did we add?
 color: var ( --white); -> var was added, brackets and we inserted the name of the variable within the brackets 