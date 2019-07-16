TLC syntax for Sublime Text 3
=============================

This project aims to provide syntax highlighting for the TLC language.

This syntax file is only compatible with the SublimeText 3 text editor.
Check the correspondig [documentation](https://www.sublimetext.com/docs/3) for
more details about the syntax.


About the language
------------------

The Target Language Compiler (or TLC, for short) is the language used by MATLAB
to convert Simulink models to source code (usually C, but also C++).


The TLC language is not very well documented, but a brief description of the
syntax is available at the following link (a MatLab account is required):

http://www.mathworks.com/help/rtw/tlc/target-language-compiler-directives.html

Alternatively, you can type the following in MatLab's command prompt:

```matlab
web(fullfile(docroot, 'rtw', 'tlc', 'target-language-compiler-directives.html'))
```

If you don't have a Matlab account or a Matlab install, here is a (free) syntax
quick reference from
[mit.edu](https://lost-contact.mit.edu/afs/it.kth.se/misc/packages/matlab/help/toolbox/rtw/tlcquick.html).


How to install
--------------

Drop the `.sublime-syntax` file in SublimeText's `Packages` directory.

This directory can be accessed via the `Preferences > Browse Packages` menu.


License
-------

This project is provided under the [Unlicense](https://unlicense.org/).

Feel free to copy, modify and redistribute it!
