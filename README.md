Intro Finder
============
Given a list of LinkedIn profile URLs, show how far those users are from you in LinkedIn's social graph. For users 2 degrees separated from you (i.e. friends of friends) show a list of your LinkedIn connections that can make a direct intro.

Try it [here](https://www.paywithpenny.com/intro_finder)!

Run It Locally
--------------
This whole tool is implemented as static HTML and JavaScript. You can easily run it locally using python's built-in static webserver:

    python -m SimpleHTTPServer 8000

The page will now be available at [http://localhost:8000](http://localhost:8000).

Run It On a Server
------------------
To run it on your own server (instead of `localhost`), you'll need to create your own LinkedIn API key [here](https://www.linkedin.com/secure/developer) and put that in the `<head>` section of `index.html` next to `api_key:`.

License
-------
This code is licensed under the MIT license. In short, you can do whatever you want with this code, but you can't sue us if it doesn't work. Use of the LinkedIn API is governed by the [LinkedIn API Terms of Use](https://developer.linkedin.com/documents/linkedin-apis-terms-use).