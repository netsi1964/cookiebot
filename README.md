# cookiebot
Simple test of cookiebot

This is a simple test of [Cookiebot](https://www.cookiebot.com/da/). This inserts a cookiebot based cookie consent dialogue.

It does only a few things:

* It changes the logo on runtime
* It hides the powered by cookiebot
* It shows alerts for each of the categories which the user gives consent to
* Linked to a Google Analytics test also. You should get an error while clicking the event button, if consent to statistics it not given.

### Use attributes on `script` tag to place code in category manually
You can also see how you can add some script in a cookiebot consent category:

`script type="text/plain" data-cookieconsent="statistics"` would block the script from running until consent is given by the user to the `statistics` category of cookies.

Four categories exists:

* preferences
* statistics
* marketing
* "required" = any other value for the data attribute, for instance `data-cookieconsent="always_executed"`


See the code in action on [https://cookiebot.netlify.app/](https://cookiebot.netlify.app/)
