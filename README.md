### github-gallery

Simple dynamic HTML page that uses GitHub's REST API to dynamically generate a gallery of your GitHub projects.
The script assumes that you have a file named 'screenshot.png' on the 'master' branch of each project.

The JavaScript in this page accepts a 'userName' HTTP request parameter that overrides what is hard-coded in the page.

Note that GitHub has a rate limit of 60 API requests/hour for unauthorized requests ; rewriting the JSON request handling to use authentication is still on my TODO list...

![screenshot](https://github.com/toby1984/github-gallery/blob/master/screenshot.png?raw=true)
