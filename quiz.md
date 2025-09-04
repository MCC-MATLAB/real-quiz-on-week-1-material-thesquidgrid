# MATLAB Quiz - Week 1 Material

### Instructions
- Read each question carefully.
- Edit _this_ file right in GitHub, check the box next to the correct answer by placing an `x` inside the brackets.
- After completing the quiz, commit your changes.

### Questions

1. What does the command `clear` do in MATLAB?
    - [ ] a) Clears the Command Window.
    - [ ] b) Clears the current figure.
    - [x] c) Clears variables from the workspace.
    - [ ] d) Clears the command history.


2. How would you display the size and type of all variables currently in the workspace?
    - [ ] a) `size`
    - [x] b) `whos`
    - [ ] c) `who`
    - [ ] d) `vars`


3. In a script, which symbol do you use to suppress the output of a line (i.e., prevent MATLAB from automatically printing the result)?
   - [ ] a) `:`   (colon)
   - [x] b) `;`   (semicolon)
   - [ ] c) `#`   (hash)
   - [ ] d) `...` (ellipsis)


4. You type the following in the Command Window:

   ```matlab
   radius = 6;
   height = 12;
   volume = (pi * radius^2 * height) / 3
   ```
 
    - [ ] a) `matlab cone_volume.m`
    - [ ] b) `run cone_volume.m`
    - [x] c) `cone_volume`
    - [ ] d) `execute cone_volume`


5. Which command(s) would you typically place at the start of an M-file to ensure a fresh environment and a clean Command Window?
    - [ ] a) `start; wipe;`
    - [ ] b) `reset; clearvars;`
    - [x] c) `clear; clc;`
    - [ ] d) `delete; close;`


6. Which of the following commands allows you to read about MATLAB’s built-in function sin in the Command Window?
    - [ ] a) `syntax sin`
    - [ ] b) `info sin`
    - [x] c) `help sin`
    - [ ] d) `read sin`


7. You want to print the text “Calculation done!” without any numeric variables. Which code snippet properly uses `disp`?
   - [ ] a) `disp(Calculation done!)`
   - [x] b) `disp('Calculation done!')`
   - [ ] c) `disp("Calculation done!", " ")`
   - [ ] d) `disp("Calculation done!"); disp()`


8. Suppose you have the following code in a script:
   ```matlab
    clc
    clear

    height = 5;
    width = 10
    area = height * width;
    disp(['Area is ', num2str(area)])
   ```

   - [ ] a) MATLAB errors out because width is missing a semicolon.
   - [ ] b) The workspace is cleared, the Command Window is cleared, variables height and width are created, and the area is displayed.
   - [ ] c) MATLAB shows only the value of height.
   - [x] d) MATLAB does nothing because disp cannot handle numbers.


9. Which MATLAB command immediately stops the execution of a script or function if it’s stuck in a loop?
   - [ ] a) `ctrl + c`
   - [ ] b) `exit`
   - [ ] c) `cancel`
   - [ ] d) `stop`


10. Which of the following statements about MATLAB scripts (M-files) is incorrect?
    - [ ] a) A script is a file containing a sequence of MATLAB commands and statements.
    - [ ] b) A script can store variables in the workspace without explicitly returning them.
    - [ ] c) A script must define input and output arguments in its first line.
    - [ ] d) A script runs in the current workspace, using any existing variables unless they are cleared.
