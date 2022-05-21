# calendar-test

## A simple calendar test that will be worked on in the future.

# Code:

```
import datetime 
date=str(input('Enter the date(for example:09 02 2019):'))
day_name= ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday','Sunday']
day = datetime.datetime.strptime(date, '%d %m %Y').weekday()
print(day_name[day]) 

```
*What this code does, is become farmilliarised with the days of the week, and, using datetime recognses the year. When run, you have to enter a date (eg. 08 06 2012) and locates the day for that date.*

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
