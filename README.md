https://golang.org/doc/faq

# golang-faq-notes

## purpose of go: 

- https://talks.golang.org/2012/splash.article : Why they made Go paper.

- the rise of multicore CPUs argued that a language should provide first-class support for some sort of concurrency or parallelism. And to make resource management tractable in a large concurrent program, garbage collection, or at least some sort of safe automatic memory management was required. 

- had become frustrated by the undue complexity required to use the languages we worked with to develop server software. Computers had become enormously quicker since languages such as C, C++ and Java were first developed but the act of programming had not itself advanced nearly as much. Also, it was clear that multiprocessors were becoming universal but most languages offered little help to program them efficiently and safely. 

-  One had to choose either efficient compilation, efficient execution, or ease of programming; all three were not available in the same mainstream language. Programmers who could were choosing ease over safety and efficiency by moving to dynamically typed languages such as Python and JavaScript rather than C++ or, to a lesser extent, Java.

- Go addressed these issues by attempting to combine the ease of programming of an interpreted, dynamically typed language with the efficiency and safety of a statically typed, compiled language. It also aimed to be modern, with support for networked and multicore computing. Finally, working with Go is intended to be fast: it should take at most a few seconds to build a large executable on a single computer. To meet these goals required addressing a number of linguistic issues: an expressive but lightweight type system; concurrency and garbage collection; rigid dependency specification; and so on. These cannot be addressed well by libraries or tools; a new language was called for. 

- more details on this faq: https://talks.golang.org/2012/splash.article

## ancestors of go: 

- some ideas from languages inspired by Tony Hoare's CSP, such as Newsqueak and Limbo (concurrency).

## go at google

Go is not the only language used at Google, far from it, but it is a key language for a number of areas including site reliability engineering (SRE) and large-scale data processing. 
