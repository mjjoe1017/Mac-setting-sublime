# Mac-setting-sublime
> Setting sublime on Mac


- Download Sublime
> download path:[https://www.sublimetext.com/](https://www.sublimetext.com/)

<img width="1078" alt="upload sublime image" src="https://user-images.githubusercontent.com/6253685/117557984-66787a80-b0ab-11eb-8b01-58b9e3282318.png">


- install plugin (add Hot Key `alt+v` open browser )
  - Run Sublime Text application software, keydown:「Command + Shift + P」.
  - Click「Package Control」this item.
  - Click「Package Control : Install Package」.
  - Click「Markdown preview」. (Sublime Text will be auto install)
  - Restart Sublime Text, click「Preferences > Key Bindings」.
  - in [] paste 
  ```markdown
    [
      {"keys":["alt+v"], "command":"markdown_preview", "args":{"target":"browser"}}
    ]
  ```
  - save Default(OSX).sublime-keymap-user file.
  - Restart Sublime Text.
 
  - Add helloworld.html file
  
  ```html
    <html>
      <head>
        <title>Example page</title>
      </head>
      <body>
        <h1>Hello world</h1>
      </body>
    </html>
  ```
  - Keydown 「 alt+v 」.
  
  
  

