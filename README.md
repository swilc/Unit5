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


5.3.8
-
Error: `The iframe should be 600px tall and 100% wide`

but in _style.css_
```
iframe{
    width:100%;
    height:600px;
}
```

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

5.4.6
-
I get the errors:  `Checking class 'header' has correct styles`, `Checking class "content" has correct styles`, and `Checking class "footer" has correct styles `.

Here is that section in _style.css_
```
.header{
    border-style: solid black 3px;
    background-color:snow;
}
.content{
    background-color:snow;
    height:80%;
    width:70%;
}
.footer{
    background-color:snow;
}
```

5.5.4
-
It says that `Class vocab should have the font color green` and `Class vocab should be "bolder"`.

It is! 

Check _style.css_:

```
.vocab{
    font-weight: bold;
    color: green;
}
```

5.5.5
-
It says that
```
The span should be DarkCyan
The span should be 40 px big
The span should have the font Fantasy 
```

and in _style.css_
```
span {
    color: DarkCyan;
    font-size: 40px;
    font-family:fantasy;
}
```

5.5.6
-
It says that
` Class job-title should be bold`, and that `
Class job-title should be Maroon `

but in _style.css_,
```
.job-title{
    font-weight:bold;
    color:maroon;
}
```
