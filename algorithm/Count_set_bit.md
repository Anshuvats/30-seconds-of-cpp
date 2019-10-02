# __builtin_popcount()

**Description** : There is **NO** __builtin_popcount in c++, it's a **built in function of GCC**.

The function prototype is as follows:
 ```int  __builtin_popcount(unsigned int)```

It returns the numbers of set bits in an integer (the number of ones in the binary representation of the integer).

We can count bits in O(1) time using lookup table.

**Example**:
```cpp
    cout<< __builtin_popcount (4);
```
The above code gives "1" as output.

**Why to use it?**

This function tries to use CPU specific instructions, which will always be orders of magnitude faster than any algorithm you manage to come up with.
