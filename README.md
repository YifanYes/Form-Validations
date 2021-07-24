# Form Validation

After building the HTML and CSS for this form, we need to make sure it prevents the user from submitting a form with the wrong information or format.
To prevent a form submission we have to listen to the "submit" event that is triggered by the form itself when the user presses either: the enter/return key or the submit button.

**Instructions**
- Make sure to stop the flow of the submission using preventDefault(), here is a little bit more about preventDefault().
- After preventing the submission make sure all the input values are correct and properly formatted.
- If there are one or more inputs with an invalid value, show a clear error on the top of the form with a very explicit message about what happened.
- Change the background color of the relevant inputs (the ones with incorrect data).
