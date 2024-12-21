## HashTable -> same implemetation as dictionary you will need to store key and value to check whether there is value you can use dict.keys.contains(). You can imagine the HashTable as buckets with chains, buckets as key and chains as value, and usually it has a hash function by which you distribute your values by keys.

### when making generic operations as "+", "-", "/", "*" etc. use unwrapping cause values of dictionary are going to be optional




###  Avoiding Collisions -> use chaining or either linear or quadratic probing

#### simple hash func dict[x % arr.count] = value