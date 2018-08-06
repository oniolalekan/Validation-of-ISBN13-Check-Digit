# Validation-of-ISBN13-Check-Digit
The concept of check digit is widely used in identification codes including bank account numbers, International Standard Book Numbers (ISBNs) and Universal Product Codes (UPCs). Check digits are useful in reducing manual input errors in digital applications, as they the codes or numbers with check digits can be validated without any other extra information. 

This python function validates ISBN13 codes and return either 'Valid' for correct ISBN13 code and 'Invalid' for incorrect ISBN13 code. 

The function was tested on the following test cases:

assert_equal(verify_ISBN13(4006381333931), 'Valid')

assert_equal(verify_ISBN13(9788175257665), 'Valid')

assert_equal(verify_ISBN13(9788175257645), 'Invalid')
