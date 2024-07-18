To reload the pallete → ctrl+shift+p

Search for reload window to reload the window

02/02/23

To install the pre-commit hook

>pre-commit install

This will install the pre-commit hook in git

17/2/23

Absolute Path vs Relative Path in Python
The absolute path is the full path to some place on your computer. The relative path is the path to some file with respect to your current working directory (PWD)

To import a function from different file in same directory use :arrow_down: 

In file_b.py import function from file_a.py



from file_a import a
The ipython shell and terminal have different settings for processing the paths .

10/03/23

Opening files using the with statement is generally recommended because it ensures that open file descriptor are automatically closed after the flow of execution leaves the with code block.

24/07/23

Check sql conventions 

Understanding Repo Structure
Let's say you need to completely restructure the directories of your codebase. You need to move some folders higher, move some other folders lower, and move lots of files into some new folders you're going to create. You start shifting the code around, checking that everything works, and adding some folders that the next project is going to need. These new folders are empty at the minute.  Wait.... what?

What happened?
Purpose of .gitkeep

git can't push empty directories. It can only track files. Now we know that Git only tracks files, so we know we need to add something to the folder. You can add anything. You just need to add a really simple dummy file to make sure that the folder is tracked, and will be pushed. You could copy and paste a text file file.txt with nothing in it, and that would work. You could put a PNG image of a cat. A common, standardised practice to solve this exact issue, however, is to push a file called .gitkeep into your empty folders.

This isn't a feature of Git! So you could name it anything. There's nothing special about the name .gitkeep – some developers add .gitignore instead, for example.

Conclusion
.gitkeep is a common thing you will see in codebases, where an empty folder needs to be tracked via Git.
