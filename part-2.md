# Front End Fundamentals

## Using your Browser like a Developer
Developers like to use modern browsers like Chrome, Firefox, and Safari.

Your browser comes with "developer tools" built right in.

* On Chrome `View > Developer > Developer Tools`.
* On Firefox `Tools > Web Developer > Inspector`.
* On Safari `Develop > Show Web Inspector`.

**Exercise**: Visit a website like [https://nytimes.com](https://nytimes.com). Open your inspector, and inspect the HTML on the page. Can you modify the text in the HTML?


## Creating an `.html` file
Developers often use special code editors like [Sublime Text](http://www.sublimetext.com/) and [Atom](https://atom.io/) (both are free).

However, you are welcome to use a simple, lightweight plain-text editor:
    - textEdit
    - notepad

Please create a file named `play.html` (make sure it has a `.html` file extension!).

Now add the following text and save the file:
```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Website</title>
</head>
<body>
  <h1>Hello World</h1>
  <img src="https://media.giphy.com/media/7jNeb9CVSgyUE/giphy.gif">
</body>
</html>
```

Next, open the file in your browser (you may have to right click and say "open in browser").

## Adding Style

Here's an example css rule that turns all the `h1` heading tags the color blue.
```
h1 {
  color: cornflowerblue;
}
```

Adding it to our page will look like this:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Website</title>
  <style type="text/css">
    h1 {
      color: cornflowerblue;
    }
  </style>
</head>
<body>
  <h1>Hello World</h1>
  <img src="https://media.giphy.com/media/7jNeb9CVSgyUE/giphy.gif">
</body>
</html>
```


<img src="http://i.giphy.com/5pxnxdzdZfXFK.gif" width="400px">


## Live Code Link
[todo](#todo)


