# Exercise 6: Testing

Testing a component against acceptance criteria for accessibility.

## Steps (Group 1)
1. Test the disclosure components on the [Agile delivery page](https://www.gov.uk/service-manual/agile-delivery)

## Steps (Group 2)
1. Test the disclosure components on the [Accessibility of PDFs page](https://www.gov.uk/guidance/how-to-publish-on-gov-uk/accessible-pdfs)

## Acceptance criteria

"As an Assistive Technology (AT) user I want to know when additional content is available, how to access that content, and to know whether the content is currently shown or not"

### General criteria

The disclosure component must:
* Hide/collapse content from all users
* Work without JavaScript
* Present content in a logical DOM order
* Use a default text size that is comfortable to read
* Have a colour contrast of at least 4.5:1 between text and the background
* Use valid code

### Focus criteria

The disclosure control must:
* Have a visible text label
* Be focusable with the keyboard
* Be focusable with screen reader shortcuts
* Be large enough to tap with one finger

### Interaction criteria

The disclosure control must:
* Be actionable with a keyboard
* Be actionable with touch
* Be actionable with a mouse
* Be actionable with voice

### Appearance criteria

The disclosure control must:
* Change appearance when focused
* Change in appearance when hovered
* Change in appearance when touched

### State criteria

The disclosure control must:
* Indicate the collapsed/expanded state of of the dislosed content in the code
* Indicate the relationship between the disclosure control and the disclosed content
