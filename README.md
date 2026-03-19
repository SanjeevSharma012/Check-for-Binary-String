Check if a String is Binary
📌 Problem Statement

Given a string s, check whether it is a binary string or not.
A binary string contains only characters '0' and '1'.

🚀 Approach

Traverse the string character by character.

If any character is not '0' and not '1', return false.

If all characters are valid, return true.

💻 Code Implementation (Java)
class Solution {
    boolean isBinary(String s) {
        for(int i = 0 ; i < s.length() ; i++){
            if(s.charAt(i) != '0' && s.charAt(i) != '1') return false;
        }
        return true;
    }
}
🧠 Example
Input	Output
"10101"	true
"10201"	false
"0000"	true
⏱️ Complexity Analysis

Time Complexity: O(n)

Space Complexity: O(1)

✍️ Author

Sanjeev Sharma.
