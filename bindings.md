# Ada bindings to open source packages

This section provides bindings in Ada for open source software. Typically these were originally developed to as part of a different projectlet eg the gnu scientific library
bindings to support some aspects of signal processing. The bindings are moved to independent repositories and cleaned up ie a uniform naming convention and wherever appropriate
simple examples. Not necessarily complete, particularly in the area of examples, collaboration is invited to make them complete and to continue enhancing as the original library does.

## GNU scientific library gsl Release 2.7

https://gitlab.com/ada23/adagsl.git

This library is also available as an alr crate:

```
alr with gsl
```

## sndfile - library to read/write audio files like .wav

https://gitlab.com/ada23/bindings/adasndfile.git

This uses the adagsl.git as a submodule.

## libflac - library to read/write flac files

https://gitlab.com/ada23/bindings/libflac.git


