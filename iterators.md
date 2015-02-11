##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
Select returns a new array for all elements who match a condition specified in the block. literal, string lenght, boolean, etc.

####reject:
Returns a new array with elements that are rejected from the initial array because the block is not true.  This is the opposite of select.

####map:
map iterates over an array and applies the code in the block to each element.  Map does the same action to everything in the array

####detect:
detect returns the first element in the array where the block returns true. Once a true occurs detect stops and does not continue through the array.  If detect never detects what it is looking for it returns nil  

####inject:
similar to reduce but more control. collapses an array into a single value by applying a block or symbol.   

####partition:
returns two arrays, one where the values passed evaluate to true, the other array with the false values.

####sort:
returns a new array that has the same elements as  the original but is sorted in alphabetical order by default. Can be used with a block for comparison sorting.

####one?:
returns true or false.  true only if the block returns true once for the array.  This checks for a unique element in the array. is sonething missing from my list? 

one is also a Metallica song on the ...And Justice For All record/CD. it came out back when they didn't suck.

####none?:
similar to one, none returns true if the block never evaluates to true for the array. 

####all?:
returns true if everything in the array evaluates for true in the block. true if block never returns false.

####empty?:
returns true if no elements in array.  good for checking if data exists or not. did that just work? I dont know, is it #empty?

####eql?:
returns true if the array being passed is the same object.  this is the "==" method

####include?:
return true if the object passed is an element in the array.  does a given array have a value? true/false

####nil?:
returns true only if nil is the object  nil.nil?

###Hash methods:

####key?:
returns true if the key value exists in the hash. 

####keys:
I like this.  returns all the keys from the hash in a new array.  

####delete:
deletes key-value pair based on the key and return the value.  get rid of this, this is the value of what you just got rid of

####delete_if:
deletes any key-value pair that matches the block.

