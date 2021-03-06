| Type         | Description
| ------------- | -----------------------
| number    | numeric data type in the double-precision floating format
| bool  | logical type that can have only true or false
| boolLike  | types convertable to boolean: number and bool
| array | sequence of elements with index access
| arrayLike | object that has indexed access to elements and length property
| object    | collection of user defined properties( key:value pairs) and default properties inherited from Object's prototype
| map   | dictionary type of data collection in which, data is stored in a form of key:value pairs, doesn't have a prototype, usually is used to store options of the routine, example of empty map : ```let map = Object.create( null )```
| objectLike  |
| mapLike   |
| RegExp    | regular expression for matching text
| Range | array-like object with two values : indecies of first and last + 1 element
| Time  | Date object or number and string that are convertable to Date object
| Long  | array, typed array, array-like object
| SortedArray | collection of elements with specific order
| Buffer | container for dealing with raw data
| Raw Buffer | fixed-length raw binary data buffer - ArrayBuffer
| Typed Buffer | array-like object of single type that provides a mechanism for accessing raw buffer, for example : Uint8Array,Float32Array,Int32Array etc.
| Node Buffer | alternative for Typed buffer optimized and suitable for Node.js
| Routine | independent part of code wrapped into function
| Error | runtime exceptions defined by a user
| Consequence | advanced synchronization mechanism based on resources and competitors
| Consequence argument | resolved value, any type except undefined
| Consequence error | rejected value, error object or any type except undefined
| Consequence resource | result of Consequence value computation, there are two kinds of resource: argument and error, only one can be defined at same time
| Consequence competitor | function that handles the resource
...