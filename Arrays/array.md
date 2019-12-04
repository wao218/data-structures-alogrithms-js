# Arrays
> Data structure that stores items sequentially (in order) in memory. Arrays are good for storing data that is to be iterated over one by one.  
There are static and dynamic arrays. Static arrays have a fixed length. Dynamic arrays grow in size as more data is added to it.   
> #### Methods:
> - Lookup O(1)
> - Push O(1)
> - Insert O(1)
> - Delete O(1)
> #### Pros:
> - Good for storing sorted data
> - Good for fast lookups
> - Fast at adding and deleting from the end of the array
> - Ordered in memory (good for caching)
> #### Cons:
> - Slow at inserting and deleting from the beginning or middle of the array due to the need to traverse and shift all indexes.
> - If using static arrays due to its fixed size you must determine its ahead of time.