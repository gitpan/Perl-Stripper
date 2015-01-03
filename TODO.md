* TODO [2015-01-03 Sat] plstrip: Option to mangle subroutine names

  With exclude and mangling options (dictionary, name mangler sub).
* TODO [2015-01-03 Sat] plstrip: Option to mangle name of lexical variables

  With exclude and mangling options (dictionary, name mangler sub).
* TODO [2015-01-03 Sat] plstrip: Option to mangle name of global variables

  With exclude and mangling options (dictionary, name mangler sub). And exclude
  Perl's predefined variables like C<@ARGV>, C<%ENV>, and so on.
* TODO [2015-01-03 Sat] plstrip: Option to mangle labels
* TODO [2015-01-03 Sat] plstrip: Option to remove comments and whitespace in /x regexes
* TODO [2015-01-03 Sat] plstrip: Option to remove certain code blocks

  Like:

       if ($DEBUG) { ... }
       if ($PRODUCTION) { ... }
       assert(...)
