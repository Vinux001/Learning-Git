Man – scoll through  space command page by page
clear -x – to clear the window but don’t erase the history (ctrl + l – to clear the window)
pwd – give the name of repository

ls – list all the content of folder
ls -a – give the all file including the hidden
ls -l – long format listing
ls -al – all long format listing.
Ls - we can also add the folder name ahead of it.

Cd – don’t have man pages
  cd .. - went back to parent folder
cd ~ - to went to the user directory

/ - refers to root directory
~ - refers to home directory

Two types to paths – Relative and Absolute(powerful, here we mention everything )
home/vin/desktop  -- also similar as ~/desktop

Touch  - we create empty files, extension doesn’t matter at all

rmdir – only deletes the empty directories

rm -  can  delete anything
rm -v – to get a visual of deleting things
rm -r – deletes evrey thing inside a folder (recurssively)
rm -ri – deletes every thing but interactively, by asking us for deletion or not.
Rm -rv – deletes every thing and also show what have been deleted

open . -- means open the current directory
xdg-open . -- same as open .

Mv – to rename the files as well as to move the files
 (by adding the -v, we can see the what has been done)

cp – to copy the file or folder (add -r also with it)
in order to copy any file to some location ->
 cp   file_name   location_where_copy/name_new_copied_file

head – prints the first 10 lines of any file (similarly, works Tail)
head   file__name  -n  number_lines

redirecting standard output -- (>) date > text.txt  => this will over-writing on the files
(>>) -> this will add data on the file.

Cat – used to print all the data of a file on the terminal. 
Also, we can print data of multiple files on  terminal together.
Printing data of more than one file, into one file (>).
cat -n  file__name – to get numbering 

less – better command to list different items of a file.
It opens in a new file, just like the man pages, we can scroll on our pace, even using the space bar. Most importantly, we can find things via  (/find_this_word)
we can even go to start of file via G and of file via g. - q to get out of the terminal

echo – it prints whatever input we give it .
Use echo with >  or  >> is a great way.


Wc – no of lines, no of words, no of bytes, name of the file

piping to give the output of any command to some other command.
Like,      cat	name_file_1 	name_file_2 | wc

sort – it sort alphabhatically
sort -n file__name – it sorts numerically.
 -nr – numerically reversely.
-nu – numerically uniquely.

Sort file__name | uniq  - this will remove all the dulplcate items
sort  -u  file_name – also do the same thing

uniq -u – to print the unique items only
uniq -d – only print the duplicate values
uniq -c – to count how many times a value has been repeated

ctrl + l – to clear the terminal

Now we are at expansions - 
echo ~
echo $PATH
echo $USER
echo * - prints all the files
echo *.pdf – print all the file with extension .pdf
ls -l *.pdf – long list of all files having the extension .pdf
echo *.?? - all the file having extension with exactly 2 characters

diff -
a means added, d means difference, c means changed
-y to compare two files
-u use in GIT

find – it find things reccursively

grep - 

kill -l – it will list all the signals
15 – signal terminate 
9 – signal kill

jobs shows all the stopped processes.
They each have some no or we can say id attached with them.

Gzip – it will compress, but overwrite it.
Gzip -k file__name – it made another file.

Alias – to make a terminal shortcut 
like, ll = ls -l
but, alias only exists for current terminal, in order to make available forever we have to make them in a file

when (|) pipes doesn’t work in that case we can use (| xargs )  {ex. Touch, rm, ls}
xargs – passes the output as argument to other command

su – switch user
we can read files of another user but we can’ t, make or change them.

Ctrl + d – to logout of the user







