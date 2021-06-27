# Change log for the `gnuplot` Haskell binding

## 0.5.6.2 (fork)

* On Windows 10, changed the executable name from `pgnuplot` to `gnuplot`.
  `pgnuplot.exe` was dropped from gnuplot version 5.0, released in January 2015.

* Added support for gnuplot's `qt` terminal, through module
  `Graphics.Gnuplot.Terminal.Qt`.

## 0.5.5:

 * `Gnuplot.Utility.quote` bugfix:
   Do not escape printable non-ASCII characters
   because gnuplot has no universal escaping support for Unicode codepoints.
