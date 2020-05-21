# Week 1 Learning Activity - COMP905
## Intro
Welcome to the first week of COMP905! As we spent some time this week reviewing your course outline, learning plan, and academic policies, this learning activity will be slighlty shorter than usual. In this weeks learning activity we will investigatge how to properly setup a Python development environment and also put into practice the theory we covered on what a programming language is and the different data types.

## Part 1 - Python Development Environment
While there are many editors that are capable of working with Python, in this course we are going to be using Visual Studio Code (VSCode). This is a free and open source editor developed by Microsoft that can handle many different languages thanks to its large extension ecosystem. It is a popular editor in industry and will give you the tools you need to further your career in programming. 

### Installing Visual Studio Code
To install Visual Studio Code you can visit [Microsofts website](https://code.visualstudio.com/download) and download the editor on a Windows, Mac, or Linux based PC. Be careful not to confuse Visual Studio Code with Visual Studio. Visual Studio is a more comprehenisve integrated development environment used by many for developing games and other large applications in different C languages. For this course, we will not be using Visual Studio but instead Visual Studio Code.

![Visual Studio Code Download Page](https://res.cloudinary.com/cst-slc/image/upload/v1590075595/3C65D409-4AB2-4475-9E00-DDFCC5D05822_y0ocww.jpg)

### Installing Python
To install Pytho you can visi the [Python Website](https://www.python.org/downloads/) and download the latest version for Windows, Mac, or Linux. Keep in mind that we will be using version 3 of Python for this course. If you already have version 2 installed on your computer, you will need to make sure that VSCode will use the correct version (more on this in a bit).

![Python Download Page](https://res.cloudinary.com/cst-slc/image/upload/v1590075840/7C972A7C-72F2-4571-8B0F-F14E4A2C6510_mphjpe.jpg)

### Installing Python Extension for VSCode
The final step you will need to take in order to complete your Python development environment is to install the Python extension into VSCode. To do so, you can follow these instructions:

1. Open VSCode

2. Open the Extensions side panel. You can do this by pressing Ctrl-Shift-X on Windows & Linux or CMD-Shift-X on Mac.

3. Search for the word Python in the Exensions side panel and click on Install.

![Python Extensions VSCode](https://res.cloudinary.com/cst-slc/image/upload/v1590076200/028A7AD1-F65B-4ABA-8309-19D902D25502_nqsdx7.png)

4. Close VSCode after the installation is complete

5. Open VSCode and create a new .py file by pressing Ctrl-N on Windows & Linux or CMD-N on Mac. Select a location to save your file, give it a name, and make sure that the file type is .py

6. Check that VScode is using the correct version of Python and if not, change it by clicking on the version (area highlighted in yellow in the below screenshot) and selecting version 3.

![VSCode Python Version](https://res.cloudinary.com/cst-slc/image/upload/v1590084018/4BD0BA15-24EA-4071-8522-E32F011069B9_idumxu.jpg)

### VSCode Shortcut Cheat Sheets
It is highly recomended that you use as many shortcuts as possible when learning to use VSCode. When you are programming, the more times you have to take your hands off the keyboard and reach for the mouse, the longer it will take you to complete your work. It may seem like a small amount of time, but if you add up all the time you do this in a couple hours of progamming, it makes a big difference. Below are the shortcut cheat sheets for Windows, Mac and Linux.

![VSCodd Cheat Sheet Windows](https://res.cloudinary.com/cst-slc/image/upload/v1590076797/7CAF2D89-B83A-4017-9A5B-5756B3ACAA53_hg6c2d.png)

![VSCodd Cheat Sheet Mac](https://res.cloudinary.com/cst-slc/image/upload/v1590076798/0DA34316-F180-458D-8D38-970DEFB9A8D1_ek4wj2.jpg)

![VSCodd Cheat Sheet Linux](https://res.cloudinary.com/cst-slc/image/upload/v1590076798/B396EA7B-DE71-4865-AF24-5AF3AC9C88A7_ymgszy.jpg)

## Part 2 - What is programming and why do we program?
Below are a couple comprehension questions that will help you start thinking in the mindset of a programmer. Please create a new .txt file in VSCode and title it **lastname-firstname-comp905-la-1.txt**. This file will be where you write your answers for the following questions.

1. In your own words, explain how English and Python (or any programming language) are similar.

2. Below is a short example of a business process. Right down the steps of the business process in the proper order and in point form. For each step, explain how it may be able to be replaced with a program or if not explain why not.

> Sam owns a web design agency. Sam has several employees who work for him to build the websites that Sam sells to customers. Sam will sell a website to a customer by having coffee with them and discussing what they need to meet their goals. After the initial meeting, Sam has to remember to follow up with the customer a couple weeks later to make sure that they are still interested in working with him. While Sam has his meetings with prospective clients and does his follow ups, he also has to manage his existing projects. One big task for Sam is following up with his employees each week to remind them to give him updates on their progress. He reaches out to them by email each week to do this. Eventually Sam will sell a website after several follow ups with different clients. After Sam sells a website, he has to get all of the information from the client for the website. He writes this all down and then later has a meeting with his employees to explain it all to them. His employees now work on the site and the process continues.

## Part 3 - Identifying appropriate data types
In the following exercise, we will test our knowledge of Python data types by selecting the assigning the appropriate data to each variable provided in the code below. Follow these steps to complete this learning activity:

1. Copy the code below into a new .py file in VSCode, name the file **lastname-firstname-comp904-la-1.py. 

```python
first_name = 
last_name =
birth_year =
is_active =
todos =

print(f'first_name is a variable of type {type(first_name).__name__} and its value is {first_name}')
print(f'last_name is a variable of type {type(last_name).__name__} and its value is {last_name}')
print(f'birth_year is a variable of type {type(birth_year).__name__} and its value is {birth_year}')
print(f'is_active is a variable of type {type(is_active).__name__} and its value is {is_active}')
print(f'todos is a variable of type {type(todos).__name__} and its value is {todos}')

```

2. Edit the code (do not edit variable names or print statements) so that each variable provided to you is associated with data according to the data type that is appropriate based on the name of the variable (data given to variable can be made up but must be of the appropriate data type)

3. Run your code and view the output by right-clicking the Python file in the explorer on the left and select Run Python File in Terminal. You will see output at the bottom like in the picture below.

![Running Python in VSCode](https://res.cloudinary.com/cst-slc/image/upload/v1590084367/0644A8FC-7545-47F9-9BF9-F9F3A9970DB0_li7woy.png)






