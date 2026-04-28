1. values added: 20
2. final redult: 20
3. You should not use *var* as a variable declared in a block in a function, can be used outside of that block within the function, potentially causing errors. In this case, if *add* is false, *var results* is never declared, causing an error with line 13.
4. values added: 20
5. The code returns an error since *let results* is declared in the if block, making that variable not accessible from outside the block.
6. values added: 0
7. The code returns an error since *const results* is declared in the if block, making that variable not accessible from outside the block.