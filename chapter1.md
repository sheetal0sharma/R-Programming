 Introduction to R Programming
R language is an open source program maintained by the R core-development team – team of volunteer developers from across the globe. R language used for performing statistical operations and is available from the R-Project website www.r-project.org. R is a command line driven program. The user enters commands at the prompt (> by default) and each command is executed one at a time.

Many routines have been written for R analytics by people all over the world and made freely available from the R project Website as packages. However, the basic installation (for Linux, Windows, or Mac) contains a powerful set of tools for most purposes.

R is a consolidated environment for performing statistical operations and generating R data analysis reports in graphical or text formats. R commands entered in the console are evaluated and executed. R cannot handle certain auto-formatting characters such as en-dashes or smart quotes; therefore, you need to be careful while copying and pasting commands into R from other applications.

Features of language R
It has effective data handling and storage facilities.
It supports a large pool of operators for performing operations on arrays and matrices.
It has facilities to print the reports for the analysis performed in the form of graphs either on-screen or on hardcopy.
You can obtain the installation files for the R program on the official R Website (www.r-project.org). The website has general documentation related to R along with the libraries of routines. The R program can be simply downloaded and installed from the R Website.

Working with R Scripts
R is utilized as a statistical programming environment for solving problems. R tools can also operate as a general matrix calculation toolbox.

R provides the freedom of selecting and editing tools to interact with the native console. While scripting in R, you don’t need to type commands but rather call functions to achieve results. The RConsole allows command editing.

The developed R scripts can be executed in the selected editor. You could download the data and save them in a local file, or just cut and paste the data from the browser to an editor such as Notepad, and then save them. The prominent editors available for R programming language are:

RGui (R graphical user interface)
Rstudio – Studio R offers a richer editing environment than RGui and makes some common tasks easier and more fun.

R Graphical User Interface (RGui)
Once you download R, RGui is provided as the standard graphical user interface (GUI). Most important component of RGui is the R console window. The console window in R is a place where instructions, scripts, and general R operations are performed. The console window also has R tools to manage the R environment. The R console screen appears every time the RGui is opened. It lists some basic information such as the R version installed and the licensing conditions.

In the RGui window you can open a new script, go to the ‘File’ menu and select ‘New Script’. The RGui can be accessed using the menu shortcuts created during the installation process.

The R prompt, a ‘>’ symbol indicates the place where the user can enter commands. To quit an active R session, you need to type the following code in the console after the command prompt (>):

> q()

R asks a question to ensure that the user wishes to quit the active session.

Note the parentheses after the q; this is because in R you don’t type commands but rather call functions to achieve results, even quit.

RStudio
RStudio is an integrated development environment (IDE) for R language. RStudio is a code editor and development environment, with some nice features that make code development in R easy and fun.

a. Features of RStudio
Code highlighting that gives different colors to keywords and variables, making it easier to read
Automatic bracket matching
Code completion, so as to reduce the effort of typing the commands in full
Easy access to R Help, with additional features for exploring functions and parameters of functions
Easy exploration of variables and values. RStudio is available free of charge for Linux, Windows, and Mac devices. It can be directly accessed by clicking the RStudio icon in the menu system on the desktop.
Because RStudio is available free of charge for Linux, Windows, and Mac devices, it is a good option to use with R. To open RStudio, click the RStudio icon in the menu system or on the desktop.

b. Components of RStudio
i. Source

Top left corner of the screen contains a text editor that lets the user work with source script files. Multiple lines of code can also be entered here. Users can save R script file to disk and perform other tasks on the script.

ii. Console

Bottom left corner is the R console window. The console in RStudio is identical to the console in RGui. All the interactive work of R programming is performed in this window.

iii. Workspace and History

The top right corner is the R workspace and history window. This provides an overview of the workspace, where the variables created in the session along with their values can be inspected. This is also the area where the user can see a history of the commands issued in R.

iv. Files, Plots, Package, and Help

The bottom right corner gives access to the following tools:

R Files: This is where the user can browse folders and files on a computer.

R Plots: This is where R displays the user’s plots.

R Packages: This is where the user can view a list of all the installed packages

R Help: This is where you can browse the built-in Help system of R

R Scripting
Let us start scripting in R.

Let’s create a script to print “Hello world!” in R. To create scripts in R, you need to perform the following steps:

Here in R, you will have to enclose some commands in print() to get the same output as on the command line. So you need to type below command: This takes “Hello World” as input in R.

1
> print (“Hello world!”)
We get the output as:

1
[1] “Hello world!”