# treemapproject
Trees are a fundamental data structure used to model all sorts of hierarchical data. 
Often, a tree represents a hierarchical categorization of a base set of data, where the leaves represent the data values themselves, and internal nodes represent groupings of this data. Files on a computer can be viewed this way: regular files (e.g., PDF documents, video files, Python source code) are grouped into folders, which are then grouped into larger folders, etc. Moreover, usually the data values are not all of equal “weight” or “importance.” 
For example, in our file system one of the most important properties of a regular file is its size; certainly not all files have the same size! A treemap is a visualisation technique to show a tree’s structure according to the weights (or sizes) of its data values, using nested rectangles to show subtrees, scaled to different dimensions to reflect the proportional sizes of each piece of data. 
Treemaps are used in many contexts. Among the more popular uses are news headlines, various kinds of financial information, and computer disk usage.

In this project, I wrote 2 key components, a data modeller that takes in some hierarchical data source (such as, but not limited to,
a folder in your computer) and stores it in a tree data structure and an interactive graphical window showing a treemap visualisation of this data to the user.

I implemented recursive operations on trees (both mutating and non-mutating), a geometric tree visualization algorithm called treemap. 
I used inherited to design classes according to a common interface, the os library to write a program that interacts with computer’s file system, 
the pygame library to create an interactive graphical user interface for the program, the PyCharm debugger to inspect the contents of a complex dictionary obtained from JSON data. 
