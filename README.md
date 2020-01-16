# myrenv

## OVERVIEW
  This project is the tool for management of R library.
  In this tool, R libraries are divided to each project and managed under home directory.
  This tool enables to make the change to another library easy.

## USAGE
  (preparation: alias to myrenv)
  ```sh
  % myrenv [-init] [-set envname] [-get] [-env] [-pkg] [-dug] [-mkenv envname] [-rmenv envname] [-show]
  ```

  -init : make ~/RProjectLibraries directory to initialize myrenv.
  -set : set new library to ~/.Rprofile instead of old.
  -get : get current library path written in ~/.Rprofile.
  -lib : show library list in ~/RProjectLibraries.
  -pkg : show package list in current library.
  -dug : show size of all packages in current library.
  -mklib : make new library in ~/RProjectLibraries.
  -rmlib : remove the library from ~/RProjectLibraries.
  -show : show ~/.Rprofile.
  -h : show help

## HAVE FUN !!