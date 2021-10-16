1. values added: 20
2. final result: 20
3. values added: 20 (not sure if we're expected to test without line 13, if we aren't, the result is same as 4)
4. ReferenceError: result is not defined
   It returns this error because we used 'let' when defining result, which kept its scope to only the if statement.
5. values added: 20 (not sure if we're expected to test without line 13, if we aren't, the result is same as 6)
6. TypeError: Assignment to constant variable.
   It returns this error because we used 'const' when defining result, which means it can't be changed, which we try to do in line 7.
