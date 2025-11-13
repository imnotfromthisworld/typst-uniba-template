# Typst uniba template
This is a thesis template used at the Comenius University in Bratislava.

If you feel adventurous, you may use this template, however, usage is at your
own risk. I am not responsible if you mess up or don't adhere to the specific
university layout requirements. Always check if it fulfills the requirements,
as they may have changed.

The template has been used in english language. Slovak language may need some
more work.

# Usage

Clone the repository and then start editing the `main.typ` file. 
```
$ git clone https://github.com/imnotfromthisworld/typst-uniba-template.git
$ cd typst-uniba-template
```

If something feels off, you may want to edit the `template.typ` which contains
all of the layout settings.

If you find a bug or have an improvement to the template, please open a pull
request.

# Compiling
To compile the document, use:
```
$ typst compile main.typ
````

Instead of manually recompiling the document each time, you may want to have the
typst compiler watch for file modifications with:
```
$ typst watch main.typ
```

# Editing
For better integration of your editor with typst, you may want to use
[tinymist](https://github.com/Myriad-Dreamin/tinymist) language server.
