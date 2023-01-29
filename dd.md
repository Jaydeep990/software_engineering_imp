# **20 Python Project**

| **No** |            **Name**             | **Project Link** |
| :----: | :-----------------------------: | ---------------- |
| **1**  |        **Email Sender**         |                  |
| **2**  |  **Word Replacement Program**   |                  |
| **3**  |      **Basic Calculator**       |                  |
| **4**  |        **Email Slicer**         |                  |
| **5**  |   **Binary Search Algorithm**   |                  |
| **6**  |        **Quiz Program**         |                  |
| **7**  |      **QR Code Generator**      |                  |
| **8**  | **Interest Payment Calculator** |                  |
| **9**  |  **Random Password Generator**  |                  |
| **10** |   **Dice Rolling Simulator**    |                  |
| **11** |  **Site Connectivity Checker**  |                  |
| **12** |     **Currency Converter**      |                  |
| **13** |      **Leap Year Checker**      |                  |
| **14** |       **Word Dictionary**       |                  |
| **15** |    **Rock, Paper, Scissors**    |                  |
| **16** |    **Python Face Detection**    |                  |
| **17** |      **Python Automation**      |                  |
| **18** |         **Web Scraper**         |                  |
| **19** |        **Image Resizer**        |                  |
| **20** |        **Graph Plotter**        |                  |

## **1. Email Sender**

<!-- info -->

> Step I follow to build this `Email Sender`.

1. Go over to your gmail account and setup 2 factor authentication.

2. Generate app password from your google account's security section. [google account security section link](https://myaccount.google.com/security)

3. Crate a function to send the mail.

> **I used `EmailMessage` class, `ssl` module and `smtplib` module.**

```python
from email.message import EmailMessage
import ssl
import smtplib
```

### **EmailMessage**

Python has EmailMessage class which can be used build email messages. This class has the required methods to customize different parts of the email message like - the TO and FROM tags, the Subject Line as well as the content of the email.

### **ssl**

This module provides access to Transport Layer Security (often known as “Secure Sockets Layer”) encryption and peer authentication facilities for network sockets, both client-side and server-side.

### **smtplib**

The smtplib module defines an SMTP client session object that can be used to send mail to any internet machine with an SMTP or ESMTP listener daemon. For details of SMTP and ESMTP operation, consult RFC 821 (Simple Mail Transfer Protocol) and RFC 1869 (SMTP Service Extensions).

## **2. Word Replacement Program**

<!-- info -->

> Step I follow to build this `Word Replacement Program`.

1. I build a `replce_word()` function to run the word replacement program.

2. I used `replace()` method to replaces a specified phrase with another specified phrase.

## **3. Basic Calculator**

<!-- info -->

> Step I follow to build this `Basic Calculator`.

1. Define a four function to calculate a certain operation on two numbers.

   - `add()` -> Additon
   - `sub()` -> Substraction
   - `mul()` -> Multiplication
   - `div()` -> Division

2. Define infinte while loop to take input from user to perform basic calculation.

3. If user give `E` as a input then program end.

## **4. Email Slicer**

<!-- info -->

> Step I follow to build this `Email Slicer`.

1. I build a `slicer()` function to run the `Email Slicer`.

2. I used `split()` method to split the string.

3. Show the Username, Domain and Extension.

## **5. Binary Search Algorithm**

<!-- info -->

> Step I follow to build this `Binary Search Algorithm`.

1. Set the start index to the first element of the list and the end index to the last element.
2. Set the middle index to the average of the start and end indices.
3. If the element at the middle index is the target element, return the middle index.
4. If the target element is less than the element at the middle index, set the end index to the middle index – 1.
5. If the target element is greater than the element at the middle index, set the start index to the middle index + 1.
6. Repeat steps 3-6 until the element is found or it is clear that the element is not present in the list.

## **6. Quiz Program**

<!-- info -->

> Step I follow to build this `Quiz Program`.

1. I create a `quiz`, it is a dictionary of questions.

2. I create a `test()` function to conduct test.

3. I create a `show_result()` function to show the result.

## **7. QR Code Generator**

<!-- info -->

### What is a QR Code?

A Quick Response code is a two-dimensional pictographic code used for its fast readability and comparatively large storage capacity. The code consists of black modules arranged in a square pattern on a white background. The information encoded can be made up of any kind of data (e.g., binary, alphanumeric, or Kanji symbols)

> Step I follow to build this `QR Code Generator`.

1. I have to install two library `qrcode` and `Image`.

2. I create a `generate_qrcode` function which generate QR code and save it as a image.

### **qrcode**

QR Code image generator

### **Image**

Django application that provides cropping, resizing, thumbnailing, overlays and masking for images and videos with the ability to set the center of attention,

## **8. Interest Payment Calculator**

<!-- info -->

> Step I follow to build this `Interest Payment Calculator`.

