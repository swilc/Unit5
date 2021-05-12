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

5.4.4
-
Now I have an issue with the class `quote`, where CodeHS gives me an error in ` Checking class quote has the right font family`, `Checking class quote has the right size`, `and Checking class quote is italicized`. 

Check _style.css_
```
.quote{
    font-style: italic;
    font-family: Arial;
    font-size: 20px;
}
```
against the instructions:

`Then create a CSS rule inside of style.css for quote to make the font Arial, 20px big, and italicized.`

5.4.5
-
There are three errors: `Class red should have the background color red`, `Class header should have the background color LightSkyBlue`, and `Checking class "rectangle" has the right dimensions`.

Compare it against _style.css_:

```
.red{
    background-color:red;
}
.white{
    background-color:white;
}
.blue{
    background-color:blue;
}
.rectangle{
    width:800px;
    height:150px;
}
.header{
    background-color:LightSkyBlue;
}
```
