# Bug Reports
This repository contains reports about bugs found by myself on different websites. There are various types of bugs reported, like functional, UI / UX design or usability bugs. Initially, these bug reports were written in JIRA, and afterwards they were uploaded on this repository.

------


### :one: Bug Reports for the online shop https://www.demoblaze.com/ :arrow_down:
![demoblaze](https://user-images.githubusercontent.com/115346533/205309277-e4a57786-92f6-4ea2-a86f-328b783bb973.jpg)



**Bug ID:** BR-1

**Bug title:** The "Welcome User" button has no special functionality for users

**Priority and severity:** P5 - Low

**Description:** When user logs in on the site with username and password, the "Welcome User" button / link from the upper-right corner makes nothing.

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

**Description:** If user clicks on "Contact" and then press "Sent message" button, it is shown the notification "Thanks for the message!!" (like in the attached image), and not a warning that the form is empty.

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
4. Click on the "Cart section" to see the product
5. Click on the "Place order" button
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

**Expected result:** It is expected to see a special button / section with detalis about user purchasing, or to see details in "Cart" section.

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

**Expected result:** A "404" custom page is expected to be seen with the logo / home button to return to the main page and eventually a search bar, if user is searching something that does not exist on the website.

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

------


### :two: Bug Reports for the online consumption calculator https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ :arrow_down:
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

**Bug title:** "404" Error page is not custom for users

**Priority and severity:** P4 - Low

**Description:** There is no "404" custom page for this webapp, which can help the user to find what he is looking for.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Write in the URL adress something random, without any meaning / which does not exist on this website.

**Expected result:** It is expected to see a "404" custom page, with the logo / home button to return to the main page and eventually a search bar for helping the user to find what he is looking for.

**Actual result:** The user is redirected to the https://www.globalsqa.com/.

**Test data:** "https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/pisici-gratuite"

#


**Bug ID:** BR-15

**Bug title:** There is no Copyright or details about author

**Priority and severity:** P5 - Low

**Description:** There is no updated Copyright in the website footer, or a special section with information about author / content creator ("About us"). 

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Scroll down to the footer of the website.

**Expected result:** It is expected to see the Copyright updated to current year (2022 in that case) and a "About Us" button containing a link to information about the site author.

**Actual result:** There is no updated Copyright or "About us" section in the footer of the website, or in other place.

**Test data:** "https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/"

#


**Bug ID:** BR-16

**Bug title:** The problem of displaying the final value with too many digits

**Priority and severity:** P1 - High

**Description:** The application does not display the final result correctly if it is a number that has more than 70 digits.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. In the first input of the calculator (Cups of coffee) introduce a number that has more than 70 digits.

**Expected result:** To see the final and the correct result of the product of multiplication in the third input.

**Actual result:** There is no number shown in the final input.

**Test data:** Cups of coffee: 100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000

#


**Bug ID:** BR-17

**Bug title:** The warning and image are not displayed correctly on the tar calculator

**Priority and severity:** P2 - High

**Description:** On the tar calculator if we have 2.99 x 10, the result is 30, but the image and the warning message are not displayed as at 3 x 10 = 30.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Write a value greater than 2.95 in the "I had … cigarettes" input
3. Check for the value 10 in the "mg for tar per cigarette" input

**Expected result:** To display the message that users have exceeded the tar limit and the image with the anti-smoking sign, because the computer rounds off the results.

**Actual result:** The warning message and the anti-smoking image are not diplayed on the main page.

**Test data:** "I had … cigarettes": 2.99 & "mg for tar per cigarette": 10

#


**Bug ID:** BR-18

**Bug title:** The anti-smoking sign image does not fit in the website design

**Priority and severity:** P5 - Low

**Description:** When the image with the anti-smoking symbol is displayed, it does not fit correctly in the page layout, and the unloaded image symbol still appears next to the image.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Write a value greater than 2 in the "I had … cigarettes" input

**Expected result:** The image with anti-smoking sign have to fit properly in the calculator design.

**Actual result:** The image has a too large resolution for the website design, and the unloaded image symbol still appears. (see the attached photo)

**Test data:** "I had … cigarettes": 3

**Attachments:** 

![Bug_img](https://user-images.githubusercontent.com/115346533/205987505-0fb5caf6-c7d0-41d7-b358-005bec8f3089.jpg)

#


**Bug ID:** BR-19

**Bug title:** The coffee image that does not load from the console

**Priority and severity:** P3 - Normal

**Description:** In the Console, in the "Images" section, there is a source with an image with a coffee (Coffeescript.sh-600x600.png), but it is not loaded at all, the format is not appropriate and sent back to another page.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Press F12 key and select Sources, then Images
3. Select the file "Coffeescript.sh-600x600.png"

**Expected result:** The image file should be displayed to see properly into the console.

**Actual result:** The image file does not have the appropriate format and forward to another page.

**Test data:** /

#


**Bug ID:** BR-20

**Bug title:** The result is wrong if the second decimal is less than 5

**Priority and severity:** P4 - Normal

**Description:** The result is not displayed correctly, if the first decimal is 0 and is followed by a decimal less than 5. Only if it is 1.04 followed by 15 digits of "9" then it is rounded to 1.05 .

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Write in the "I had … cups of coffee" / "I had … cigarettes" the value 1.049
3. Then replace 1.049 with 1.04999999999999999

**Expected result:** The result of the first calculation should be 10.5 or 11 (rounded), and the result of the second calclulation should be shown rounded after first digit of  "9".

**Actual result:** The result of the first calculation is 10, and the result of second calculation is 11 only after the value of 1.04999999999999999 (14 digits of "9").

**Test data:** "I had … cups of coffee": 1.049 & "I had … cigarettes": 1.04999999999999999

#


**Bug ID:** BR-21

**Bug title:** Arbitrary modification of the final amount of caffeine and caffeine per cup leads to meaningless calculations

**Priority and severity:** P2 - High

**Description:** If on the caffeine calculator user arbitrarily changes the final amount and then arbitrarily changes the amount of caffeine per cup, calculations without mathematical meaning result, because the parameters do not automatically adjust to each other.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Write value 1 in the "I had … cups of coffee" input
3. Write value 100 in the "mg of caffeine" input

**Expected result:** It is expected the "mg of caffeine per cup" to change according on the other two parameters, so that a correct mathematical calculation results, in this case "mg of caffeine per cup" should be 100.

**Actual result:** The "mg of caffeine per cup" is set to default value, 107.5 mg.

**Test data:** "I had … cups of coffee": 1 & "mg of caffeine": 100

#


**Bug ID:** BR-22

**Bug title:** Insufficient information about the computer and how to interpret the data by the user

**Priority and severity:** P3 - Normal

**Description:** There is no detailed information about this calculator, its utility or advice for users based on the amounts of caffeine or tar they consume daily.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Write value 4 in the "I had … cigarettes"

**Expected result:** It is expected to receive some detailed analysis about these parameters, how they can influence the users health, and / or advice for decreasing the daily consumed quantity of caffeine / tar.

**Actual result:** It is shown a standard message that user exceeded the daily maximum intake of tar, but with no explanation or detailed about this quantity, or why is bad for user to overtake this limit.

**Test data:** "I had … cigarettes": 4

------


### :three: Bug Reports for the website of Techirghiol town hall https://www.primariatechirghiol.ro/ :arrow_down:
![screenshot](https://user-images.githubusercontent.com/115346533/205991540-fb29d651-fd66-4d1b-abaa-75ef08515732.jpg)



**Bug ID:** BR-23

**Bug title:** The Copyright of the website for the current year

**Priority and severity:** P4 - Low

**Description:** The Copyright of the website is not updated for the current year (in that case for 2022), but for 2021 (previous year).

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Scroll down to the footer of the website, where are Copyright details 

**Expected result:** It is expected to see the Copyright updated for the current year (2022) in the footer of the website.

**Actual result:** The Copyright is not updated for the current year, but for the previous one (2021).

**Test data:** /

#


**Bug ID:** BR-24

**Bug title:** The "Start" button and "Volume" button of the main page video do not work

**Priority and severity:** P3 - Normal

**Description:** When the video on the home page is turned on in a restricted format, the Start button and the Volume button in the lower left corner do not work properly.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Click on the video interface from the home page
3. Click on the Start button or Volume button from the lower left corner

**Expected result:** The video should stop when user clicks on the Start button, or to mute when user clicks on the Volume button.

**Actual result:** The Start button or Volume button does not make anything.

**Test data:** /

#


**Bug ID:** BR-25

**Bug title:** The "404" error page does not have a search bar for user

**Priority and severity:** P4 - Low

**Description:** The "404" error page does not have a search field for additional information and does not provide any indication to the user.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Write in the URL adress something random, without any meaning/ which does not exist on this website.

**Expected result:** A "404" custom error page should be displayed, with a search bar for additional information, or additional tips to help the user to find relevant results. 

**Actual result:** The "404" custom error page does not have a search bar for more information, and it does not help the user to find what he is looking for.

**Test data:** "https://www.primariatechirghiol.ro/pisici-cu-raze-laser"

#


**Bug ID:** BR-26

**Bug title:** In the Photo Gallery, the images cannot be viewed by switching between them

**Priority and severity:** P3 - Medium

**Description:** In the "Photo Gallery" section, the images cannot be viewed by switching between them with an arrow button, but must be selected and deselected one at a time.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Select "Photo Gallery" section from the left menu of the home page
3. Select one photo and try to switch between them

**Expected result:** The user should switch the photo between them with an arrow button, in the same interface. 

**Actual result:** The user must select a picture, then deselect it and choose another from the gallery.

**Test data:** /

#


**Bug ID:** BR-27

**Bug title:** The Contact section size font is too small for a normal user

**Priority and severity:** P3 - Medium

**Description:** The font size in the Contact section is too small to be easily read by a normal user, compared to other sections that have a larger font size (eg. "Purchasing" section).

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Select "Contact" section from the top menu of the home page
3. Try to read the information on this page

**Expected result:** The user should read easily any type of information about Town Hall contact.

**Actual result:** The information from "Contact" section are rather difficult to read by users, because the size font is too small. 

**Test data:** /

#


**Bug ID:** BR-28

**Bug title:** No concrete information in the "Botanical Garden" section

**Priority and severity:** P3 - Low

**Description:** The "Botanical Garden" section of the bottom-left menu of the main page does not provide any concrete information about it, but only a picture with a digital simulation of the garden.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/
2. Select "Botanical Garden" section from the bottom-left menu of the main page

**Expected result:** This section should contain relevant information about Botanical Garden of the Techirghiol town, information like schedule or entrance fees.

**Actual result:** There is no relevant information about this public objective, only a picture with a digital simulation of the garden.

**Test data:** /

#


**Bug ID:** BR-29

**Bug title:** The logo does not contain a link to the main page

**Priority and severity:** P3 - Normal

**Description:** The town hall logo from the header of the website does not contain any link to the main page.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Select a random section from the menu
3. Click on the town hall logo from the header of the website

**Expected result:** After clicking of the logo, the user should see the main page.

**Actual result:** The town hall logo does not make anything.

**Test data:** /

#


**Bug ID:** BR-30

**Bug title:** There is no Search bar on this site

**Priority and severity:** P2 - High

**Description:** There is no search bar for relevant information on this site.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/
2. Try to search something on that site, without knowing in which section to look

**Expected result:** In the upper right / left corner of the home page menu should be a search bar, for helping the user to find anything on the site.

**Actual result:** There is no search bar on this site.

**Test data:** "Cont IBAN"

#


**Bug ID:** BR-31

**Bug title:** The "News" link button in the footer of the site does not work

**Priority and severity:** P2 - High

**Description:** The "News" link button in the footer of the site does not work. Specifically, it leads to an error page and does not provide any news to users.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Scroll down to the footer of the website
3. Click on the News ("Știri") link button

**Expected result:** It is expected to be open a new page with news about town or other relevant problems.

**Actual result:** The link is not working, it leads to a "404" error page, without any relevant information.

**Test data:** /

#


**Bug ID:** BR-32

**Bug title:** The information of the European Projects section is incomplete

**Priority and severity:** P4 - Low

**Description:** In the European Projects section the information is incomplete, either the project data is not specified or it is not put at all links to more detailed documents.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/
2. Select Projects ("Proiecte") section from the header of the main page
3. Select European Projects ("Proiecte Europene") section
4. Try to open a link from this page

**Expected result:** Every document from this section should have detailed information about it, like data implementation, and a link to original documents of the projects.

**Actual result:** The projects data are not specified and it is not put at all links to more detailed documents.

**Test data:** /

#


**Bug ID:** BR-33

**Bug title:** The "Town Hall Management" section does not provide relevant information for citizens

**Priority and severity:** P2 - Normal

**Description:** The "Town Hall Management" section does not provide relevant information for citizens about the mayor and other political leaders, such as CVs or wealth declarations.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Select Town Hall Management ("Conducerea primăriei") section from the left menu of the home page

**Expected result:** The user should find easily any relevant details or documents about the mayor of the town or other political leaders, because these are publical information for everyone.

**Actual result:** There are missing a lot of relevant inforamtion, like CVs or wealth declarations.

**Test data:** /

#


**Bug ID:** BR-34

**Bug title:** The website design is not responsive

**Priority and severity:** P4 - Low

**Description:** The town hall website is not at all responsive to different resolutions.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/
2. Open the Console by pressing F12 and select different resolutions of the website

**Expected result:** The town hall website should have a responsive design on every type of screen resolution.

**Actual result:** The website does not have a responsive design, the writing becomes smaller and smaller.

**Test data:** /

#


**Bug ID:** BR-35

**Bug title:** There are two errors of the website into the console

**Priority and severity:** P2 - High

**Description:** There are two errors of the website in the Console, one related to a link that no longer exists and refers to an error page, and another is related to the CSS part and the loading of Bootstrap files.

**Steps to reproduce:**
1. Go on https://www.primariatechirghiol.ro/ 
2. Open the Console by pressing F12 key and select the Error section

**Expected result:** There should be no site error in the console after we open it.

**Actual result:** There are two important error of the website into the Console.

**Test data:** /

------


### :four: Bug Reports for the website of Piatra-Neamț city hall https://www.primariapn.ro/ :arrow_down:
![pn](https://user-images.githubusercontent.com/115346533/206227630-53686641-d7d6-4a16-98e6-8715e578c4e0.jpg)



**Bug ID:** BR-36

**Bug title:** Copyright is incomplete, without the current year (2022)

**Priority and severity:** P4 - Low

**Description:** The Copyright of the website does not mention the current year (2022). Actually, it does not mention any year.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Scroll down to the website footer, where is mentioned the Copyright

**Expected result:** It is expected to see the Copyright of the website, with current year updated (2022).

**Actual result:** The current year is not mentioned at all.

**Test data:** /

#


**Bug ID:** BR-37

**Bug title:** The "City Hall Management" section does not contain links for all town hall members

**Priority and severity:** P4 - Low

**Description:** In the City Hall Management section ("Conducerea primăriei"), no links with additional details are inserted for all members of the mayor's office.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on "City Hall Management" button ("Conducerea primăriei") from the left menu of the home page

**Expected result:** All the members of the mayor's office should have a valid link with additional information about, like CVs.

**Actual result:** Not all the members of the mayor's office have a functional link button with more relevant information.

**Test data:** /

#


**Bug ID:** BR-38

**Bug title:** The "Organization Chart" document is poorly sized, with illegible writing

**Priority and severity:** P4 - Low

**Description:** In the Organization Chart section, the document of the same name is poorly sized, the writing is largely illegible because it has a too small font size.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on Organization Chart button ("Organigramă") from the left menu
3. Click on Organization Chart document

**Expected result:** The Organization Chart document should be properly sized, and it should be easily read.

**Actual result:** The writing of the Organization Chart document is largely illegible because it has a too small font size.

**Test data:** /

#


**Bug ID:** BR-39

**Bug title:** The "Useful Information" section does not have links to all documents

**Priority and severity:** P3 - Low

**Description:** In the "Useful Information" section ("Informații utile"), not all the mentioned documents has a valid link attached, and some information is not updated for current year (2022).

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on Public Information from the top part of the menu
3. Select Useful Information from the list

**Expected result:** All mentioned documents should have a valid link to open them, and all information must be relevant and updated for current year.

**Actual result:** Not all the mentioned documents has a valid link attached, and some information is not updated.

**Test data:** /

#


**Bug ID:** BR-40

**Bug title:** The Enlarge font size button does not work properly on the Public Services section

**Priority and severity:** P3 - Normal

**Description:** In the Public Information / "Public Services" section, not all text is increased if we click on the "Enlarge Font" button ("Mărește Fontul") in the upper-right corner of the menu bar.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on "Public Information" section from the top menu
3. Select "Public Services" section from the list
4. Click on Enlarge Font button

**Expected result:** All the text of this section should be uniformly increased, in order to be easily read by the users.

**Actual result:** Only link and titles are enlarged if we click on the "Enlarge Font" button.

**Test data:** /

#


**Bug ID:** BR-41

**Bug title:** The online account sign up procedure involves the physical presence of the user

**Priority and severity:** P1 - High

**Description:** For user account registration on this site, in order to validate the user's account (step 4), the user must physically go to the Town Hall with their identity card. (See the attachment)

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on "Online account creation procedure" button ("Procedură creare cont online") from the right menu of the home page

**Expected result:** The steps for creating a new account are expected to be described as clearly as possible, and to be completed exclusively online by the user.

**Actual result:** To validate the online account, it is necessary that the user go to the Town Hall with they identity card, to access the account. (See the attachment, step 4)

**Test data:** /

**Attachments:**

![cont pn](https://user-images.githubusercontent.com/115346533/206232304-a63ff240-6330-4dc3-8872-f270ed0065b3.jpg)

#


**Bug ID:** BR-42

**Bug title:** The "Local Police" section does not contain any information

**Priority and severity:** P3 - Low

**Description:** The "Local Police" section ("Poliția Locală") does not contain any necessary information for users.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on Publical Services section from the top menu
3. Select "Local Police" button

**Expected result:** It is expected to see relevant information about Local Police of Piatra-Neamț, like Police stations and their adresses, phone numbers, operational staff etc.

**Actual result:** The "Local Police" section from this site does not contain any information for the users.

**Test data:** /

#


**Bug ID:** BR-43

**Bug title:** The General presentation information about the town cannot be reached directly through the web interface

**Priority and severity:** P2 - High

**Description:** The page with general presentation information about the town cannot be reached directly, but only by searching in the direct URL, or by searching in the search bar ("city presentation"). The description also contains several typos (missing diacritics, misspelled words).

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/
2. Search general information in the website about Piatra-Neamț

**Expected result:** It is expected to exist a special button / section with a general presentation of the town, which can be accessed easily.

**Actual result:** It does not exist a direct link button to general presentation information of Piatra-Neamț. This section can be accessed only by URL or search bar.

**Test data:** "prezentare oraș" in search bar or URL

#


**Bug ID:** BR-44

**Bug title:** Initially English is missing from the foreign languages translation menu

**Priority and severity:** P2 - High

**Description:** Initially, the English language is missing from the translation menu in foreign languages, the main language of international circulation. The English option appears only after we have selected another language from the menu. (See the attachments)

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Select the translation menu from the upper-right corner
3. Select a foreign language from this menu

**Expected result:** It is expected the English language to be one of the option when the translation menu is open. 

**Actual result:** The English language is missing from the translation menu in foreign languages. The English option appears only after we have selected another language from the menu. (See the attachments)

**Test data:** /

**Attachments:**

![English after another option](https://user-images.githubusercontent.com/115346533/206234480-4eec54d4-58e6-48db-b2e8-00df26d3a1cb.jpg)

![Missing English](https://user-images.githubusercontent.com/115346533/206234519-5a400971-2da8-4d53-8524-47b05c207295.jpg)

#


**Bug ID:** BR-45

**Bug title:** The translation functionality does not work for the whole text of the website

**Priority and severity:** P2 - High

**Description:** When a language is selected in which to translate the site (in this case French) not the whole text is translated, but only fragments and isolated words. (See the attachment)

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Select French from the translation menu in the upper-right corner

**Expected result:** The whole text of the website should be translated in French.

**Actual result:** Only fragments and isolated words are translated in the selected foreign language, the other part of the text is still presented in Romanian. 

**Test data:** /

**Attachments:**

![Incomplete translation](https://user-images.githubusercontent.com/115346533/206235976-9fbc0614-aada-4a07-9ecb-db05be78101b.jpg)

#


**Bug ID:** BR-46

**Bug title:** The site is loading harder on the Mozilla browser

**Priority and severity:** P3 - Normal

**Description:** The site requires more loading time on the Mozilla browser (more than 3 seconds) compared to Google Chrome and Microsoft Edge.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ in Mozilla browser
2. Open the Console by pressing F12 key and select Network
3. Press CTRL + R

**Expected result:** The website should load pretty fast, in less than 3 seconds.

**Actual result:** The loading time of this website on Mozilla browser is greater than 3 seconds.

**Test data:** /

#


**Bug ID:** BR-47

**Bug title:** The link to the Neamț County Council does not work

**Priority and severity:** P3 - Normal

**Description:** The link to the Neamț County Council website on the main page does not work, an error being reported.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/ 
2. Click on the Neamț County Council link ("Consiliul Județean Neamț") from the bottem-left menu of the home page

**Expected result:** The website of the Neamț County Council should open normally, in order to be accessed by users.

**Actual result:** When the link is select, an error page is open.

**Test data:** /

#


**Bug ID:** BR-48

**Bug title:** The links associated with the images on the Social Life page are broken

**Priority and severity:** P3 - Normal

**Description:** The links associated with the pictures on the Social Life page open in error.

**Steps to reproduce:**
1. Go on https://www.primariapn.ro/activitate-sociala
2. Click on the images from this section

**Expected result:** After selecting the images, it should open a 360-degree panoramic image.

**Actual result:** The links are broken, and they open error pages.

**Test data:** "https://www.primariapn.ro/activitate-sociala"

------


### :five: Bug Reports for the online demo banking website https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login :arrow_down:
![bank](https://user-images.githubusercontent.com/115346533/206239594-b7941008-5a2e-4d33-aeef-2806d1b273e0.jpg)



**Bug ID:** BR-49

**Bug title:** No information about copyright or banking policy

**Priority and severity:** P4 - Low

**Description:** There is no information about banking policy, copyright or other helpful guidance for a novice user.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login

**Expected result:** On the home page of the website should be information about Copyright and other useful guidance for users, for helping them.

**Actual result:** There is no information about this banking app, or about the author.

**Test data:** /

#


**Bug ID:** BR-50

**Bug title:** The number of the amount deposited can start with 0

**Priority and severity:** P2 - High

**Description:** When depositing a sum of money, the number can have its first digit 0 (eg. 0100).

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Click on Customer login button
3. Select one customer from the list and login
4. Click on Deposit button and write a number which starts with 0
5. Press Deposit button under Amount input

**Expected result:** It is expected the banking app should show an alert message that the deposited sum is incorrect written, because it is starting with digit 0.

**Actual result:** It is shown the message "Deposit Successful".

**Test data:** Amount to be Deposited: "0100"

#


**Bug ID:** BR-51

**Bug title:** Amounts with negative values can be selected for deposits and withdrawals

**Priority and severity:** P2 - High

**Description:** For deposits and withdrawals, negative values can be selected with the help of the spin-button element, which do not make any mathematical sense, because they cannot be added or withdrawn.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click on Customer login button
3. Select one customer from the list and login
4. Press on spin-button and select a negative value 
5. Click on "Deposit" button under Amount input

**Expected result:** The banking app should show an alert message that the selected amount is a negative one, and it can not be deposited or withdrawn.

**Actual result:** The negative value could be selected with spin-button, then nothing happens.

**Test data:** Amount to be Deposited: "-1"

#


**Bug ID:** BR-52

**Bug title:** No deposits or withdrawals can be made with decimal values

**Priority and severity:** P2 - High

**Description:** When we make deposits or withdrawals from the account, we can write decimal values in the input, but we are not allowed the transaction, being necessary only positive integers.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Click on "Customer login" button
3. Select one customer from the list and login
4. Click on "Deposit" button
5. Write a decimal value in the Amount to be Deposited input

**Expected result:** The user should be able to deposit or withdraw a decimal amount of money.

**Actual result:** It is shown an alert message to write valid integer numbers in Amount input.

**Test data:** Amount to be Deposited: "10.5"

#


**Bug ID:** BR-53

**Bug title:** The transaction history can be viewed only if a banking operation is currently performed

**Priority and severity:** P3 - Normal

**Description:** A customer's transaction history can be viewed only if a bank deposit or withdrawal transaction is currently being performed.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Click on "Customer login" button
3. Select one customer from list and login
4. Click on "Transactions" button
5. Deposit an amount of money, then click again on "Transactions"

**Expected result:** After login, the customer should be able to see the transactions by clicking the "Transactions" button, without any additional action.

**Actual result:** The customer can see the transactions history after he performed a deposit or withdrawal.

**Test data:** Amount to be Deposited: "100"

#


**Bug ID:** BR-54

**Bug title:** Accessing a client's account is done without a password

**Priority and severity:** P1 - Critical

**Description:** When a customer's situation is selected to be viewed, it is necessary to select only the username, without any password or other way to check the security of the account.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Click on "Customer login" button
3. Select a custom from the list

**Expected result:** After the selecting of a customer from the list, the banking app should ask for a password for that account, to ensure the security of the customer.

**Actual result:** It is necessary only the username of the customer, and then anyoane could login in that account, without any password.

**Test data:** /

#


**Bug ID:** BR-55

**Bug title:** The "Home" button has the same functionality as the Logout button

**Priority and severity:** P1 - Critical

**Description:** When a customer is logged in to their account and presses the Home button, the result is logging out of the account, just like the Logout button.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Select a customer from the list and login
3. Click on the "Home" button from the left corner

**Expected result:** The app should show the Home page, and the customer should stay logged in.

**Actual result:** The "Home" button logs the client out of its account, as Logout button.

**Test data:** /

#


**Bug ID:** BR-56

**Bug title:** The banking app allows spaces at the beginning and end of the customer's name

**Priority and severity:** P3 - Low

**Description:** When the name and postal code for a new customer are entered, the application allows them to be written with spaces at the beginning and at the end.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click on Bank Manager login button
3. Click on Add customer button
4. Complete the  First Name input
5. Complete the Last Name input
6. Complete the Post Code input and press Add customer

**Expected result:** The website should show an alert message that no spaces can be placed at the beginning or end of names or post codes.

**Actual result:** The website allows spaces at the beggining and at the end of the customers names and post codes.

**Test data:** "John" in the First Name input & "Doe" in the Last Name input & "A1234" in the Post Code input

#


**Bug ID:** BR-57

**Bug title:** Any type of characters can be written in the first name and last name inputs

**Priority and severity:** P2 - High

**Description:** When a user wants to add a new customer to the database, at First Name and Last Name he can write any type of character, including numbers, diacritics or special characters. (See the attachment)

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Click on Bank Manager Login button
3. Click on Add Customer button
4. Complete the First Name and Last Name inputs with special characters and numbers
5. Click on Add customer button

**Expected result:** The banking app should not allow to validate names which includes special characters or numbers.

**Actual result:** The banking app records the names of customers that contain special characters.

**Test data:** First Name: "1234" & "!@#$%" & Last Name: "1234" & "ăîțșâ,,,,.?"

**Attachments:**

![user name](https://user-images.githubusercontent.com/115346533/206246361-b04f2d6e-122d-45a8-a6e8-15ef16012b34.jpg)

#


**Bug ID:** BR-59

**Bug title:** There is no custom "404" error page

**Priority and severity:** P4 - Low

**Description:** There is no custom "404" error page that tells the user that the search result does not exist, and may be directed to what they are looking for by additional hints or a search bar.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Write something that does not exist on this website in the home page URL

**Expected result:** The website show a custom "404" error page with a search bar and additional hints for user to improve his searching on the website.

**Actual result:** Nothing happens when it is searched something wrong in the home page URL.

**Test data:** "https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login/pisici-mutante"

#


**Bug ID:** BR-60

**Bug title:** The banking application is not fully responsive

**Priority and severity:** P3 - Low

**Description:** The banking application does not have a fully responsive design when it is selected a lower screen resolution.

**Steps to reproduce:**
1. Go on https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Open the Console by pressing F12 key
3. Select a lower resolution for this website (less than 800 pixels)

**Expected result:** The banking app should have a responsive design, to match different resolutions, and to be used by customers from any type of device.

**Actual result:** The application is not fully responsive, the writing shrinks and becomes unreadable.

**Test data:** /

#
