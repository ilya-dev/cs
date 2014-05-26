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

