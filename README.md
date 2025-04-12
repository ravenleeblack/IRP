# IRP

The Illeshian Runtime Processor. The IRP takes in a special file called a file manager that has a file ext of .fm. The file manager is used 
to take in all header and source files so that we do not have to call headers in every source file.

We would do something like:
```
use: main.h, lex.h;
link: main.seed, lex.seed;
```

Use is the directive for headers and link is the directive for source files. Its a working process. The IRP will output headers files with a .i
ext and source files with a .p and these files can get ran through the Illeshian compiler named comp. I am still working out the how this is 
going to work. I think right now it brings in the headers on top of the source file during comp stage but its been a  moment.
