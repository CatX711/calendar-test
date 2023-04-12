# calendar-test

## A simple calendar test that will be worked on in the future.

# Code:

*For simplicity let's name this file "calendar test".*

```py
import datetime 
date = str(input('Enter the date(for example:09 02 2019):'))
day_name= ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday','Sunday']
day = datetime.datetime.strptime(date, '%d %m %Y').weekday()
print(day_name[day]) 

```
*What this code does, is become farmilliarised with the days of the week, and, using datetime recognises the year. When run, you have to enter a date (eg. 08 06 2012) and locates the day for that date.*

## Examples:

*To show you what this program can do, here's some text I got when running the program:*

```
Enter the date(for example:09 02 2019):

```
*I then typed my answer and got this result:*

```
Enter the date(for example:09 02 2019):11 10 1880
Monday

```
*You can expand on this concept, like using it in games, and things like that, so if you want to, go ahead!*

# Errors:

*When you don't type anything, and just hit enter, the program will become confused, resulting in a lengthy error.*

*(I've blurred out my username with multiple astrics, for privacy reasons. Thanks for understanding!*
```
Traceback (most recent call last):
  File "C:\Users\******\AppData\Local\Programs\Python\Python310\calendar test.py", line 4, in <module>
    day = datetime.datetime.strptime(date, '%d %m %Y').weekday()
  File "C:\*******\AppData\Local\Programs\Python\Python310\lib\_strptime.py", line 568, in _strptime_datetime
    tt, fraction, gmtoff_fraction = _strptime(data_string, format)
  File "C:\Users\*******\AppData\Local\Programs\Python\Python310\lib\_strptime.py", line 349, in _strptime
    raise ValueError("time data %r does not match format %r" %
ValueError: time data '' does not match format '%d %m %Y'

```
# Thanks for reading!

*I hope this was useful!*
