
# HTML Cheatsheet

HTML (Hypertext Markup Language) is the standard language for creating web pages. It uses markup tags to structure content on the web. Here's a quick reference for a variety of HTML elements and attributes.

## Basic Structure

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## Headings

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Paragraph

```html
<p>This is a paragraph.</p>
```

## Links

```html
<a href="https://www.example.com">Visit Example</a>
```

## Lists

### Unordered List

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

### Ordered List

```html
<ol>
    <li>First Item</li>
    <li>Second Item</li>
</ol>
```

### Definition List

```html
<dl>
    <dt>Term 1</dt>
    <dd>Definition 1</dd>
    <dt>Term 2</dt>
    <dd>Definition 2</dd>
</dl>
```

## Images

```html
<img src="image.jpg" alt="Description">
```

## Forms

```html
<form action="submit.php" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <input type="submit" value="Submit">
</form>
```

## Divisions

```html
<div>
    <!-- Content goes here -->
</div>
```

## Comments

```html
<!-- This is a comment -->
```

## Tables

```html
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
    <tr>
        <td>Row 2, Cell 1</td>
        <td>Row 2, Cell 2</td>
    </tr>
</table>
```

## Inline Elements

```html
<strong>Bold Text</strong>
<em>Italic Text</em>
<abbr title="Abbreviation">Abbr</abbr>
<code>Code</code>
<mark>Highlighted Text</mark>
<sup>Superscript</sup>
<sub>Subscript</sub>
```

## Special Characters

```html
&copy; &reg; &trade; &lt; &gt; &nbsp;
```

## Line Break

```html
<br>
```

## Horizontal Line

```html
<hr>
```

## Audio

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```

## Video

```html
<video controls width="320" height="240">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>
```

## IFrames

```html
<iframe src="https://www.example.com"></iframe>
```

## Meta Tags

```html
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="description" content="A website description">
<meta http-equiv="refresh" content="5;url=https://www.example.com">
```

## Scripts

```html
<script src="script.js"></script>
```

## Styles

```html
<style>
    /* CSS styles go here */
</style>
```

## Head Elements

```html
<head>
    <title>Document Title</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>
```

## Semantic Elements

```html
<header>
    <!-- Header content -->
</header>
<nav>
    <!-- Navigation content -->
</nav>
<main>
    <!-- Main content -->
</main>
<aside>
    <!-- Sidebar content -->
</aside>
<footer>
    <!-- Footer content -->
</footer>
```

## Document Structure

```html
<article>
    <!-- Article content -->
</article>
<section>
    <!-- Section content -->
</section>
<figure>
    <!-- Figure content -->
    <figcaption>Figure Caption</figcaption>
</figure>
<figcaption>Table Caption</figcaption>
```

## Interactive Elements

```html
<button>Click me</button>
<input type="text" value="Input Field">
<select>
    <option value="option1">Option 1</option>
    <option value="option2">Option 2</option>
</select>
<textarea rows="4" cols="50">Textarea content</textarea>
```

## Canvas

```html
<canvas id="myCanvas" width="200" height="100"></canvas>
```

## Audio and Video

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

<video controls width="320" height="240">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>
```

## Input Types

```html
<input type="text">
<input type="password">
<input type="email">
<input type="number">
<input type="checkbox">
<input type="radio">
<input type="file">
<input type="submit" value="Submit">
<input type="reset" value="Reset">
```

## Form Elements

```html
<form action="submit.php" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" required></textarea><br><br>
    
    <label for="gender">Gender:</label>
    <input type="radio" id="male" name="gender" value="male">
   

 <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br><br>
    
    <label for="interests">Interests:</label>
    <select id="interests" name="interests[]" multiple>
        <option value="programming">Programming</option>
        <option value="design">Design</option>
        <option value="gaming">Gaming</option>
        <option value="music">Music</option>
        <option value="sports">Sports</option>
    </select><br><br>
    
    <input type="checkbox" id="subscribe" name="subscribe" value="yes">
    <label for="subscribe">Subscribe to our newsletter</label><br><br>
    
    <input type="submit" value="Submit">
</form>
```

## Document Metadata

```html
<meta charset="UTF-8">
<meta name="description" content="Website description">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="Author Name">
```

## Additional Resources

- [MDN Web Docs - HTML Basics](https://developer.mozilla.org/en-US/docs/Web/HTML/Introduction)

