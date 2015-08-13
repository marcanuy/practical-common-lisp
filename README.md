# Practical Common Lisp
Playing around with [Practical Common Lisp](http://www.gigamonkeys.com/book/) book.

# Chapters #

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Table of Contents**

- [Practical Common Lisp](#practical-common-lisp)
- [Chapters](#chapters)
    - [1. Introduction: Why Lisp?](#1-introduction-why-lisp)
    - [2. Lather, Rinse, Repeat: A Tour of the REPL](#2-lather-rinse-repeat-a-tour-of-the-repl)
    - [3. Practical: A Simple Database](#3-practical-a-simple-database)
    - [4. Syntax and Semantics](#4-syntax-and-semantics)
    - [5. Functions](#5-functions)
    - [6. Variables](#6-variables)
    - [7. Macros: Standard Control Constructs](#7-macros-standard-control-constructs)
    - [8. Macros: Defining Your Own](#8-macros-defining-your-own)
    - [9. Practical: Building a Unit Test Framework](#9-practical-building-a-unit-test-framework)
    - [10. Numbers, Characters, and Strings](#10-numbers-characters-and-strings)
    - [11. Collections](#11-collections)
    - [12. They Called It LISP for a Reason: List Processing](#12-they-called-it-lisp-for-a-reason-list-processing)
    - [13. Beyond Lists: Other Uses for Cons Cells](#13-beyond-lists-other-uses-for-cons-cells)
    - [14. Files and File I/O](#14-files-and-file-io)
    - [15. Practical: A Portable Pathname Library](#15-practical-a-portable-pathname-library)
    - [16. Object Reorientation: Generic Functions](#16-object-reorientation-generic-functions)
    - [17. Object Reorientation: Classes](#17-object-reorientation-classes)
    - [18. A Few FORMAT Recipes](#18-a-few-format-recipes)
    - [19. Beyond Exception Handling: Conditions and Restarts](#19-beyond-exception-handling-conditions-and-restarts)
    - [20. The Special Operators](#20-the-special-operators)
    - [21. Programming in the Large: Packages and Symbols](#21-programming-in-the-large-packages-and-symbols)
    - [22. LOOP for Black Belts](#22-loop-for-black-belts)
    - [23. Practical: A Spam Filter](#23-practical-a-spam-filter)
    - [24. Practical: Parsing Binary Files](#24-practical-parsing-binary-files)
    - [25. Practical: An ID3 Parser](#25-practical-an-id3-parser)
    - [26. Practical: Web Programming with AllegroServe](#26-practical-web-programming-with-allegroserve)
    - [27. Practical: An MP3 Database](#27-practical-an-mp3-database)
    - [28. Practical: A Shoutcast Server](#28-practical-a-shoutcast-server)
    - [29. Practical: An MP3 Browser](#29-practical-an-mp3-browser)
    - [30. Practical: An HTML Generation Library, the Interpreter](#30-practical-an-html-generation-library-the-interpreter)
    - [31. Practical: An HTML Generation Library, the Compiler](#31-practical-an-html-generation-library-the-compiler)
    - [32. Conclusion: What's Next?](#32-conclusion-whats-next)

<!-- markdown-toc end -->


## 1. Introduction: Why Lisp? ##

+ LISP stands for LISt Processing
+ It is known as "the programmable programming language"
+ clean map between ideas about how the program works and the code written
+ easy to develop code incrementally and interactively (interactive REPL)
+ Designed by John McCarthy in 1956 for "symbolic data processing", well suited for AI programming
+ Lisp is one of computer science's "classical" languages, based on ideas that have stood the test of time.

## 2. Lather, Rinse, Repeat: A Tour of the REPL ##

+ Common Lisp is defined by its standard (a contract between any Common Lisp vendor and Common Lisp programmers)
  + some things were intentionally left unspecified in order to allow continuing experimentation by implementers
  + .emacs
  ```
  (setq inferior-lisp-program "sbcl")
  (add-to-list 'load-path "~/.slime")
  (require 'slime)
  (slime-setup)
  ```
  + Lisp syntax overview
    + Anything in parentheses is a list
	+ It treats the first element of a list as the function name, and the rest as expressions to be evaluated and pass them as function parameters.
	+ Strings and numbers are self-evaluating objects (when evaluated, they evaluate to themselves)
	+ Basic building blocks:
	  + *functions* are defined with *DEFUN*: `(defun hello-world () (format t "hello, world"))`
	    + (defun <name> (<parameters>) <body>)
		+ (defun name varlist &rest body)
	+ load a file and its definitions:
	  + `(load "~/ch1-hello-world.lisp")`

## 3. Practical: A Simple Database ##

## 4. Syntax and Semantics ##

## 5. Functions ##

## 6. Variables ##

## 7. Macros: Standard Control Constructs ##

## 8. Macros: Defining Your Own ##

## 9. Practical: Building a Unit Test Framework ##

## 10. Numbers, Characters, and Strings ##

## 11. Collections ##

## 12. They Called It LISP for a Reason: List Processing ##

## 13. Beyond Lists: Other Uses for Cons Cells ##

## 14. Files and File I/O ##

## 15. Practical: A Portable Pathname Library ##

## 16. Object Reorientation: Generic Functions ##

## 17. Object Reorientation: Classes ##

## 18. A Few FORMAT Recipes ##

## 19. Beyond Exception Handling: Conditions and Restarts ##

## 20. The Special Operators ##

## 21. Programming in the Large: Packages and Symbols ##

## 22. LOOP for Black Belts ##

## 23. Practical: A Spam Filter ##

## 24. Practical: Parsing Binary Files ##

## 25. Practical: An ID3 Parser ##

## 26. Practical: Web Programming with AllegroServe ##

## 27. Practical: An MP3 Database ##

## 28. Practical: A Shoutcast Server ##

## 29. Practical: An MP3 Browser ##

## 30. Practical: An HTML Generation Library, the Interpreter ##

## 31. Practical: An HTML Generation Library, the Compiler ##

## 32. Conclusion: What's Next? ##

