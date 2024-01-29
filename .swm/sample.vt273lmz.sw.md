---
title: sample
---

&nbsp;

The following script is an basic structure of an html file.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Additional meta tags, CSS links, and scripts can be added here -->
</head>
<body>
    <!-- Content of the HTML document goes here -->
    <header>
        <!-- Header content such as navigation links, logos, etc. -->
    </header>

    <main>
        <!-- Main content of the page -->
    </main>

    <footer>
        <!-- Footer content such as copyright information, contact details, etc. -->
    </footer>
    <!-- Additional scripts or JavaScript can be added before closing the body tag -->
</body>
</html>
```

<SwmSnippet path="/source_code/frontend.html" line="3">

---

This code snippet sets up the basic structure and properties of a web page. It includes the meta tags for character encoding and responsive design, sets the title of the page, and adds a shortcut icon.

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <title>Statcraft</title>
  <link
    rel="shortcut icon"
    href="images/statcraft_icon.ico"
    type="image/x-icon"
  />
</head>
```

---

</SwmSnippet>

<SwmSnippet path="/source_code/frontend.html" line="45">

---

The following External resources are included into the project.

- `bootstrap.min.css` stylesheet from the Bootstrap library.
- `bootstrap.bundle.min.js` script from the Bootstrap library.
- `jquery.min.js` script from the jQuery library.

These resources are used to enhance the styling and interactive functionality of the web page.

These resources packages are downloaded and placed inside the following path.

/path to the resources

```html
<link
  rel="stylesheet"
  type="text/css"
  href="/webjars/bootstrap/5.3.2/css/bootstrap.min.css"
/>
<script src="/webjars/bootstrap/5.3.2/js/bootstrap.bundle.min.js"></script>
<script src="/webjars/jquery/3.7.1/jquery.min.js"></script>
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZG9jdW1lbnRhdGlvbiUzQSUzQXZpbmF5YWtiYW5hdmk=" repo-name="documentation"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
