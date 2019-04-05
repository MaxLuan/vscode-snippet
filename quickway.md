# Quick way to create vscode template
1. Create the code file of course.
2. Put it in a seperate file.
3. `ctrl` + `f`, 
   1. select `"`, replace as `\"`
   2. toggle regex on
   3. select `^(.+)$`, replace as `"$1",`
   4. toggle regex off
   5. select "double space" (assuming set tab as two spaces), replace as `\t` 
4. Done, copy the finalized code to snippet. 