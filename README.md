# Atuomation-Testing-for-PHPTRAVELS
Atuomation Testing for PHPTRAVELS for Register form 
using Selenium and JAVA to test the following:
1. Enter First Name which must start with capital letter.
2. Enter Last Name which must start with capital letter and can’t be equal First Name.
3. Enter a valid Mobile Number.
4. Enter a valid E-mail that should be unique for every user.
5. Enter a Password and check that it must have capital letter, small letter, with a limit of 8
characters.
6. After successful registration, verify that the user can login.

*****Note: Can't find some Xpath for some element and some parameters need to redefine*****
-------------------------------------------------------------------------------------------------------------
Possible Test Scenarios of the Sign Up Page
---------------------------------------------

Required Fields:

1- First Name
----------
→ Verify without providing First Name, it should give the respective error and it should not be possible to proceed further the registration page.

→ verify with providing First Name starting with capital letter, it should be possible to complete the registration (considering user has provided all other information correctly).

→ Verify verify with providing First Name start without capital letter, t should give the respective error and it should not be possible to proceed further the registration page.


2- Last Name
----------
→ Verify without providing Last Name, it should give the respective error and it should not be possible to proceed further the registration page.

→ verify with providing Last Name starting with capital letter, it should be possible to complete the registration (considering user has provided all other information correctly).

→ Verify verify with providing Last Name start without capital letter, t should give the respective error and it should not be possible to proceed further the registration page.


3- Mobile Number
---------------
→ Verify without providing any phone number in the field, as it is also mandatory field so user should not be able to proceed and complete the registration without providing phone number.

→ Verify with providing invalid phone number ( phone number with 2-3 digit), in this case also user should not be able to proceed and complete the registration with invalid providing phone number.

→ Verify with providing valid phone number in the field, in this case the user should be able to register successfully with valid phone number (considering user has provided all other information correctly).


4- E-mail
-----------
→ Verify with valid email ID, but have an existing account on PHPTRAVELS with that email ID, then in that case, it should not be allowed to register with that email ID and should give a respective error message (considering user has provided all other information correctly).

→ Verify without providing any details in the Email field, it should not be allowed to register without any email ID and should give a respective error message.

→ Verify with valid email ID, which does not have any account on PHPTRAVELS with that email ID, so the user should be able to proceed and register successfully (considering user has provided all other information correctly).

5- Password
----------------
→ Verify without providing any password in the Password field, it should give the respected error message to provide the password.

→ Verify with providing password in the Password field less than 8 characters, it should give the respected error message to provide the password,we can make use of test design technique Boundary Value Analysis (BVA), with lengths 7, 8 and 9 characters.

→ Verify with providing password in the Password field not contain capital characters, it should give the respected error message to provide the password.

→ Verify with providing password in the Password field not contain small characters, it should give the respected error message to provide the password.



