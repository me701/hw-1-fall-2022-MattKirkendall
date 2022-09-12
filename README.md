# ME 701 -- Homework 1 -- Matthew Kirkendall

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

One situation that I had to a prolem that was open sorce had to do with my 3d printer.
I wanted to get a bed leveler and when I tried to get it to work I couldnt find a software that worked
that didn't make me pay monthly. Then I found a open sorce verson of the software that someone edited to work with my
exact leveler and I have used it ever since. 

## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

sysctl -n machdep.cpu.brand_string
Intel(R) Core(TM) i5-5250U CPU @ 1.60GHz

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most amount of (1) processing and (2) memory. 
Describe your command(s) in your writeup.
### Solution

I used the "top" command. It gives me all my info about cpu info and Memory info

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

Bash is located in home i got to it using 
cd $Home
I can find the Bash verson using the code
bash --version echo $?
