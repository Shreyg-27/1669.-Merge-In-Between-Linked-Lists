# 1669.-Merge-In-Between-Linked-Lists

# Medium 
You are given two linked lists: list1 and list2 of sizes n and m respectively.
Remove list1's nodes from the ath node to the bth node, and put list2 in their place.
The blue edges and nodes in the following figure indicate the result:

![image](https://user-images.githubusercontent.com/98229024/196421291-479af2cc-48b9-4d4d-bfeb-07f27c972026.png)
Build the result list and return its head.

Example 1:
![image](https://user-images.githubusercontent.com/98229024/196421442-640b62be-45c0-4f67-8549-2fcfee39e404.png)

Input: list1 = [0,1,2,3,4,5], a = 3, b = 4, list2 = [1000000,1000001,1000002]
Output: [0,1,2,1000000,1000001,1000002,5]
Explanation: We remove the nodes 3 and 4 and put the entire list2 in their place. The blue edges and nodes in the above figure indicate the result.


Example 2:
![image](https://user-images.githubusercontent.com/98229024/196421562-51e164ac-c25a-41d8-bffa-4aaed62f036b.png)

Input: list1 = [0,1,2,3,4,5,6], a = 2, b = 5, list2 = [1000000,1000001,1000002,1000003,1000004]
Output: [0,1,1000000,1000001,1000002,1000003,1000004,6]
Explanation: The blue edges and nodes in the above figure indicate the result.

# Constraints:
* 3 <= list1.length <= 104
* 1 <= a <= b < list1.length - 1
* 1 <= list2.length <= 104
