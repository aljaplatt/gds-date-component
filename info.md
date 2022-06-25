1. app folder

config file - serviceName - change to your project name

2. assets 

application.js - for vanilla js - available throughout app 

same for patterns > application.sass - can put css in here 

3. data - session-data-defaults

4. views 
{% extends layout.html %} - allows us to inherit design system macros

layout.html - sets layout over whole app that extends the layout.html

- save everything to session storage
as long as you're within a form, have a button inside the form, it will save and submit anything that has a name property associated to the input.

class=form
action= where the form should move on to - next question 

name 
name: 'name' =  value: data['name']

namePrefix: 'dob'  = value: data['dob-month']