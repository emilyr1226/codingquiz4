# codingquiz4
Camel Case: 
The time complexity of camel case would be O(n). First we are initializing a variable, which is constant. Then, we have a for loop which is linear. Within the for loop, we have an if statement that is looking to see when the current character is an Upper Case letter, which is constant. If it is, we increment the variable we initilized in the beginning, which is also constant. Thus, the time complexity is O(n).
The space complexity of camel case would be O(1). This is because we are not using more memory/space than out input space (our string). Thus, it is constant

Correctness and Loop Invariant: 
The time complexity of this would be O(n^2). This is because in insertion sort, we have a for loop, which is linear. Within that for loop, we have a while statement, which is also linear. Since the while statement is within our for-loop, our time complexity of this would be O(n^2). For our other functions, all of the time complexity are O(n), as they have a for loop or for-each loop with constant work. We know that time complexity of n^2 trumps n. Thus, the time xomplexity of the function is O(n^2).
The space complexity of this would be O(1) because we are not using more memory/space than our input space (our array). The program is just doing work on that array. Thus, it is constant.
