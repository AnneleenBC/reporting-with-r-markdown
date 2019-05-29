### Context

We will take the lay out of your document one step further. Sometimes, the available Bootstrap themes are not good enough for the report we have in mind. For instance, we might want to brand our report in DataCamp's style. This is where CSS stylesheets come in place.
CSS is a language that describes how HTML elements are to be displayed on screen, paper, or in other media. It can control the layout of multiple web pages all at once, as such saving us a lot of work.
Writing a CSS stylesheet goes beyond the scope of this course. But to get an idea of the information encoded in a css stylesheet, take a look at the `datacamp.css` at the right.
When working with an external stylsheet, we need to set the `theme` parameter in the YAML header to `null`. We can highlight the syntax using one of the available styles, such as `tango`. Finally, we pass the name of our stylesheet to the `css` parameter.


### Instructions

- Pass null for no `theme`, as we will use the css parameter to add our own styles.
- Set the syntax highlighting style to tango.
- Add our own CSS stylesheet caled `datacamp.css` using the `css` parameter.
- Render the file to admire your DataCamp styled report on the importance of deliberate practice to retain knowledge, and build your data fluency seamlessly.


### Solution code

```
---
title: "Practice makes perfect"
output:
  html_document:
    theme: null
    highlight: tango
    css: datacamp.css
---
```
