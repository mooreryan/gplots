# gplots

My personal fork of `gplots`.

## Install

You need the `devtools` R package to install.  If you don't have it, install it first.

```
install.packages("devtools")
```

Now you can install my fork of `gplots`!

```
library(devtools)
install_github("mooreryan/gplots")
```

## What's different?

Currently, just an added function called `heatmap.lala`.  It's just like `heatmap.2` except some option defaults are changed and you can adjust the `lwd` of row and col dendrograms.

### Version number

Version number will be the same as the master version, plus an additional level tacked on to the end to see the changes of this fork from the master.  E.g., currently the version I forked was `3.0.1.1` so the first edit of the fork will be `3.0.1.1.9000` and the next would be `3.0.1.1.9001`.  Might change this if I keep adding stuff.  It's a riff on [this](http://r-pkgs.had.co.nz/description.html#version).
