# HTML Crash Course

Use this as a quick introduction into HTML that will teach you the basics needed to follow along in my other web development courses.

## Form challenge

Create a registration page called `form_challenge.html` with the following fields:
- **Name** (text field, required)
- **Email** (email field, required)
- **Birthdate** (date field, maximum date set to a year ago)
- **Biography** (textarea with a placeholder telling the user to write a bit about themselves)
- **What animal do you most relate to?** (select with the options: Mountain Chicken, Spider Monkey, Dik-dik, Agra cadabra, Sparklemuffin, Sarcastic fringehead. Make Spider Monkey the selected option)
- **Will you accept our spam mail?** (3 radio inputs with the labels: "Heck no!", "A little, maybe", "Fill my inbox, man!")
- **By signing up on this site I pledge to sell my soul to Web Spider Monkey at the bargain price of 1 Dogecoin.** (checkbox, checked by default)
- **Sign me up, already!** (submit button)

Remember to give the fields appropriate names (for example give the "What animal do you most relate to" field the name of "animal")

Make the form submit via **POST** to a page called `registered.html` where the user will see a message that they've been registered.

Check the "network" tab of your browser's developer tools (press F12 to open them) to see if the form data was correctly passed to the registered.html page.

## Solution

Check to `form-solution` branch for a sample solution.

## Author

* Chris Rollins - [Web Spider Monkey](https://github.com/webspidermonkey)
