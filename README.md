# demo1
This is my first repo
<br>
author - Pranav Patil

## What is Hashing in Data Structures?

**Hashing** is a technique used to store and retrieve data efficiently by mapping data to fixed-size values using a hash function.

### Key Concepts

- **Hash Function**: Converts input data (key) into a fixed-size integer (hash value)
- **Hash Table**: Data structure that stores key-value pairs using hash values as indices
- **Collision**: When two different keys produce the same hash value
- **Time Complexity**: O(1) average case for search, insert, and delete operations

### Example Hash Function

```javascript
function hashFunction(key, tableSize) {
    let hash = 0;
    for (let i = 0; i < key.length; i++) {
        hash += key.charCodeAt(i);
    }
    return hash % tableSize;
}
```

### Common Applications

- Database indexing
- Caching systems
- Password storage
- Hash tables (Maps/Dictionaries)
- Data integrity verification
- Cryptography

### Advantages

- Fast data access (O(1) average)
- Efficient for large datasets
- Simple to implement

### Disadvantages

- Collisions can affect performance
- No natural ordering of elements
- Requires careful hash function design

For more detailed information, see [hashing.html](hashing.html)
