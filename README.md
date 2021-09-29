<!-- #region -->
# Compiled page
https://t-fransson.github.io/xest/docs/intro.html

# Notes meeting 28/9

- Contact techtransfer and see if this is relevant
- Involve Roberto (and potentially other beamline people)
- Make it both for synchrotron and XFEL (make it relatively agnostic to source - just need data in the correct format)
- Currently for XES, but can expand...
- Decide on where to put our production versions
- Uncertain on journal (J. Sync. Rad.?)
- Including real (practice) data ok



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
<!-- #endregion -->
