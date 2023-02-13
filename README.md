# Regex Basics

## Due: Tue 2/21 at 11:59 PM

- Create a program called `RegexBasics.java`
- Prompt the user for a filename containing hexadecimal color codes
- Prompt the user for a filename containing phone numbers
- Prompt the user for a filename containing email addresses
- Read in all the lines from the hex color codes file into an ArrayList
- Read in all the lines from the phone numbers file into another ArrayList
- Read in all the lines from the email addresses file into another ArrayList
- Print whether each hex color code is a valid hex color code or not
  - A hex color code is valid if it contains only 0 through 9 and A through F for each of the six digits
- Print whether each phone number is a valid phone number or not
  - A phone number is valid if it follows any of the following formats where # is a digit
    - (###) ###-####
    - ###-###-####
    - ##########
- Print whether each email address is a valid email address or not
  - An email address is valid if it follows the format username@domain.extension with the following being true
    - username contains only alphanumeric characters, dots, dashes, and underscores
    - domain contains only alphanumeric characters and dashes
    - extension is two to four letters

***Example Input:***\
hex1.txt\
phone1.txt\
email1.txt\
***Example Output:***\
