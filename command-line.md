The command line is a way of interacting with your computer using only your keyboard. For example, if I want to download a program to my computer, normally I would - using my mouse - open my web browser and click around, looking for a website to download it from. Using the command line, I can install the same program by typing in the command - if I know what to tell it.

cd - change directory. A directory is a folder on your computer, like My Documents or My Pictures so 'change directory' is telling the terminal to move to a new folder

ls - list. This tells the command line to show you the files in the current directory. So it would be like opening your My Documents and seeing the files listed in that folder:
CV2016
LING329 Essay1
GERM111 Assignment2
Letter to the Editor NZHerald
And so on so forth. The command line does give a little more information about the files than just their names.

pwd - print working directory. Doesn't actually print anything, not in the usual sense. Your printer isn't going to start spitting out pages of code. It just tells you where you are, in case you lose track of what directory you're working in.

mkdir - make directory. Creates a new directory! Say I have a folder called workspace, and in that folder I have other folders where I keep work relating to html, css, and now I want a folder in which to keep JS-related work. I can do this from the command line by moving into the workspace directory, then giving the command
$ mkdir js-work
js-work is just the name that I'm giving this directory.

git clone - download a repo to your computer. git clone would be followed by the url of the repository, or project, that you want to work on. The whole project and all the files contained within are downloaded so you can work on them on your own machine (locally).

git push - pushes work to GitHub. Like saving something to the cloud. You work on something locally (on your computer), and you want to store it remotely, so you push it up to GitHub where you (or someone else if you've made it public) can pull it from to work on from another computer.

touch - creates a new file. It's like going into a folder, using your mouse to right-click and then scroll down to 'Create New File', but you do it all with your keyboard. For example, to create this file, I used cd to go into my workspace, then into sprint-1, then
$ touch command-line.md
created this file.

cp - copy. Pretty much exactly what it sounds like. Copy [this file] to [there].

grep - search for specific text within a file. Kind of like using ctrl+f to search a page.

exit - closes the shell!
