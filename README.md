# programming-language-classifier
Option 1: Get code from the Computer Language Benchmarks Game and downloaded their code directly.

The classifier is able to recognize the following languages:

C (.gcc, .c)
C#
Common Lisp (.sbcl)
Clojure
Java
JavaScript
OCaml
Perl
PHP (.hack, .php)
Python
Ruby (.jruby, .yarv)
Scala
Scheme (.racket)

Using your corpus, you should extract features for your classifier. Use whatever classifier engine that works best for you and that you can explain how it works. Either using an existing Transformer or one you've written.

Write a classifier function that takes a string of code and returns a guess for the language the code was written in. It is recommended you also have a method that returns the snippet's percentage chance for each language in a dict.

Testing your classifier

The test/ directory contains code snippets. The file test.csv contains a list of the file names in the test directory and the language of each snippet. Use this set of snippets to test your classifier.

To see my findings visit this link to the Jupyter Notebook: https://github.com/tarakdavis/programming-language-classifier/blob/master/polyglot.ipynb
