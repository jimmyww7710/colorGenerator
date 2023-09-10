# colorGenerator
a color generator using react.js.

## technologies
* react.js: 4.0.1
* nanoid: 18.2.0
* values: 2.1.1
* vite: 4.1.0

## Setup
To run this project, install it locally using npm:
$ npm install
$ npm start

or see demo on: https://jwclrgenerator.netlify.app/

## Inspiration
I went through the color generator lesson from Udemy course "React 18 Tutorial and Projects Course (2023)" by John Smilga, built this app successfully.

## what I learned from this project
The main target for this project is for building a color generator. There would be set a input for typing color string of hex. after confirming by clicking the submit button. 
app would rerender to display new list of color set relate to tints and shades, base on original color( the original color would be displayed also). 

To achieve that, I add three function components: Form.jsx, ColorList.jsx, and SingleColor.jsx

Those are the purpose of them:
* Form.jsx: put a color inputpicker and input here, decide a color send to App.jsx, and App.jsx will trigger setColor function for updating the list of color set (setColor would be stored as _userState_);

* ColorList.jsx: template for list of color set. import SingleColor component, mapping list with SingleColor, and use nanoid as attribute 'key' put on that.

* SingleColor.jsx: template for card of color displaying value of weight and hex.

Use _Toast_ display state of interaction with app by showing text message. 





