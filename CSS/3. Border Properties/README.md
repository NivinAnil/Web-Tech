# Border Properties

    border: <thickness> <border type> <color>;
    border-top: <thickness> <border type> <color>;
    border-right: <thickness> <border type> <color>;
    border-bottom: <thickness> <border type> <color>;
    border-left: <thickness> <border type> <color>;

### Example

```html
<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .sol{
            border: 2px solid black;
        }
        .dot{
            border: 15px dotted red;
        }
        .rid{
            border: 15px ridge green;
        }
        .groove{
            border: 15px groove red;
        }
        .dashed{
            border: 5px dashed red;
        }.mixed{
            border-top: 15px red;
            border-top-style:solid;
            border—bottom: 10px black;
            border-bottom-style : dashed ;
            border—right:20px double green;
            border—left: 10px dotted blue;
        }
    </style>

  </head>
  <body>
    <h3 class="sol"> Solid  <h3>
    <h3 class="dot"> Dotted  <h3>
    <h3 class="rid"> Ridge  <h3>
    <h3 class="groove"> Groove  <h3>
    <h3 class="dashed"> Dashed  <h3>
    <h3 class="mixed"> Mixed  <h3>
  </body>
</html>
```

### Output :

<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .sol{
            border: 2px solid black;
        }
        .dot{
            border: 15px dotted red;
        }
        .rid{
            border: 15px ridge green;
        }
        .groove{
            border: 15px groove red;
        }
        .dashed{
            border: 5px dashed red;
        }.mixed{
            border-top: 15px red;
            border-top-style:solid;
            border—bottom: 10px black;
            border-bottom-style : dashed ;
            border—right:20px double green;
            border—left: 10px dotted blue;
        }
    </style>

  </head>
  <body>
    <h3 class="sol"> Solid  <h3>
    <h3 class="dot"> Dotted  <h3>
    <h3 class="rid"> Ridge  <h3>
    <h3 class="groove"> Groove  <h3>
    <h3 class="dashed"> Dashed  <h3>
    <h3 class="mixed"> Mixed  <h3>
  </body>
</html>

---

## Border Radius

![](border%20Radius.PNG)

### Example

```html
<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .head{
            border: 10px solid hotpink;
            border-radius: 50px;
        }
        .bottom{
            border: 10px solid hotpink;
            border-bottom-left-radius: 50px;
            border-top-left-radius: 50px;
            border-bottom-right-radius: 10px;
            border-top-right-radius: 10px;
            text-align:center;
        }
    </style>

  </head>
  <body>
    <h3 class="head"> Border Radius  <h3>
    <h3 class="bottom"> Border Radius  <h3>
  </body>
</html>
```

### Output :

<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .head{
            border: 10px solid hotpink;
            border-radius: 50px;
        }
        .bottom{
            border: 10px solid hotpink;
            border-bottom-left-radius: 50px;
            border-top-left-radius: 50px;
            border-bottom-right-radius: 10px;
            border-top-right-radius: 10px;
            text-align:center;
        }
    </style>

  </head>
  <body>
    <h3 class="head"> Border Radius  <h3>
    <h3 class="bottom"> Border Radius  <h3>
  </body>
</html>
