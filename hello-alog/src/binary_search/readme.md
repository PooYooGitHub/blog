# 二分查找法

* 不管题目是什么，只要是用二分法解题的话，模板都是差不多的，只是说边界条件需要额外注意
```text
    int l,j,mid;
    while(l<j){
        if(nums[mid]==target){
            return mid;
        }else if( < ) {
            h
        }else{
            l
                }
        }
```
* 什么时候使用：
  * 被操作的是**已排序**的**数组**
  
* 注意点
  * 如果数组长度较小，那么直接遍历查找更加方便
  
  * 如果数组的顺序不是已经排好的，就不适合再使用二分了，因为一般的排序算法的时间复杂度是
    $$
    O(n\log n)
    $$
    cv 而二分法是
    $$
    O(log n)
    $$
    得不偿失
    
    