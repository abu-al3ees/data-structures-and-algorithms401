## Challenge
### Implement a Hashtable with the following methods:

- add: takes in both the key and value. This method should hash the key, and add the key and value pair to the table, handling collisions as needed.
- get: takes in the key and returns the value from the table.
- contains: takes in the key and returns a boolean, indicating if the key exists in the table already.
- hash: takes in an arbitrary key and returns an index in the collection.
Approach & Efficiency
 space O(1)/time O(1)
 
### API


- add(key, value) method: which takes a key and a value as an argument, hashes the key and adding the pair to the table as {key: value} object.
- hash(key) method: which takes a key as an argument, and returns an index in the array within its range based on this key.
- contains(key) method: which takes a key as an argument, and returns true if the key exists, and returns false otherwise.
- get(key) method: which takes a key as an argument, and returns its value if it exists, and returns null if it does'nt.