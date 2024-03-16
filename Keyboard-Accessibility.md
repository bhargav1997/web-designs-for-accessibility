---

## Keyboard Accessibility

Keyboard accessibility ensures that users can navigate and interact with a website using only a keyboard, without relying on a mouse or other pointing device. This is crucial for users with motor disabilities who may have difficulty using a mouse or for those who prefer keyboard navigation for efficiency.

### Navigating a Website Using Only a Keyboard

To ensure keyboard navigation, we need to make sure all interactive elements on our website are accessible via the keyboard. This includes links, buttons, form inputs, and any other actionable items.

#### Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Keyboard Accessibility Example</title>
</head>
<body>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
  <main>
    <h1>Welcome to our Website</h1>
    <button onclick="alert('Button clicked!')">Click Me</button>
  </main>
</body>
</html>
```

In this example, users can navigate between the links in the navigation menu using the Tab key. They can also interact with the "Click Me" button using the Enter or Space keys.

### Focus Management and Tabindex

Focus management ensures that keyboard users can easily see which element on the page currently has keyboard focus. By default, browsers handle focus management, but we can enhance it using the `tabindex` attribute.

#### Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Focus Management Example</title>
</head>
<body>
  <button tabindex="1">First Button</button>
  <button tabindex="2">Second Button</button>
  <button tabindex="3">Third Button</button>
</body>
</html>
```

In this example, the `tabindex` attribute specifies the order in which elements should receive focus when navigating with the Tab key. Users can press Tab to move between the buttons in the specified order.

### Handling Keyboard Events for Interactive Elements

Interactive elements like buttons often require additional keyboard event handling to ensure a seamless user experience. We can use JavaScript to handle keyboard events such as key presses and releases.

#### Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Keyboard Event Handling Example</title>
</head>
<body>
  <button id="myButton">Press Me</button>

  <script>
    const button = document.getElementById('myButton');

    button.addEventListener('keydown', function(event) {
      if (event.key === 'Enter' || event.key === ' ') {
        alert('Button clicked!');
      }
    });
  </script>
</body>
</html>
```

In this example, pressing the Enter key or the Space key while the button is focused triggers a JavaScript function to display an alert.

By implementing keyboard accessibility techniques like these, we can ensure that our websites are usable and accessible to all users, regardless of their input method or abilities.

---
