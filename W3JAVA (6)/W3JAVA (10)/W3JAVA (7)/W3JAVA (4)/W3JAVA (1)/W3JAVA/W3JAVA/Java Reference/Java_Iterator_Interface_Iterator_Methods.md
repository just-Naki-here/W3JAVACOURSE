# Java Iterator Methods<br>
The Iterator interface provides methods to access and iterate through collections:<br>

| Method    	| Description                                              	| Return Type 	|
|-----------	|----------------------------------------------------------	|-------------	|
| hasNext() 	| Returns true if there are more elements in the iteration 	| boolean     	|
| next()    	| Returns the next element in the iteration                	| _T_         	|
| remove()  	| Removes the last element returned by next()              	| void        	|

**Note:** The next() method uses the type of the iterator's items as its return value. This type is referred to as *T* in the table.

