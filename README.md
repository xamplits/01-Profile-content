## Background & Objectives

A simple challenge to manipulate basic HTML tags and create a profile page with headers, text, lists, images and tables.

## Setup 

Jump into your `profile` and create an `images` directory to store all your pictures:


```bash
cd profile
mkdir images
stt
```

## Local server

You can start a local webserver by typing the following command in your terminal (just make sure you are in the exercise's folder):

```bash
serve
```

(it has been defined in an [alias](https://github.com/lewagon/dotfiles/blob/f894306fd81502f1fe513dd253e3129f4b56874d/aliases#L7))

- You can now visit your files on [http://localhost:8000](http://localhost:8000)
- Sometimes, you may have to kill the server with **Ctrl + C** and start it again with `serve`.

## Specs

Build a simple HTML profile page with the following elements (use the right HTML tags):

- an image of yourself
- a header and sub-header with your name and your job title (you can put programmer now 💻)
- a description of yourself
- a list of your social links
- a table showing your projects, favorite movies/programming languages/sport teams/recipes, etc. whatever you want.

A picture is worth a thousand words, [so here is what you should build in this challenge](http://lewagon.github.io/html-css-challenges/01-profile-content/)

## Further suggestions & resources

### Find **good** pictures

Prepare your image files (1 profile picture & 3 movie pictures) before starting to code.

**Always use hi-res images**
**Always use hi-res images**
**Always use hi-res images**

Got it? 😉

Go to [Google Images](https://www.google.com/imghp) and search for what you want. Then, under the menu bar, click on `Tools` ➡️ `Size` ➡️ `Large`. No more pixelation now!

Finally, ensure your **profile image is square** (you can crop it to make it square) and ensure **your movies pictures are all of same width**.

- Don't forget the basic skeleton tags `<html>`, `<body>`, `<head>`.
- Don't forget the page `<title>` in the `<head>` section, and other important metatags like `<meta charset="utf-8">`.
- You can use [Font Awesome](http://fontawesome.io/) to find cool icons (e.g. for social networks). It's a super useful library because all of the icons are **fonts**, making it really easy to resize them, change their color, and even add animations to them!). To import Font Awesome, simply add this link into your `<head>`:

```html
<!-- Fontawesome Stylesheet -->
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
```

- You can use the `target="_blank"` attribute on your links to open them on new tabs once clicked.

## Indent or die

**Take your time to indent your HTML carefully**. HTML code has a lot of nesting - way more than ruby. If you don't indent, it's game over for your code!

Which code is easier to understand?

This one:

```html
<ul>
    <li><a href="#">
        <i class="fa fa-facebook"></i> Facebook
  </a>
</li><li>
  <a href="#">
    <i class="fa fa-linkedin"></i> Linkedin
      </a></li>
<li>  <a href="#">
  <i class="fa fa-twitter"></i> Twitter
    </a>
  </li>
    </ul>
```

Or this one:

```html
<ul>
  <li>
    <a href="#">
      <i class="fa fa-facebook"></i> Facebook
    </a>
  </li>
  <li>
    <a href="#">
      <i class="fa fa-linkedin"></i> Linkedin
    </a>
  </li>
  <li>
    <a href="#">
      <i class="fa fa-twitter"></i> Twitter
    </a>
  </li>
</ul>
```

Indent your HTML! Your code should look like a [V formation of ducks](https://upload.wikimedia.org/wikipedia/commons/0/0b/Eurasian_Cranes_migrating_to_Meyghan_Salt_Lake.jpg) 🦆🦆🦆!
