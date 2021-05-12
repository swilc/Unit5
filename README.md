# Unit5

5.3.5
-
Here is my code for embedding Wikipedia:

_index.html_
```
<!DOCTYPE html>
<html>
    <head>
        <title>Embedding Wikipedia</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <iframe src="https://wikipedia.org/"></iframe>
    </body>
</html>
```

_style.css_
```
iframe {
    width: 450px;
    height: 350px;
}
```

But CodeHS says there is an error from `Checking the iframe has the correct dimensions`. It works, but it won't grade properly.
