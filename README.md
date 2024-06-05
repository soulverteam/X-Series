# Introducing the Soulver X Series

We are considering embarking on a multi-year R&D project for Soulver.

Our mission:

-  To explore advanced feature ideas for Soulver
-  To seek out new forms and workflows
-  To boldly go where no notepad calculator has gone before 🖖

## Soulver X1

Our tentative first release in this work is Soulver X1.

<img src="Images/Introducing%20X1.png" alt="Introducing Soulver X1" width="800"/>

It includes implementations of our top three most requested features:

-  Custom function support (including natural language functions)
-  Sharing variables across sheets (via the new 'header')
-  Connecting to Web APIs (with a paste and a couple of clicks)

## Experimental features in X1

### Tabs & the header

Documents have multiple tabs in Soulver X1.

<img src="Images/Tabs%20&%20header.png" alt="Tabs & header" width="800"/>

A dedicated "header" lets you define variables, units, and functions that are available across all of them. 

You use the header to define both "equivalence units" (defined in terms of an existing unit), and (new in X1) generic units that are entirely new unit types.

### Declare custom functions

You can use almost any syntax you like for custom functions:

-  C-style: `doSomething(123)`
-  Swift-style: `doSomething(with: 123)`
-  Or even natural language: `do something with 123`

Provide Soulver X1 with an example of how you plan to *use* the function, and then implement it in a dedicated sheet.

Parameters are injected as tokens.

<img src="Images/Defining%20a%20custom%20function.png" alt="Defining A Custom Function" width="800"/>

Once a function has been defined, you can use it with different parameters (that match by type) across your sheets.

<img src="Images/Custom%20function%20in%20use.png" alt="Custom Function In Use" width="800"/>

### Web values

Connecting to remote data sources is as easy as pasting in a link to a JSON feed and then clicking on your desired data point.

<img src="Images/Adding%20a%20web%20value.png" alt="Adding A Web Value" width="800"/>

The data point will be assigned a variable name that you can refer to across your sheets. The data point will be periodically fetched for you in the background at a frequency you specify.

## Supporting this project

We invented the modern notepad calculator (with an answer column alongside a text editor) in 2005, and we envision more exciting advancements arising from this research too.

- If you're a long-time user of Soulver (or a mega-fan), and think this research is worthwhile, consider becoming a [one-time or monthly GitHub](https://github.com/sponsors/soulverteam) or Patreon sponsor
- All sponsors (monthly or one-time) will receive access to Soulver X1
- Monthly sponsors will also get access to the latest X series release (X2, X3, etc), as well as a copy of [Soulver Mini](http://soulver.app/mini/) for Mac, and pre-release builds of Soulver 4
- With your support, our (very) small team will dedicate more resources to this kind of advanced notepad calculator research
