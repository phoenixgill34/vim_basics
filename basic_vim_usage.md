# Basic VIM and Pandoc Usage

# VIM Usage

* Jump forward and land on } character.
```f} ```

* Search for the string in forward direction
```/string```

* Search for the string in backward direction
```?string```

* Move forward with ```n``` and backward with ```N``` between string instances.

* ```j``` move down one line.

* ```k``` move top one line.

* ```O``` move to the beginning of the line.

* ```$``` move to the end of the line.

* ```w``` move forward by one word.

* ```b``` move backward by one word.

* ```)``` move forward by one sentence.

* ```}``` move forward by one paragraph.

* ```H``` move to the top of the screen.

* ```M``` move to the middle of the screen.

* ```L``` move to the bottom of the screen.

* ```g``` go to the top of the file.

* ```G``` go to the bottom of the file.

## Pandoc

* Download the latest .deb or tar file from their github page <https://github.com/jgm/pandoc/releases/tag/2.7.3> and after extraction run the following.
``` sudo mv pandoc /usr/bin ```
* Run the following command to generate aesthetically pleasing PDF using markdown.
```
pandoc -f markdown -t latex --highlight-style=breezeDark --pdf-engine=xelatex documentation_integration.md -s -o output.pdf
```
