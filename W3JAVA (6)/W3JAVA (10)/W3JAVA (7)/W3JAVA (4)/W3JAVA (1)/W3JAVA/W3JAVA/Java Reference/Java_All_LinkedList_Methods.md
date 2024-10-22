A list of all LinkedList methods can be found in the table below.

Some methods use the type of the LinkedList's items as a parameter or return value. This type will be referred to as _T_ in the table.
| Method                  	| Description                                                                     	| Return Type   	|
|-------------------------	|---------------------------------------------------------------------------------	|---------------	|
| add()                   	| Add an item to the list                                                         	| boolean\|void 	|
| addAll()                	| Add a collection of items to the list                                           	| boolean       	|
| addFirst()              	| Adds an item to the beginning of the list                                       	| void          	|
| addLast()               	| Adds an item to the end of the list                                             	| void          	|
| clear()                 	| Remove all items from the list                                                  	| void          	|
| clone()                 	| Create a copy of the LinkedList                                                 	| Object        	|
| contains()              	| Checks whether an item exist in the list                                        	| boolean       	|
| descendingIterator()    	| Returns an iterator to loop through the items of the list in reverse order      	| (None)        	|
| element()               	| Retrieves the first item in the list<br>Similar to getFirst()                   	| (None)        	|
| forEach()               	| Perform an action on every item in the list                                     	| void          	|
| get()                   	| Return the item at a specific position in the list                              	| _T_           	|
| getFirst()              	| Returns the first item in the list                                              	| _T_           	|
| getLast()               	| Returns the last item in the list                                               	| _T_           	|
| indexOf()               	| Return the position of the first occurrence of an item in the list              	| int           	|
| isEmpty()               	| Checks whether the list is empty                                                	| boolean       	|
| iterator()              	| Return an Iterator object for the LinkedList                                    	| Iterator      	|
| lastIndexOf()           	| Return the position of the last occurrence of an item in the list               	| int           	|
| listIterator()          	| Return a ListIterator object for the LinkedList                                 	| ListIterator  	|
| offer()                 	| Adds an item at the end of the list                                             	| (None)        	|
| offerFirst()            	| Adds an item at the beginning of the list                                       	| (None)        	|
| offerLast()             	| Adds an item at the end of the list                                             	| (None)        	|
| peek()                  	| Retrieves the first item in the list<br>Similar to getFirst()                   	| (None)        	|
| peekFirst()             	| Retrieves the first item in the list.<br>Similar to peek()                      	| (None)        	|
| peekLast()              	| Retrieves the last item in the list                                             	| (None)        	|
| poll()                  	| Retrieves and removes the first item in the list.                               	| (None)        	|
| pollFirst()             	| Retrieves and removes the first item in the list.<br>Similar to poll()          	| (None)        	|
| pollLast()              	| Retrieves and removes the last item in the list.                                	| (None)        	|
| pop()                   	| Returns the first element in the list.<br>Similar to removeFirst()              	| (None)        	|
| push()                  	| Adds an item to the beginning of the list.<br>Similar to addFirst()             	| (None)        	|
| remove()                	| Remove an item from the list                                                    	| boolean\|_T_  	|
| removeAll()             	| Remove a collection of items from the list                                      	| boolean       	|
| removeFirst()           	| Removes the first item in the list                                              	| _T_           	|
| removeFirstOccurrence() 	| Removes the first occurrence of a specified item in the list                    	| (None)        	|
| removeIf()              	| Remove all items from the list which meet a specified condition                 	| boolean       	|
| removeLast()            	| Removes the last item in the list                                               	| _T_           	|
| removeLastOccurrence()  	| Removes the last occurrence of a specified item in the list                     	| (None)        	|
| replaceAll()            	| Replace each item in the list with the result of an operation on that item      	| void          	|
| retainAll()             	| Remove all elements from the list which do not belong to a specified collection 	| boolean       	|
| set()                   	| Replace an item at a specified position in the list                             	| _T_           	|
| size()                  	| Return the number of items in the list                                          	| int           	|
| sort()                  	| Sort the list                                                                   	| void          	|
| spliterator()           	| Return a Spliterator object for the LinkedList                                  	| Spliterator   	|
| subList()               	| Return a sublist which provides access to a range of this list's items          	| List          	|
| toArray()               	| Return an array containing the list's items                                     	| Object[]      	|