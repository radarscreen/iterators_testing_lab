##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select: will return an array of the items specified in the block; otherwise, if no block present, will return an enumerator.

####reject: will return an array of the items not specified to be excluded from the resulting array in the block; otherwise, if no block present, will return an enumerator

####map: will return another array after the work specified in the block has been performed on the original array; otherwise, if no block present, will return an enumerator 

####detect/find: will return the first item from an array specified by the block, or will return nil if nothing matches.  

####inject: will combine the values of an array in the manner specified by the block by iterating through the array until all items are combined. It will return the final value. Default initial value is the value of the first item in the array, otherwise can specify. 

####partition: will return a two-dimensional array containing one array in which the elements were considered to be 'true' by the block, and another array where the elements that weren't considered 'true' were grouped.  

####sort: will return an array of strings or integers sorted by the designations of the block. 

####one: will return the boolean true if there is only one item in the array that meets the block's specifications. 

####none?: will return a boolean of whether an array contains the element specified in the block or not. It will return 'true' if none of them meet the criteria, false otherwise.

####all?: returns a boolean: true if none of the elements return a value of nil or false, false otherwise.

####empty?: returns a boolean: true if the array is empty; false otherwise. 

####eql?: returns boolean: true if identical array is compared to the original; false otherwise.

####include?: returns boolean: true if the item specified is in the array, false if it is not. 

####nil?: returns boolean: true if the item is nil (nil.nil?) and false otherwise ("".nil? == false)

###Hash methods:

####key?: returns boolean: true if the hash contains the key specified in the block; false if it doesn't. 

####keys: returns an array of symbols/keys if they are present in the hash as specified by the block. 

####delete: returns the value of the deleted key.

####delete_if: checks if certain values are present in a hash and deletes the key/value pair if it is present, and returns the remainder
