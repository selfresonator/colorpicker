# Make a Color Picker

In this challenge, you'll build a color picker for a web page.

A color picker is a simple UI (User Interface) tool that allows a user to choose from a list of colors. It is used in lots of software where users can select different colors.

For example, say you are designing a blog editor. You will likely want to let users choose the colors of things like their blog header, background, and text. A color picker is a user-friendly way to edit things like this.

In this challenge, we'll start simple and build a web page with a color picker that, when clicked, changes the background color of the page.

**Your task is to build a working version of this color picker with HTML, CSS, and JavaScript.**

Here's an example of what the basic version could look like:

![example color picker gif](http://f.cl.ly/items/3j3D143L101Z471l3Y0A/color-picker.gif)

## Getting Started

1. Fork this gist (click the "Fork" button above; read this [help article](https://help.github.com/articles/forking-and-cloning-gists/) if you need more info)
1. Open your fork in JS Bin (use the "Import Gist" feature of JS Bin, [here's how](https://jsbin.com/help/import-gists))
1. Start working on the first objective

## Submitting your Code

When you are ready to submit your code, share the **link to your fork of the gist**. This link will look something like:

```
https://gist.github.com/your-github-username/lettersandnubmers8123u12
```

Make sure you update your gist with the latest version of your code! You'll need to edit the files in the gist and copy over your code from JS Bin.

## Challenge Objectives

Complete each of the challenge objectives in order.

### 1: Three Primary Colors

To start, our color picker will just use the three primary colors.

Tasks:

- Create three buttons for the primary colors red, blue, and yellow
- Make each button change the background color of the page to the corresponding color

**GOOD NEWS!** This step has already been completed for you. The developer who solved it even recorded [this video for you to watch](https://vimeo.com/learnersguild/color-picker-obj-1) so you can get up-to-speed.

As you watch the video, note things like:

- How they go about learning about the existing code
- What steps they go through to solve the problem
- How they debug their code

<iframe src="https://player.vimeo.com/video/160761687" width="500" height="375" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/160761687">Color Picker: Objective 1</a> from <a href="https://vimeo.com/learnersguild">Learners Guild</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

### 2: The Full Rainbow

3 colors are nice, but not quite enough. It'd be better to have more colors available.

Tasks:

- Create a button for each color of the rainbow
- Make each button change the background color of the page to the corresponding color

_Hint: you can find a list of the CSS color keywords in the [Mozilla Developer Network documentation for CSS][mdn-docs-color]._

### 3: Edit Text Color

Changing the background color is nice, but usually more than just the background can be changed.

To make this page a bit more interesting, let's make it possible for the users to change the color of the text on the page as well.

Tasks:

- Add at least one text element to the page with some sample text (e.g. `<h1>My Page</h1>`)
- Create a new color palette to manage the color of the text
- Make each button in the text color palette change the color of the text on the page to the corresponding color

_Hint: to change the color of text, use the `color` attribute in CSS._

### 4: Choose a Harmonious Palette

The rainbow is a nice range of colors, but it isn't very unique.

It'd be nicer if the colors in the palette were more complimentary - they should look good together, so the text looks nicer on the background.

Tasks:

- Create a new color palette with a set of complimentary colors (there are lots of free options online - just search "color palette generator")
- Replace each button from the old palette with a new button using the complimentary palette

_Hint: you'll likely need to use the hex value of these colors. Learn more about how to use colors in HTML and CSS with [the MDN guide on color][mdn-color-guide]._

### 5: Get Creative

What else can you do to improve the color picker? What other features would you like to build?

Some ideas:

- Let a user enter in a custom color name (e.g. `blueviolet`) to change the color to anything they want
- Use the HTML5 `<input type="color">` element (read the [docs on Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/color) to learn more)
- Let the user click on different page elements (i.e. background, text) to "select" them, and then click on colors to change the color of the _selected_ element
- Refactor your code to use event listening instead of triggering functions from the HTML element with the `onclick` attribute. You might want to read up on [DOM on-event handlers](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Event_handlers).

This objective is intentionally open-ended. Have fun with it!

[mdn-color-guide]: https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Color
[mdn-docs-color]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
