Here are examples of various ARIA attributes that can be used to enhance accessibility for people with disabilities:

### 1. ARIA Roles:

#### Example 1: Using ARIA role to indicate a navigation menu
```html
<nav role="navigation">
  <!-- Navigation menu items -->
</nav>
```

#### Example 2: Using ARIA role to indicate a landmark region
```html
<div role="main">
  <!-- Main content of the page -->
</div>
```

### 2. ARIA States:

#### Example 3: Using ARIA `aria-checked` state for a checkbox
```html
<input type="checkbox" aria-checked="true">
```

#### Example 4: Using ARIA `aria-expanded` state for an accordion panel
```html
<button aria-expanded="false" aria-controls="panel1">Expand Panel</button>
<div id="panel1" aria-hidden="true">
  <!-- Content of the accordion panel -->
</div>
```

### 3. ARIA Properties:

#### Example 5: Using ARIA `aria-label` property for a custom button
```html
<div role="button" aria-label="Play">
  <!-- Button content -->
</div>
```

#### Example 6: Using ARIA `aria-describedby` property for additional description
```html
<input type="text" aria-describedby="description">
<div id="description">Additional information about the input field</div>
```

### 4. ARIA Landmarks:

#### Example 7: Using ARIA landmarks for a web page structure
```html
<header role="banner">
  <!-- Header content -->
</header>

<nav role="navigation">
  <!-- Navigation menu -->
</nav>

<main role="main">
  <!-- Main content -->
</main>

<aside role="complementary">
  <!-- Sidebar content -->
</aside>

<footer role="contentinfo">
  <!-- Footer content -->
</footer>
```

These examples demonstrate how ARIA attributes can be utilized to improve accessibility for people with disabilities, providing additional context and functionality to assistive technologies.
