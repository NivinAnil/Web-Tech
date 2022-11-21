# Pseudo Class Element Selector

- link
- visited : clicked
- active : click or hold
- hover : placing the mouse

## Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      a:link {
        color: forestgreen;
      }
      a:visited {
        color: red;
      }
      a.active {
        border: 30px firebrick;
        border-style: groove;
        background—color: aqua;
        border-radius: 15px;
      }
      a:hover {
        border: 5px hotpink;
        border-style: groove;
        background—color: aqua;
        border-radius: 2.5px;
      }
    </style>
  </head>
  <body>
    <a href="https://www.instagram.com/">Instagram</a>
  </body>
</html>
```

### Output

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>
        a:link{
            color:forestgreen;
        }
        a:visited{
            color:red;
        }
        a.active{
            border:30px firebrick;
            border-style: groove;
            background—color: aqua;
            border-radius: 15px;
        }
        a:hover{
            border:5px hotpink;
            border-style: groove;
            background—color: aqua;
            border-radius: 2.5px;
        }
    </style>
</head>
<body>
    <a href="https://www.instagram.com/">Instagram</a>
</body>
</html>
