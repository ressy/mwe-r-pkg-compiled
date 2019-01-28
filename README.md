# MWE - R Package with Compiled Code

When things are working, `R CMD check .` should result in
`src/packageexample.so` appearing.

When things are *not* working, the check fails with this in
`.Rcheck/00install.out`:

    * installing *source* package ‘packageexample’ ...
    ** libs
    Error in if (nzchar(SHLIB_LIBADD)) SHLIB_LIBADD else character() : 
      argument is of length zero
