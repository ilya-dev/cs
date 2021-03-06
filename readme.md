# Coding style guide for PHP

## Basics

Use at least version `5.4`, however `5.5` is strongly recommended.
Use namespaces to better organize your code. Use short array syntax.
Use all language features to improve the quality of your code.

+ Only use `<?php`, avoid short tags (`<?`), never use closing tag (`?>`)
+ Only use UTF-8 without BOM
+ Never mix declarations (classes, functions) with "side-effect producers"
+ Use consistent naming (PSR-4 is the best)
+ Follow `ClassTraitInterfaceName`, `methodName`, `function_name`, `CONSTANT_NAME`
+ For properties stick with `propertyName`

## More detailed

+ Use 1 tab for indenting
+ Line length limit is 120 characters, I usually go for 100 maximum
+ `<?php namespace Foo;`, no blank line required
+ Opening braces for classes/traits/interfaces go on the same line
+ Opening braces for functions/methods/structures go on the next line
+ Closing braces always go on the next line
+ Always declare visibility, keep the right order (`abstract public static foo()`) 
+ `isset ($bar)` and `if ($foo)` but `foo(42)` and `$baz->bar()` 

