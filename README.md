# Compiled page
https://t-fransson.github.io/xest/docs/intro.html

# Some commands

```
$ pip install -U jupyter-book
$ git clone https://github.com/t-fransson/xest.git
$ cd xest/ebook
$ jupyter-book build .
$ open _build/html/index.html
```

**Note**: We need version 0.11 (or higher) to compile our ebook which is not yet available with `conda install` so therefore do `pip install` as suggested above.

# Publish the html-version

```
$ pip install ghp-import
$ ghp-import -n -p -f _build/html
```

# References
The file `references.bib` in the top directory is a regular BIBTEX file. Add your references in this file. A citation in the text is added with

```
{cite}`xesdiag2018, ps2xesxrd2020`
```

Multiple lists of references are possible but not yet propoerly implmented.
