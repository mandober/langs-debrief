# PL Classification criteria



- scripting
- systems programming
- web dev
- markup
- DLS
- General purpose
- orientation
- side-effects
- mutability
- reflexion

## Orientation
- functional
- object-oriented
- aspect-oriented

## Type System
* Type checking (strictness)
  - Statically typed
  - Dynamically typed
untyped



## Categories
Various
commenting
documentation comment
information about the current line and file
tokens
breaking lines (useful when end-of-line and/or indentation has a special meaning)
variable assignment or declaration
grouping expressions
block (grouping statements, especially when statements are not expressions)
use a block as a return value (when statements are not expressions)
equality / inequality
comparison
runtime evaluation
manual memory allocation
force garbage collection
Functions
function call
partial application (in the examples below, a normal call is "f(a,b)")
function definition
anonymous function
function return value
function called when a function is not defined (in dynamic languages)
runtime inspecting the caller information
function composition
identity function
Control Flow
sequence
if_then
if_then_else
ifnot_then (unless)
multiple selection (switch)
loop
breaking control flow
exception
call-with-current-continuation
Types
declaration
annotation (or variable declaration)
cast
mutability, constness
Object Oriented & Reflexivity
method invocation
object creation
object cloning
manually call an object's destructor
class declaration
testing class membership
get the type/class corresponding to an object/instance/value
methods available
inheritance
has the method
current instance
accessing parent method
accessing child method
Package, Module
package scope
declare
import
Strings
type name
character type name
character "z"
strings
multi-line
convert something to a string (see also string interpolation)
serialize (marshalling)
unserialize (un-marshalling)
sprintf-like
simple print
string equality & inequality
string size
string concatenation
duplicate n times
upper / lower case character
uppercase / lowercase / capitalized string
ascii to character
character to ascii
accessing n-th character
extract a substring
locate a substring
locate a substring (starting at the end)
Booleans
type name
false value
true value
logical not
logical or / and
Bags and Lists
type name
list concatenation
list flattening
list constructor
list/array indexing
adding an element at the beginning (list cons)
adding an element at index
adding an element at the end
first element
all but the first element
last element
all but the last element
get the first element and remove it
get the last element and remove it
for each element do something
transform a list (or bag) in another one
transform two lists in parallel
find an element
keep elements
partition a list: elements matching, elements non matching
split a list
is an element in the list
is the predicate true for an element
is the predicate true for every element
smallest / biggest element
join a list of strings in a string using a glue string
list size
iterate with index
remove duplicates
sort
reverse
list of couples from 2 lists
2 lists from a list of couples
lookup an element in a association list
list out of a bag
f(... f(f(init, e1), e2) ..., en)
f(e1, f(e2, ... f(en, init) ...))
Various Data Types
tuple type
tuple constructor
computable tuple (these are a kind of immutable lists playing a special role in parameter passing)
reference (pointer)
optional value
record
union type declaration
enumerated type declaration
dictionary
range
Mathematics
type name
numbers syntax
addition / subtraction / multiplication / division
exponentiation (power)
negation
random
operator priorities and associativities
square root / e-exponential / absolute value
trigonometry
logarithm
euclidean division (both quotient and modulo)
modulo
truncate / round / floor / ceil
bitwise operators
Threads
thread definition
thread creation
thread object creation
starting / stopping threads
passing data directly between threads
terminating thread communication due to a time-out
Thread Synchronization
Joining Another Thread
Thread Prioritization
Thread-safe sharing of data without synchronization
