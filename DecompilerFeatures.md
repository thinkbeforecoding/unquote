Notable decompiler features include
  * Precedence based parenthesization
  * Fully re-sugared multi-variable lambda expressions and applications
  * Sequential expressions
  * Static method calls
  * Module function calls
  * Instance method calls
  * IntrinsicFunction calls
  * Seq, List, and Array range expressions
  * Binary infix operators
  * Unary prefix operators
  * All instance and static property get expressions
  * Instance and static field get expressions
  * All variable, field, and property set expressions
  * Unit and None
  * Generic type test expressions
  * Source names of functions and modules
  * Omission of module qualification for FSI module and AutoOpen modules
  * Excellent F# type name printing, including
    * Precedence parenthesization
    * Non-generic types
    * Arbitrarily complex generic types
    * Known type abbreviations
    * Unit, tuples, functions, and arrays
    * Generic type definitions
    * Definition within Modules or namespaces
  * Detection of whether generic args are inferable
  * if...then...else and && and || short-circuiting boolean expressions
  * Implicit coercion
  * Let bindings
    * Mutable and non-mutable variables
    * Single variable assignment
    * Fully re-sugared tupled variable assignment
    * Recursive functions (including mutually recursive functions)
  * Tuple, array, union case, and object construction
  * Literal list union case construction
  * Basic union case pattern matching
  * While loops and integer for loops
  * try...with and try...finally expressions