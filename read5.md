# CSS

## how to make our web pages more attractive, controlling the design of them using CSS

> CSS allows us to create rules that specify how the content of an element should appear.
> Once you have learned how to write a CSS rule, learning CSS mostly involves learning the different properties you can use. So this chapter will:

- Introduce you to how CSS works .
- Teach you how to write CSS rules .
- Show you how CSS rules apply to HTML pages .

> Example Styles:
- Boxes:
*Width and height Borders (color, width, and style) Background color and images Position in the browser window.*

- Text:
*Typeface Size Color Italics, bold, uppercase, lowercase, small-caps*


## Here we can see a simple web page that is styled using CSS:

> html file
```

<!DOCTYPE html>
 <html>
  <head>
    <title>Introducing CSS</title>
    <link href="css/example.css" type="text/css" rel="stylesheet" />
  </head> 
  <body>
       <h1>From Garden to Plate</h1>
       <p>A <i>potager</i> is a French term for an ornamental vegetable or kitchen garden </p>
       <h2>What to Plant</h2>
       <p>Plants are chosen as much for their functionality as for their color and form </p>
  </body>
 </html>

```

**The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page.**

`href` This specifies the path to the CSS file (which is often placed in a folder called css or styles)

`rel` This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

> External CSS
```

body {
      font-family: Arial, Verdana, sans-serif;
}
h1, h2 {
     color: #ee3e80;
}
p {
     color: #665544;
}

 ```

**You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page.**

> Internal CSS
```

<!DOCTYPE html> 
<html>
 <head>
   <title>Using Internal CSS</title>
    <style>
        body {     
            font-family: arial;     
            background-color: rgb(185,179,175);
        }   
        h1 {     
            color: rgb(255,255,255);
        }  
    </style>
 </head>
 <body>
   <h1>Potatoes</h1>
   <p>There are dozens of different potato varieties. They are usually described as early, second early and maincrop.</p>
 </body>
</html>

 ```

> Color can really bring website pages to life.

**Color**: The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

1. rgb values:
 *These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)*

1. hex Codes:
*These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash* *`#` sign. For example: #ee3e8*

1. Color names:
*There are 147 predefined color names that are recognized by browsers. For example: DarkCya*

```

/* color name */
 h1 {
      color: DarkCyan;
}
/* hex code */
 h2 {
      color: #ee3e80;
}
/* rgb value */
 p {
      color: rgb(100,100,90);
}

```

we can apply *background-color* property.

```

body { 
    background-color: rgb(200,200,200);
}
h1 { 
    background-color: DarkCyan;
}
h2 {
    background-color: #ee3e80;
}
p {
    background-color: white;
}

```