# Requirements
 - Ollama with qwen3:coder30B downloaded and open
 -  All the python packages in the first cell (pydantic, raylibpy, ollama, nltk)

# Instructions
1. Run all the cells top to bottom until the section "Execution"
   1. If you change the order, make sure that the cells that require the content of other cells (those that use the builtin _i* variables) point to the cell above.
2. To execute a prompt:
   1. Run the cell right below "Execution" to reset the system and scene
   2. Write the prompt in the user_query variable and run
   3. Wait for the termination (you need to have Ollama open and the model downloaded)
   4. Scroll below to "Display" and run the cell
3. To continue the conversation:
   1. Press "X" to close the display window
   2. Write the new query in user_query and execute
   3. Run the cell below "Display" again to see the results
