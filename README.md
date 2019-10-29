### 需求：
写一个程序打印1到100之间的数字。

### Tasking
When 数字为3的倍数，Then 打印“Fizz”
When 数字为5的倍数，Then 打印“Buzz”
When 数字既为3的倍数又为5的倍数，Then 打印“FizzBuzz”
When 数字既不是3的倍数又不是5的倍数，Then 打印数字本身。

### Test Cases
Input: 1
Output: 1

Input: 3
Output: Fizz

Input: 5
Output: Buzz

Input: 15
Output: FizzBuzz

### 新增需求
When 数字包含3，Then 打印“Fizz”
When 数字包含5，Then 打印“Buzz”
When 数字既包含3又包含5，Then 打印“FizzBuzz”

### 新增TestCase
Input: 13
Output: Fizz

Input: 52
Output: Buzz

Input: 53
Output: FizzBuzz
