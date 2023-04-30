1. Line 9 prints "values added: 20"
2. Line 13 prints "final result: 20"
3. Line 9 prints "values added: 20"
4. Line 13 gives a ReferenceError and says "result is not defined." This is because the variable result only exists in the if block because it used 'let' to declare/define the variable, and code in line 13 isn't inside the if block.
5. Line 9 doesn't print anything because line 7 gives an TypeError because const is used to declare/define result and the code tries to change result in line 7 and it isn't allowed to, so it give an error.
6. Line 13 doesn't print anything because the TypeError in line 7 stops the code from getting to that line, but if it did, it would give an error because result is note defined outside the if block, and line 13 is outside the if block.
7. 
