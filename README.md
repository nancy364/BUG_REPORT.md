# BUG_REPORT.md
## Bug 1: JavaScript Null Error
Why it happened:
The script was loaded before the HTML elements were available.
How I fixed it:
I added the defer attribute so JavaScript runs after page load.We can also load a page by writting the script tag after the closing body tag.
---
## Bug 2: Register Button Not Clickable
Why it happened:
The button had incorrect CSS z-index settings.
How I fixed it:
I fixed the z-index value so the button stays above other elements.
---
## Bug 3: Spots Counter Increasing
Why it happened:
The counter value was treated as a string and added instead of subtracted.
How I fixed it:--
JavaScript me string + number karne par concatenation hota hai, isliye counter galat increase ho raha tha. So I converted the value to a number and used decrement logic because condition is that when user register, number should go down .
---
## Bug 4: Form Submit Not Working
Why it happened:
The submit button was set to type="button".
How I fixed it:
I changed it to type="submit" and handled the submit event properly.
