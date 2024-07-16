# Form-Submission
HTML Document: The structure starts with <html>, followed by <head> and <body> tags.
Form: Inside the body, there is a <form> element which contains a table with multiple rows (<tr>) and columns (<td>). Each row represents a different form field.
#Form Fields:
#Firstname:
<td>Firstname</td>: Label for the first name.
<td><input type="text"></td>: Input field for entering the first name.
#Surname:
<td>Surname</td>: Label for the surname.
<td><input tytpe="text"></td>: Input field for entering the surname (with a typo in the type attribute, should be corrected to type="text").
#Password:
<td>Password</td>: Label for the password.
<td><input type="password"></td>: Input field for entering the password.
#Telephone Number:
<td>Telephone Number</td>: Label for the telephone number.
<td><input type="tel"></td>: Input field for entering the telephone number.
#Gender:
<td>Gender</td>: Label for the gender.
<td>Male<input type="radio" name="gender" checked> Female<input type="radio" name="gender" checked></td>: Radio buttons for selecting gender (both have the checked attribute, which should be corrected to allow only one default selection).
#Email:
<td>Email</td>: Label for the email.
<td><input type="email"></td>: Input field for entering the email.
#Date of Birth:
<td>Date of birth</td>: Label for the date of birth.
<td><input type="date"></td>: Input field for entering the date of birth.
#I Agree:
<td>I Agree</td>: Label for agreement.
<td><input type="checkbox"></td>: Checkbox for agreement.
#Buttons:
<td><input type="button" value="Click me"></td>: Button labeled "Click me" (does not submit the form).
<td><input type="reset"></td>: Button to reset the form fields.
#Address:
<td>Address</td>: Label for the address.
<td><textarea rows="5" cols="23"></textarea></td>: Text area for entering the address.
#Country:
<td>Country</td>: Label for the country.
<td><select><option>INDIA</option><option>LONDON</option><option>FRANIS</option></select></td>: Dropdown menu for selecting the country (should be corrected to FRANCE instead of FRANIS).
#Corrections Needed:
Fix the typo in tytpe="text" to type="text".
Remove the checked attribute from one of the gender radio buttons to allow only one default selection.
Correct the option value FRANIS to FRANCE.
