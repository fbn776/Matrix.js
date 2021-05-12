# Matrix.js
Matrix.js is lightweight js library for using matrices in your js code.
If fast and can be used very easily. And does not depend on any other libraries.


Matrix.js functions are wrapped in a namespace `Matrix`
The matix syntax matrix.js uses, is a very simple and easy to read. You can create a new matix using either the direct method or the `Matrix.create()` method

## Creating matrices

#### The direct method:
The direct method uses an object with 3 properties.
* n 

  Which represents the number of rows
* m 

  Which represents the number of columns
* matrix

  An array that has all the matrix element.

In JavaScript a matrix would look like:

```js
 var A = {
   n:2,
   m:2,
   matrix:[
     1,2,
     3,4
   ]
 }
```

#### The create() method:

This method uses the matrix.js function `Matrix.create(array,n,m)`

This function takes in three arguments, which are:

* array (type:array)

  An array containing all the elements of the matrix

* n (type:number)

  Specifies the number of rows

* m (type:number)

  Specifics the number of columns

In code it would look like:

```js
 var A = Matrix.create([
   1,2,
   3,4
 ],2,2);
 /*
   This return,
   {
     n:2,
     m:2,
     matrix:[
       1,2,
       3,4
     ]
   }
 */
```
For more details read the documentation:
