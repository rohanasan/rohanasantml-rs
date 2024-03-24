# Rohanasantml: An alternative to html

An easy way to write your messy html code in a better way:

```rohanasantml
html

head
    title
        {Rohanasantml}
    title end
head end

body
    div style="color:blue;"
        h1
            {Hello, How are you?}
        h1 end
    div end
body end

html end
```

Compiled:

```ht
<html>
<head>
<title>
Rohanasantml
</title>
</head>
<body>
<div style="color:blue;">
<h1>
Hello, How are you?
</h1>
</div>
</body>
</html>
```

# How to use rohanasantml?
**Run:**
```shell
cargo install rohanasantml
```
### To compile a rohanasantml file to html:

```shell
rohanasantml ./some.rohanasantml ./output.html
```

### Featues:

- Helps code readibility
    - Gives you errors of mistakes that you might have made in your code. Such as:
      - Did you forget to add a } at the end of line 15?
      - Warning: Number of tags starting is greater than the number of tags ending.
      - Warning: Number of tags ending is greater than the number of starting tags.
    - Helps make reliable html



## Checkout
### Rohanasan: An extremely fast backend framework:
https://github.com/rohanasan/rohanasan-rs

### Join discord:
https://discord.gg/Yg2A3mEret

### Todo:
- Add hot reload and a live server
- Add js support
- Add css support

## Contribution:

https://www.buymeacoffee.com/rohanvashisht
