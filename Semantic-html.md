---

## Semantic HTML

Semantic HTML refers to using HTML elements that convey meaning beyond just presentation. It's like using the right tool for the job. By choosing the appropriate HTML elements, we can not only make our code more understandable for other developers but also improve accessibility for users of assistive technologies like screen readers.

### Importance of Semantic Markup

Imagine you're reading a recipe. You'd expect to see headings for the ingredients, steps, and maybe even subsections like "Preparation" and "Cooking." Semantic HTML works the same way. It helps browsers, search engines, and assistive technologies understand the structure and meaning of your content.

### Proper Use of HTML Elements for Accessibility

Let's consider a common scenario: creating a navigation menu. Instead of using `<div>` or `<span>` elements and relying solely on CSS for styling, we can use semantic HTML elements like `<nav>` and `<ul>`:

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

Here, `<nav>` represents a navigation section, and `<ul>` with `<li>` represents an unordered list of navigation links. By using these elements, we provide meaning to the structure of our navigation, making it more accessible and understandable.

### Semantic Structure of a Webpage

A well-structured webpage not only enhances accessibility but also improves SEO (Search Engine Optimization). Let's consider a simple webpage structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <article>
      <h2>About Us</h2>
      <p>Welcome to our website! We provide...</p>
    </article>
  </main>
  <footer>
    <p>&copy; 2024 My Website</p>
  </footer>
</body>
</html>
```

Here, we use semantic elements like `<header>`, `<nav>`, `<main>`, `<article>`, and `<footer>` to structure our webpage. This helps both browsers and assistive technologies understand the organization of our content, making it easier for users to navigate and comprehend.

By embracing semantic HTML, we not only make our code cleaner and more maintainable but also contribute to a more accessible and inclusive web for all users.

---
