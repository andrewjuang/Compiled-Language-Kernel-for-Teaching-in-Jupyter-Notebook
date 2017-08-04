## Synopsis 
This project was designed in order to make it more feasible for educadors to teach compiled languages through Jupyter Notebook. Jupyter Notebook provides the ability to run code in individual cells and also provide large dividers, titles, pictures and other visual aids in between the code cells using markdown cells. This is ideal for a classroom environment, where markdown cells could be used in order to provide descriptions to break up how an example code functions, provide assignments to be run in a cell (such as "make the for loop for your function here") and also just add visuals to make the notebook more appealing. This can be accomplished easily when utilizing an interpretive language such as python, but when running compiled languages, this separation of each cell as an instance by itself prevents the use of visual aids within the code.


##Running
As this project is still a prototype, sadly I have yet to make the code convenient to run. It still relies on switching kernels in order to work and requires a piece of code to run prior to the execution of the notebook file. In order to run the code, there is a Javascript command written underneath the %%javascript magic command in Python 3. This must be executed after writing a notebook file or making edits. It basically takes only the coding cells within the current notebook file and then appends it to another file which is read by the kernel. After running the Javascript, the kernel file must be changed to "ANewCPPKernelforList" from "Python 3" and the code cells can be run in order to display the final output of the C++ code. This coding language can change from C++ to any other by simply changing the compiler. Another thing to note is that single quotes or "'" cannot be used with my code, as it would break the python I use in the Javascript.

## Installation 
In order to run the code, one must download the kernel file labeled "ANewCPPKernelforList". The reason for such a name is since I worked on multiple prototypes, and this differentiates itself from another kernel similarly named, it can be changed if it is inconvenient. This ipython notebook file would be the kernel to be run in order for my program to work. The next file that has to be downloaded is "AnOriginalJavascriptTestListRelavantComments"