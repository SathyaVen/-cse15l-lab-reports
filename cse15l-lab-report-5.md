# Lab Report 5
* I searched through the tests with different results manually in order to find the differing outputs
* All expected links are according to common mark
* [Link 548.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/548.md)
* [Link 481.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/481.md)

## Test #1 548.md
* The output for my implmentation is shown below
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.25.43-PM.png)
* The output for the provided implementation is shown below
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.25.58-PM.png)
* The expected output is `/uri`. Both implementations are incorect.
* The bug in my implementation is that the method throws an illegal argument exception when its not supposed to. This happens on line 30, where the value of openParen is -1, and thus the line evaluates. See the image below.
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.44.48-PM_1.png)

## Test #2 481.md
* The output for my implmentation is shown below
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.24.08-PM.png)
* The output for the provided implementation is shown below
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.24.29-PM.png)
* The expected output is again `/uri`. Both implementations are incorect.
* The bug in my implementation is that the method throws an illegal argument exception when its not supposed to. This happens on line 27, where the value of openBracket is -1, and thus the line evaluates. See the image below.
* ![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-31-at-11.35.11-PM_1.png)
