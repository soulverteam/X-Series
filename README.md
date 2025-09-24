# Introducing the Soulver X Series

In 2024 we embarked on a multi-year R&D project for Soulver.

The mission:

-  To explore advanced feature ideas for Soulver
-  To seek out new forms and workflows
-  To boldly go where no notepad calculator has gone before 🖖

We plan on releasing a new entry in the Soulver X series yearly.

## Soulver X2 (2025)

### Inline Subsheets
A subsheet is a separate sheet that lives inside a single token. 
- Just like line references, you can use the result of a subsheet in your calculations
- Subsheets can reference variables from the mother sheet (provided the variables are declared above the subsheet's line).
- Create a subsheet from the + button in the tab bar.
- Double-click the token to open the subsheet editor.

### Slider Tokens
- Create a slider from the + button in the tab bar
- Sliders are inline tokens that let you specify a minimum/maximum range via a pop-up
- This is more sophisticated than the number scrubbing feature, which did not let you specify the desired range

### Divider Lines
- Use divider lines to create more visual separation between different parts of your sheet
- Type dash (-) three times to insert a divider line

## Soulver X1 (2024)

<img src="Images/Introducing%20X1.png" alt="Introducing Soulver X1" width="800"/>

X1 includes implementations of Soulver's top three most requested features:

-  Custom function support (including natural language functions)
-  Sharing variables across sheets (via the new 'header')
-  Connecting to Web APIs (with a paste and a couple of clicks)

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

## Detailed Documentation

You can find more detailed documentation for Soulver X [here](https://documentation.soulver.app/experimental-features/x).

## Supporting the X Series

We invented the modern notepad calculator (with an answer column alongside a text editor) in 2005, and we envision more exciting advancements arising from this research too.

- If you're a long-time user of Soulver (or a mega-fan), and think this research is worthwhile, consider becoming a [one-time or monthly GitHub](https://github.com/sponsors/soulverteam) sponsor
- All sponsors receive access to the latest app in the series (currently X2)
- Monthly sponsors also get a copy of [Soulver Mini](http://soulver.app/mini/) for Mac, and pre-release builds of Soulver 4 for Mac & iOS (also in development)
- With your support, our (very) small team will dedicate more resources to this kind of advanced notepad calculator research
