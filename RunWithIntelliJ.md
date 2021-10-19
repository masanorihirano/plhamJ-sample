# How to run by java (CUI)

## Before running
Please install IntelliJ.

## How to run
1. Open the repository with IntelliJ
2. Open File > Project Structure
3. Go To "Project" tab and select "Project SDK". You can also add SDK here using SDK adopted by IntelliJ.
   Java 16 and before are recommended.
4. Go to "Module" tab and set `src` folder as "Sources" (blue folder icon)
5. Go to "Library" and click on "+" and select "Java". Then, find and select `plhamj-v1.0.0-jar-with-dependencies.jar`.
6. Close Project Structure window
7. Go to class file you can run, such as `src/CI2002/CI2002Main`.
8. Click green triangle (▶(Run)) on the left of Main, such as CI2002Main
9. Although you can see error message, go to "Edit configurations" by clicking on the CI2002Main in the right-above bar.
10. set your config file, such as `src/CI2002/config.json`, to "Program arguments".
11. Click green triangle (▶(Run)) again
12. you can successfully run the simulator
