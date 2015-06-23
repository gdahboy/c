# A better C compiler

## Project Philosophy

- Less is more.
- Gotta go fast.

### Quotes

"There are two ways of constructing a software design: 
One way is to make it so simple that there are obviously no deficiencies
and the other way is to make it so complicated that there are no obvious deficiencies." - C.A.R. Hoare, The 1980 ACM Turing Award Lecture


"One of my most productive days was throwing away 1000 lines of code." - Ken Thompson


## Design choices

- Choose fast algorithms, keep compilation speed and code complexity in mind.
- Die on error. Usually only the first error means anything anyway.
- Few/No warnings. Finding bugs is orthogonal to compiling, use a static checker.

## Style Guidelines

- http://www.lysator.liu.se/c/pikestyle.html
- http://plan9.bell-labs.com/magic/man2html/6/style
- http://aiju.de/b/style

## Useful Links

- C11 standard final draft http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1570.pdf
- Dave Prosser's C Preprocessing Algorithm http://www.spinellis.gr/blog/20060626/
- The x86-64 ABI http://www.x86-64.org/documentation/abi.pdf
- http://aiju.de/rant/cross-compiling
- http://bellard.org/tcc/
- https://github.com/rui314/8cc
