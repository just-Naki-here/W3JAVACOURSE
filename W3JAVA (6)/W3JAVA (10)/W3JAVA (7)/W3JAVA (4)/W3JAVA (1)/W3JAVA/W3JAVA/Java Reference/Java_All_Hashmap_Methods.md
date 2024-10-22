A list of all HashMap methods can be found in the table below.

Some methods use the type of the HashMap's entries as a parameter or return value. The type of the key will be referred to as _K_ and the type of the value will be referred to as _V_ in the table.
| Method             	| Description                                                                                                          	| Return Type               	|
|--------------------	|----------------------------------------------------------------------------------------------------------------------	|---------------------------	|
| clear()            	| Remove all entries from the map.                                                                                     	| void                      	|
| clone()            	| Create a copy of the HashMap.                                                                                        	| Object                    	|
| compute()          	| Compute a value for an entry based on its key and the current value (if it has one)                                  	| _V_                       	|
| computeIfAbsent()  	| Compute a value for an entry based on its key only if an entry using the key does not already exist                  	| _V_                       	|
| computeIfPresent() 	| Compute a new value for an entry based on its key and current value but only if an entry with the key already exists 	| _V_                       	|
| containsKey()      	| Indicate if an entry with the specified key exists in the map                                                        	| boolean                   	|
| containsValue()    	| Indicate if an entry with the specified value exists in the map                                                      	| boolean                   	|
| entrySet()         	| Return a set of all entries in the map                                                                               	| Set< Map.Entry<_K_,_V_> > 	|
| forEach()          	| Perform an action on every entry in the map                                                                          	| void                      	|
| get()              	| Return the value of the entry with a specified key                                                                   	| _V_                       	|
| getOrDefault()     	| Return the value of the entry with a specified key or a default value if the entry is not found                      	| _V_                       	|
| isEmpty()          	| Indicate whether the map is empty                                                                                    	| boolean                   	|
| keySet()           	| Return a set of all keys in the map                                                                                  	| Set<_K_>                  	|
| merge()            	| Compute a value for an entry based on its key and value or write a specific value if the entry does not yet exist    	| _V_                       	|
| put()              	| Write an entry into the map                                                                                          	| _V_                       	|
| putAll()           	| Write all of the entries from another map into this one                                                              	| void                      	|
| putIfAbsent()      	| Write an entry into the map but only if an entry with the same key does not already exist                            	| _V_                       	|
| remove()           	| Remove an entry from the map                                                                                         	| _V_\|boolean              	|
| replace()          	| Write to an entry in the map only if it exists                                                                       	| _V_\|boolean              	|
| replaceAll()       	| Replaces the value of every entry with the result of an operation                                                    	| void                      	|
| size()             	| Return the number of entries in the map                                                                              	| int                       	|
| values()           	| Return a collection containing all of the values in the map                                                          	| Collection<_V_>           	|