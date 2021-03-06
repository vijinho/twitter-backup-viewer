An experimental project to update the default twitter backup files viewer. This is a companion project for [@vijinho/tweets-cli](https://github.com/vijinho/tweets-cli) which is used to generate the data files for viewing (using the *--grailbird* option on that script).

# Changes

Updated/upgraded files:

- jquery 1.8.3 -> [jquery 3.3.1](https://jquery.com/upgrade-guide/3.0/#jquery-migrate-plugin)
- underscore 1.4.1 -> [underscore 1.9.1](https://underscorejs.org/)
- hogan 2.0.0 -> [hogan 3.0.1](https://twitter.github.io/hogan.js/)

# Improvements

Taken from [@mislav/tweets](https://github.com/mislav/tweets/commits/master):

- Ability to add URL tweets search parameter 'q' i.e. index.html?**q=test**
- Unminified css/application.css and modified to preserve line-breaks in tweet (also updated css/application.min.css with this change)
 
# How to use your Twitter archive

The simplest way to use your Twitter archive is through the archive browser interface provided in this file. Just double-click `index.html` from the root folder and you can browse your entire history of Tweets from inside your browser.

---

In the `data` folder, your Twitter archive is present in two formats: JSON and CSV exports by month and year.

* CSV is a generic format that can be imported into many data tools, spreadsheet applications, or consumed simply using a programming language.

## JSON for Developers

* The JSON export contains a full representation of your Tweets as returned by v1.1 of the Twitter API. See https://dev.twitter.com/docs/api/1.1 for more information.
* The JSON export is also used to power the archive browser interface (index.html).
* To consume the export in a generic JSON parser in any language, strip the first and last lines of each file.

To provide feedback, ask questions, or share ideas with other Twitter developers, join the discussion forums on https://dev.twitter.com.
