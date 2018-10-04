/*
    Zhongyuan Zheng / zhongyuan_zheng@my.cuesta.edu
    CIS 232 / Scovil
    Assignment 2
*/

#### Overview

For the assigment, we are required to implement our own version of `ArrayList`- one of the most important data structures in Java. In the project, I wrote a generic arraylist named `SortedArrayList` based on the version of Dr Weiss's. As part of the requirement, the list needs to be sorted at all times, modification to `add`, `remove`, and `set` method are made accordingly. Furthormore, in order to find mode of the data set in the list, I implementd an instance method - `getMode`. At last, a static method named `binarySearch` is added to the class to perform a binary search with input SortedArrayList referent and the desired item.
For `add(item)` method, on the basis of the original `add` method, the proper index of the new item is found, the existing elements at the right of the proper index are shifted to right by one index. Lastly, the new item is inserted at the proper index.
For the overloaded version of `add` method, though the desired index to put the item is given, it's not necessarily right if we want the list to be sorted. The logic of expanding the original array and inserting the new item is the same with that of `add(item)`, a direct call to `add(item)` is used.
When it comes to the `getMode` method, since an interface `Result` return type is wanted, the  `ResultOfSAL` (**S**orted**A**rray**L**ist) class is used to implement the `Result` interface, and the logic of finding the mode is encapsulated in the constructor of `ResultOfSAL`. Since the list is already sorted, a time complexity of `O(n)` can be archived. For the implementation, the following variable are used,
+ `lastItem`- the last accessed item
+ `lastCount`- the frequency of `lastItem`
+ `maxItem` - the most ocuuring item
+ `maxCount`-the frequency of `maxItem`

In the `for` loop, `lastItem` is updated to be the current item. Once the current item is different from the old lastItem, `lastCount` is clear to be `1`, otherwise, `lastCount` increases by `1`. By comparing `lastCount` with `maxCount`, we are able to update `maxCount` and `maxItem`. At end of the loop, the `maxCount` is the frequency of the most-occurring item, and the `maxItem` is such item.

##### Question
In the `binarySearch` method, it is instructed to use `AnyType` for the second parameter. I was not able to do so, because the `binarySearch` method is static, it does not allow `AnyType` in the parameter list, as `AnyType` is not staticlly declared. I used `Comparable` for that parameter, and it worked. My question is how do we use the generic type `AnyType` in the static method? Thank you.
