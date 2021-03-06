# Slightly refurbished BASIC classics

Some classic basic games slightly cleaned up for modern terminals / mobile:

- Improved input, in particular to accept lowercase. Sometimes replacing multiple inputs with improved parsing to make the code more suitable for mobile.
- Output improved to take advantage of unicode, in particular lowercase letters.

The original sources are from http://www.classicbasicgames.org/

The BASIC used is limited to ECMA 55 with the following extensions:

- Multiple statements per line, separated by colon
- Unrestricted variable names
- Any statements allowed after "THEN" 
- Additional string processing functions
  - ASC 
  - CHR$
  - LEFT$
  - LEN
  - MID$
  - RIGHT$

These extensions should mostly match the ones of http://vintage.basic.net and all BASIC programs will still run in the vintage basic interpreter. They should also run with the BASIC interpreter expression parser demo: https://github.com/stefanhaustein/expressionparser
