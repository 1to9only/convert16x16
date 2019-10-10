## convert16x16

Converts a 16x16 Sudoku from 0-9A-F, 1-9A-G, 1-16 grid format to the A-P grid format used by Sudoku16Explainer.

```
NAME
  convert - 16x16 Sudoku grid format converter

SYNOPSIS
  convert16x16.exe -f|g|16 [-c] FILE

DESCRIPTION
  Converts a 16x16 Sudoku from 0-9A-F, 1-9A-G, 1-16 grid format
  to the A-P grid format used by Sudoku16Explainer.

OPTIONS
  -f  sudoku grid is in 0-9A-F format.
  -g  sudoku grid is in 1-9A-G format.

  -16 sudoku grid is in 1-16 format.

  -c  (one) sudoku grid is in clipboard.

FILE  input file containing the 16x16 sudoku grid(s).

  -?  displays this help.

INVOCATION
  convert16x16.exe -f  test1.0f > test1.txt
  convert16x16.exe -16 test2.16 > test2.txt
  convert16x16.exe -16 test3.16 > test3.txt
  convert16x16.exe -g  test4.1g > test4.txt
  convert16x16.exe -g  test5.1g > test5.txt

  convert16x16.exe -16 -c > output.txt

  convert16x16.exe -?
```

## Credits

- test1.0f - http://forum.enjoysudoku.com/post6769.html#p6769
- test2.16 - http://forum.enjoysudoku.com/post258131.html#p258131
- test3.16 - http://forum.enjoysudoku.com/blue-s-ultimate-16x16s-t33587.html
- test4.1g - http://forum.enjoysudoku.com/post275765.html#p275765
- test5.1g - the first grid from test4.1g

