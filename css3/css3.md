# Selectors

## ul li

- descendant selector matches nested li elements

## ol > li

- Child selector matches li elements in ol element but not nested ul element

## li.myClass ~ li

- adjacent sibling matches later siblings, but not nested.
- All elements after it with the same parent will be effected

## li.myClass + li

- general sibling selector matches later siblings, but not nested
- Only 1 element later siblings

# Attribute selectors

## E[atribute]

- Select elements containing the named attribute
- IE7 and lower doesn't support

## E[attr="val"]

- Element *E* that has the attribute *attr* with the exact, case-sensitive if attribute is case sensitive value *val*

## E[attr|=val]

- Element *E* whose attribute *attr* has a value *val* or begins with *val...*

## E[attr~=val]

- Element *E* whose attribute *attr* has within its value the space sperated full world *val*

## E[attr^=val]

- Element E whose attribute *attr* starts with the value *val*

## E[attr$=val]

- Elements whose attribute *attr* ends in *val*

## E[attr*=val]

- Element E whose attrbute *attr* matches *val* enywhere within the attribute. Similar to E[attr~=val] above. except the *val* can be part of a word.

## E[attr][attr]

- We can do multiple attributes.

# UI pseudo classes

- Based on the current state of UI
- :checked
- :valid
- :invalid
- :inrange
- :out-of-range
- :optional
- :required

# Structural UI pseudo selectors

- Target elements on the page based on their relationships to other elements in the DOM
- Updates dynamically if page updates
- Reduced need for extra markup, clases and IDs
- 
- :first-child
- :last-child
- :first-of-type
- :last-of-type
- :only-child
- :only-of-type
- 
- :root: Selects the document root which is html element
- :empty
- 
- Target element or elements based on argument passed to the selector
- :nth-child()
- :nth-child(2n)
- :nth-of-type(5)
- nth-child(even)
- nth-child(odd)
- :nth-last-child()
- :nth-of-type()
- :nth-last-of-type()
- 
- Negative pseudo-class
- :not(:empty)
- :not(.class_name)
- :not([attr])
- :not(#id)

## Pseudo elements

### ::first-line

### ::first-letter

### ::section (not in specification)

### ::before

### ::after

- *Pseudo classes* select elements that already exist.
- *Pseudo elements* create "faux" elements you can style.

