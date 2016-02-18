# jCalc 0.4 (06.10.2013)

## This is a simple pocket calculator and it simply does what it says.

A brief overview of the main features:

- Decimal, octal, binary, hexadecimal conversions
- A couple of useful (?) math shortcuts for powers and square root
- Full memory registry use
- AREXX port (see "rexx" directory for info)
- Batch execution through text file input (see "batch" directory for info)

Shortcuts available:
- `SHIFT+B` Convert to binary
- `SHIFT+D` Convert to decimal
- `SHIFT+H` Convert to hexadecimal
- `SHIFT+O` Convert to octal
- `ENTER` = perform the calculation
- `+`, `-`, `*`, `/`, `%` are operators
- `a` to `f` hex numbers
- `p` to type in Pi
- `h` open the "tape" panel (a sheet of paper to remember past operations)
- `s` save tape to disk (optionally as a CSV)
- `DEL` to "Clear All"
- `Backspace`

Feedback and bug reports:
- aros-exec.org (user `jman`)
- mailto: jman at storiepvtride dot it

KNOWN BUGS/LIMITS:
- Due to the actual limit of AROS 32bit build, I cannot allow input of more than 10 figures
- Crashes randomly occur due to the above mentioned limit
- This application eats memory (noticeable when running a batch of calculations): this is likely due to memory leaks outside jcalc.

jCalc icon: courtesy of http://www.iconsea.com
