# Useful-eslisp-macros
A collection of macros for [eslisp](https://github.com/anko/eslisp).
###ACHTUNG!
Works for as of now the latest version of elisp which is: 0.7.x

Current macros:
* vlambda, variadic lambdas
* chain, chain methods just like in JS!
* make-lookup, make a lookup table from a list of keys
* ?, ternary if as full-fledged expressions

####Note:
The following obsolete macros had been removed and will be updated for v0.7.x if I feel like it or if I need them in production.
* let, the classic Lisp let for JS
* guard, guards against the undefined error (it's up to you to decide whether it's a good idea or not)
* build, builds a path in an object
* dotguard, guards for deep object members
