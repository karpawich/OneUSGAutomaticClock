# OneUSGAutomaticClock (updated 1-10-21)
This is a little script for Georgia Tech students to be able to automatically clock hours without worrying about forgetting to turn it off.

It can be easily modified to work for any university in the USG system 
(If you have any questions on how to do this, feel free to reach out, I can make a fork that works for any of the universities). 

## Requirements:
- Python 2.7+ (or 3+) [Find Here] (https://www.python.org)
- selenium [Find Here] (https://www.selenium.dev/documentation/en/)
- chromedriver_autoinstaller [Find Here] (https://pypi.org/project/chromedriver-autoinstaller/)

## Set-Up Instructions: 
To get Python simply click [here](https://www.python.org/downloads/).
Once you have python, go to any terminal and write the following two things:

`pip install selenium`

`pip install chromedriver_autoinstaller`

Then clone the repo, for self-help click [here](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/).

Finally, go to the *clock_manager.py* file and edit the User Variables to clock how many hours you want. 
![A screenshot of the User Variables Code](https://github.com/Shaun-Regenbaum/OneUSGAutomaticClock/blob/master/Pictures/User%20Variables.PNG)

Just remember, you will need to confirm on duo 2fa (two factor authentication) one time.

## Help and Reach out:
I know that getting code up and running can be very frustrating, so please if you have any problems with python or cloning the repo (or anything else) reach out to me at shaunregenbaum@gmail.com or leave an issue!
If you have any others questions at all, please reach out!

## Note: 
If you want to get the chromedriver manually, or are having problems, you can download the appropriate chromedriver for your OS from [here](https://sites.google.com/a/chromium.org/chromedriver/home). You will need to manually add this driver to your path and and modify the code to correctly reference it [as such](https://chromedriver.chromium.org/getting-started).