1. Define a method to run this `Interest Payment Calculator`.

2. Implement formula for monthly payment for a loan.

3. Show the monthly payment for a loan.

## **9. Random Password Generator**

<!-- info -->

> Step I follow to build this `Random Password Generator`.

1. I have to import `string` and `random` module.

2. I create `generate_password()` function which generate the password from the user's required password's length.

### **random**

Python Random module is an in-built module of Python which is used to generate random numbers.

### **string**

Python string module is an in-built module of python which is used to quickly access some string constants.

## **10. Dice Rolling Simulator**

<!-- info -->

> Step I follow to build this `Dice Rolling Simulator`.

1. I have to import `random` module.

2. I create a `dice_drawing`, it is dictionary that contain key as a number and value as a drawing of a dice.

3. I create a `roll_dice()` function which ask for user for to `Roll the dice? (Yes/No)` & if Yes then print the random 2 dice drawing & again it ask for user to `Roll again? (Yes/no):` & if No then end the program.

### **module random**

Python Random module is an in-built module of Python which is used to generate random numbers.

## **11. Site Connectivity Checker**

<!-- info -->

> Step I follow to build this `Site Connectivity Checker`.

1. I have to import `urllib.request` module.

2. I create a `check_connectivity()` to check the connection of url & show the response code if connection is successfull.

### **urllib.request**

The urllib.request module defines functions and classes which help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more.

## **12. Currency Converter**

<!-- info -->

> Step I follow to build this `Currency Converter`.

1. I create a `currency` function which take input from the user as a dollar & call the `convert_to_rupees` function & then show the rupee as a output.

2. I creat a `convert_to_rupees` function which calculate the dollar to rupee.

## **13. Leap Year Checker**

> Step I follow to buld this `Leap Year Checker`.

1. I create a flow chart for this `Leap Year Checker`.

2. I create a `is_leap_year` & implement the logic to it.

## **14. Word Dictionary**

> Step I follow to build this `Word Dictionary`.

1. I have to install `PyDictionary` module.

   ```cmd
   pip install -e git+https://github.com/yeahwhat-mc/goslate#egg=goslate
   pip install PyDictionary
   ```

2. I have to import `PyDictionary` class from the PyDictionary module.

   ```python
   from PyDictionary import PyDictionary
   ```

3. I create a `word_dictionary()` function which take input fron the user as word & show meaning to the word.

### **PyDictionary**

PyDictionary is a Dictionary Module for Python 2/3 to get meanings, translations, synonyms and Antonyms of words. It uses WordNet for getting meanings, Google for translations, and synonym.com for getting synonyms and antonyms.

This module uses Python Requests, BeautifulSoup4 and goslate as dependencies.

## **15. Rock, Paper, Scissors**

> Step I follow to build this `Rock, Paper, Scissors`.

1. I have to import `random` module.

2. I create a `play()` function which run the program (The game) & show `user_points`, `computer_points`.

### **random module**

Python Random module is an in-built module of Python which is used to generate random numbers.

## **16. Python Face Detection**

> Step I follow to build this `Python Face Detection`.

1. I have to install `opencv`.

   ```cmd
   pip install opencv-python
   ```

2. I have to import `cv2`.

3. I have to use some pre-defined function to build this `Python Face Detection`.

### **OpenCV-Python**

`OpenCV-python`is a library of Python bindings designed to solve computer vision problems.
`cv2.imread()` method loads an image from the specified file.

## **17. Python Automation**

<!--  -->

> Step I follow to build this `Python Automation`.

1. I have to import 3 module `requests`, `schedule` and `time`.

   ```python
   import requests
   import schedule
   import time
   ```

2. I create a `send_message()` function which sends the POST request.

## **18. Web Scraper**

<!-- info -->

> Step I follow to build this `Web Scraper`.

1. I have to install `beautifulsoup4` library.

   ```cmd
   pip install beautifulsoup4
   ```

2. I have to import `request` module and `BeautifulSoup` class.

3. I create a `get_title()` function which show the all title present in `'http://codewithtomi.com/'` website.

## **19. Image Resizer**

<!-- info -->

> Step I follow to build this `Image Resizer`.

1. I have to install `Pillow` library.

2. I have to import `Image` from the `PIL`.

3. I create a `resize_image()` function which take Width & Height from the user & save the resize image.

### **PIL**

PIL is the Python Imaging Library by Fredrik Lundh and Contributors. Copyright (c) 1999 by Secret Labs AB.

### **20. Graph Plotter**

<!-- info -->

> Step I follow to build this `Graph Plotter`.

1. I have to install `matplotlib`.

   ```cmd
   pip install matplotlib
   ```

2. I have to import `matplotlib.pyplot`.

3. I just create a simple graph with build-in function of matplotplotlib library.

## **matplotlib**

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.
