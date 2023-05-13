# Hall's STATA Toolbox

This is an Index Page for Hall's Stat tools.

1. General initial steps before your stata codings. 👉 [ini.do](/ini.do)
2. Install and update all specified `ssc` and `net` packages at once. 👉 [whichdep.ado](/README_whichdep.md)


# How to install
You can install [`halltool`](https://github.com/LissHall/halltool) using [`github`](https://github.com/haghish/github) in Stata.

```{stata}
    github install LissHall/halltool
```

and uninstall:

```{stata}
    github uninstall halltool
```

If you do not have `github` installed, try run this in your Stata:

```{stata}
    net install github, from("https://haghish.github.io/github/")
```
