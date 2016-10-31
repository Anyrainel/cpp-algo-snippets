# C++ Sublime Snippets for Competitive Programming

**Snippet completion system + Code library**, the magic assistant for competitive programming!

This repo contains data structures, algorithms and simple code snippets that could be useful when solving problems. If you happen to find this repo, feel free to leave comments! I would like to know how to make this more useful.

### Contents

Reference list of snippets and their triggers:

> Formatted in `<trigger>`: \<content\> (*\<filename\>.sublime-snippet*)

1. Basic
	- `include`: header, namespace std, very commen macros & typedefs (*head*)
	- `macro`: more useful macros (*macro*)
	- `deftype`: typedefs of STL for shorter names (*typedef*)
	- `main`: main function with `sync_with_stdio` disabled (*main*)
	- `kase`: a loop for printing "Case #: " (*print_case*)
	- `dstream`: ostream `<<` for pair, vector and variable (*debug_ostream*)

2. Graph algorithm
	- `maxfow`: (struct) max flow algorithm (*maxflow*)
	- `costflow`: (struct) min cost max flow algorithm (*mincost_maxflow*)
	- `maxmatch`: (struct) max match Hungarian algorithm (*maxmatch*)
	- `weightmatch`: (struct) max weighted match algorithm (*maxweight_match*)
	- `dinic`: Dinic max flow algorithm (*dinic*)
	- `eulerpath`: Euler path finding algorithm (*eulerpath*)
	- `mincut`: global min cut of undirected graph algorithm (*global_mincut*)

3. Geometry library
	- `geompt`: 2D point struct `PT` with simple calculation and utilities (*geom_point*)
	- `geomrotate`: computation about rotation and angles (*geom_rotate*)
	- `geomline`: computation around points and lines (*geom_line*)
	- `geommore`: computation around circles, polygons and more (*geom_advanced*)
	- `convexhull`: convex hull algorithm (*convex_hull*)

4. String algorithm
	- `kmp`: KMP algorithm (*kmp*)
	- `manacher`: Manacher palindrome algorithm (*manacher*)

5. Miscellaneous
	- `bitfunc`: macro functions involving bit expression (*bit_function*)
	- `rational`: struct `Rat` for rational (fraction) arithmetic (*rational*)
	- `bigint`: struct `bigint` for high precision arithmetic (*bigint*)
	- `orderedset`: declaration of `ordered_set` using pb\_ds (*ordered_set*)

Note that many snippets rely on some basic typdef or basic snippets, but they are very easy to understand with compiler message. There are certainly more algorithms worth adding. I will continue to finish it. I believe now it could serve as a decent helper already. `include` and `main` are used as triggers, and both of the snippets are considered essential to me, be sure to change it if you don't need.

### More words

The idea of embedding codes into snippets comes to me while I was configuring my sublime for competitive programming. This way I think we can save time and focus more on the thoughts in our minds. It may not neccessarily boost your rank, but it is cool! Just imagine the beautiful pieces of code magically show on the screen and helped you indeed. All you have to do is making several keystrokes.

The initiative behind is more personal. I prefer some tricks to boost the workflow while coding for problems, as long as the things introduced are not too difficult to remember. I prefer shorter names and slimmer (but consistent) codes. Also, I would like to adopt some macros that could make a decent (positive) difference comparing to pure C++. I'm a collector of awesome stuffs!

The style I used in the snippets are somehow "mixed". The reason of having such patterns is that they should be:

- short, not demanding time to scroll
- fit for half screen's width (for desktops)
- correct, efficient and trustful
- clear and readable, convenient to check any parameter or protocol
- easy to use, not likely to break the rest code's robustness and readability
- forgettable, not likely to distract us from implementing our thoughts

It is impossible to have a single style that could be the best for every problem. I believe this will also change as I gain more experience.

### Credits

Most of the implementations are from others. I made some minor fixes and style changes. Please refer to:

- [stanford's ACM-ICPC notebook](https://github.com/jaehyunp/stanfordacm)
- [Team Mandrake's template](https://github.com/zhijian-liu/acm-icpc-mandrake)
- [CodeLibrary](http://code-library.herokuapp.com/)

I also looked at many other sources. I choosed the codes that are efficient and easy to understand. Many awesome icpc notebooks cannot be included since they are too simplified for convenience of typing.
