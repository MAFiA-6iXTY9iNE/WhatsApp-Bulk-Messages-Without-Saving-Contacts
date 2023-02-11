# WhatsApp Bulk Messages Without Saving Contacts

It is a python script that sends WhatsApp message automatically from WhatsApp web application without saved contact numbers. It can be configured to send advertising messages to recipients. It read data from an excel sheet and send a configured message to people.

## Prerequisites

In order to run the python script, your system must have the following programs/packages installed and the contact number should be saved in your phone (You can use bulk contact number saving procedure of email). There is a way without saving the contact number but has the limitation to send the attachment.
* Python : Download it from https://www.python.org/downloads
* Chrome : Download it from https://chrome.google.com
* Pandas : Run in command prompt **pip install pandas**
* Xlrd : Run in command prompt **pip install xlrd**
* Selenium: Run in command prompt **pip install selenium** 
* Web Driver: Run in command prompt **pip install webdriver_manager**
* Openpyxl: Run in command prompt **pip install openpyxl**

## Approach
* First need to clone this respiratory
* Run python script script.py using py script.py in the terminal
* The script opens WhatsApp web using chrome.
* User needs to scan QR code from his/her phone.
* Enter in command prompt to execute further.
* The script hit url with contact number and message from excel sheet.
* Once all the message will be sent chrome driver will automatically closed.

Note: If you wish to send an image instead of text you can write attachment selection python code.

