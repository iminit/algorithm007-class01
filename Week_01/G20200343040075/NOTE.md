学习笔记

感触最深的是双指针法的应用，在很多题里都能大大降低时间和空间复杂度

其次，66题的进位的写法很有技巧，耗时才O(1)
````c#
// 新数组元素默认0
int[] digits = new int[digits.Length + 1];
// 进位1
digits[0] = 1;
````