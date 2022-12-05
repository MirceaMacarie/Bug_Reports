# Bug Reports
This repository contains reports about bugs found by myself on different websites. There are various types of bugs reported, like functional, UI / UX design or usability bugs. Initially, these bug reports were written in JIRA, and afterwards they were uploaded on this repository.

------

### :one: Bug Reports for the online shop https://www.demoblaze.com/ :arrow_down:
![demoblaze](https://user-images.githubusercontent.com/115346533/205309277-e4a57786-92f6-4ea2-a86f-328b783bb973.jpg)



**Bug ID:** BR-1

**Bug title:** The "Welcome User" button has no special functionality for users

**Priority and severity:** P5 - Low

**Description:** When user logs in on the site with username and password, the "Welcome User" button/ link from the upper-right corner makes nothing.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on "Welcome User", on the right corner.

**Expected result:** User should be redirected to the settings of the account.

**Actual result:** Nothing special happens on the website.

**Test data:** Username: Ceao & Password: 1234

#


**Bug ID:** BR-2

**Bug title:** The empty contact form is considered "sent"

**Priority and severity:** P3 - Normal

**Description:** If user clicks on "Contact" and then press "Sent message" button, it is shown the notification  "Thanks for the message!!" (like in the attached image), and not a warning that the form is empty.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on Contact without complete the form
4. Click on "Sent message"

**Expected result:** Show a notification for user that the form is empty.

**Actual result:** It is shown a pop-up with "Thanks for the message!!".

**Test data:** Username: Ceao & Password: 1234

**Attachments:**
![bug](https://user-images.githubusercontent.com/115346533/205721092-d5a565e8-89e1-4fb5-adff-54284b02a597.jpg)

#


**Bug ID:** BR-3

**Bug title:** The email adress is unnecessary to sign up / log in

**Priority and severity:** P3 - Normal

**Description:** The website does not ask user for an email adress, in order to create an account or to log in. It asks only the username, which is a security issue.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Click on the sign up button
3. Enter your username and password, without any email adress

**Expected result:** It is expected to exist an input in the sign up/ log in form for the email adress.

**Actual result:** The website asks user just the username and the password.

**Test data:** Username: Ceao & Password: 1234

#


**Bug ID:** BR-4

**Bug title:** The description size font of the products is too small

**Priority and severity:** P5 - Low

**Description:** The description size font of the products is too small for a normal user.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Select one product from the main list

**Expected result:** Show the description of the selected product with a normal size font, which can be read easily by a normal user.

**Actual result:** The description size font of the product is too small, with 15% smaller than a normal font.

**Test data:** Item: Samsung galaxy s6.

#


**Bug ID:** BR-5

**Bug title:** The inexistent symbol of the currency in Cart section

**Priority and severity:** P3 - Normal

**Description:** In the Cart section does not appear the symbol of the currency after you place a product in Cart to buy.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Log in with the correct credentials
3. Select one product from the main list
4. Click on the Cart section to see the product and its price

**Expected result:** To see the product, its price and the symbol of the currency.

**Actual result:** The symbol of the currency does not appear near the price.

**Test data:** Username: Ceao & Password: 1234 & Item: Samsung galaxy s6.

#


**Bug ID:** BR-6

**Bug title:** The creditcard number of the purchase form works without any requirements

**Priority and severity:** P1 - Critical

**Description:** When user wants to buy a product, he can fill any type of number in the creditcard section in the purchase form, without any conditions like minimum number of digits.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Log in with the correct credentials
3. Select one product from the main list and click "Add to cart"
4. Click on the Cart section to see the product
5. Click on the ”Place order” button
6. Complete the name section and one digit in the creditcard section
7. Click on "Purchase" button

**Expected result:** Show a window alert to complete the correct creditcard number, with its specific structure (XXXX-XXXX-XXXX-XXXX).

**Actual result:** The website validates the purchasing of the product, without any problem.

**Test data:** Username: Ceao & Password: 1234 & Item: Samsung galaxy s6 & Creditcard number: 0.

#


**Bug ID:** BR-7

**Bug title:** The section with products in delivery does not exist

**Priority and severity:** P1 - Critical

**Description:** There is no section where clients can verify the products they purchase them, or what is the status of the delivering (for exemple when they will receive the products).

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Log in with the correct credentials
3. Select one product from the main list
4. Click on the Cart section to see the product and its price
5. Click on the "Buy now" button
6. Complete the purchasing form
7. Click on "Purchase" button

**Expected result:** It is expected to see a special button/ section with detalis about user purchasing, or to see details in Cart section.

**Actual result:** There is no section with information on purchased items.

**Test data:** Username: Ceao & Password: 1234 & Item: Samsung galaxy s6 & Creditcard number: 0.

#


**Bug ID:** BR-9

**Bug title:** "404" Error page is not custom for users

**Priority and severity:** P3 - Normal

**Description:** There is no "404" custom page for this website, which can help the user to find what he is looking for on the website.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Write in the URL adress something random, without any meaning / which does not exist on this website.

**Expected result:** A "404" custom page is expected to be seen with the logo/ home button to return to the main page and eventually a search bar, if user is searching something that does not exist on the website.

**Actual result:** It is shown a simple page with the "Error" text, without any link to the main page or additional advice to search correctly on the website.

**Test data:** "https://www.demoblaze.com/pisici-gratuite"

#


**Bug ID:** BR-10

**Bug title:** The Copyright of the website for current year

**Priority and severity:** P5 - Low

**Description:** The Copyright of this website is not updated to current year.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Scroll down to the footer of the website.

**Expected result:** The Copyright have to be updated to the current year (2022).

**Actual result:** The Copyright is not updated to the current year, in this case 2022, but for 2017.

**Test data:** /

#


**Bug ID:** BR-11

**Bug title:** The website is not full responsive

**Priority and severity:** P4 - Low

**Description:** The website is not full responsive, because the writing is no longer readable at low resolutions, and the menu buttons do not fit on the small screen, but exit the frame.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Press F12 keyboard to open the Console and choose a smaller resolution (under 750 px)

**Expected result:** The webpage have to fit properly to the selected resolution, the writing must be readable, the size of the image must fit to the screen, and the menu buttons appear in the header.

**Actual result:** The writing is not readable, the image are not correctly sized, and the menu buttons exit from the website frame.

**Test data:** /

#


**Bug ID:** BR-12

**Bug title:** Deprecated file in the console

**Priority and severity:** P3 - Low

**Description:** There is a deprecated file which is shown in the console, and it has to be fixed.

**Steps to reproduce:**
1. Go to the site https://www.demoblaze.com/
2. Open the Console by pressing F12 keyboard and select section "Problems"

**Expected result:** There should be no errors or problems in the console.

**Actual result:** When the console is opened, the message "Event.path is deprecated and will be removed. Please use Event.composedPath() instead." appears in that section.

**Test data:** /

#

### :two: Bug Reports for the online consumption calculator https://www.demoblaze.com/ :arrow_down:
![Calculator](https://user-images.githubusercontent.com/115346533/205721765-fd690630-504e-4c8f-bded-4ddd234f7c68.jpg)



**Bug ID:** BR-13

**Bug title:** The appearance of an unloaded image symbol

**Priority and severity:** P3 - Low

**Description:** The symbol for an image that does not load appears on the main page of the application on the right part of the screen.

**Steps to reproduce:**
1. Go on the https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Increase to 1 the number from the input "I had ... cups of coffee"
3. Look on the right side of the screen.

**Expected result:** To see a normally loaded image on the main page under certain conditions, or to see nothing, not even the unloaded image symbol.

**Actual result:** The unloaded image symbol can be seen on the main page of the application, on the right side of the page.

**Test data:** /

**Attachments:**
![bug_image](https://user-images.githubusercontent.com/115346533/205722414-6bd31243-648d-436d-b2b7-8fbc0582f5f7.jpg)

#


**Bug ID:** BR-14

**Bug title:**

**Priority and severity:**

**Description:** 

**Steps to reproduce:**
1. 
2. 
3.

**Expected result:** 

**Actual result:** 

**Test data:** 

#


**Bug ID:** BR-15

**Bug title:**

**Priority and severity:**

**Description:** 

**Steps to reproduce:**
1. 
2. 
3.

**Expected result:** 

**Actual result:** 

**Test data:** 

#


**Bug ID:** BR-16

**Bug title:**

**Priority and severity:**

**Description:** 

**Steps to reproduce:**
1. 
2. 
3.

**Expected result:** 

**Actual result:** 

**Test data:** 

#
