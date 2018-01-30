## Naming Schemes

Apparently many people still not understood the importance of using a (somewhat)
consistant naming scheme when naming their files. Just imagine being a student,
downloading 10-20 slides from one of those fancy online course management
platforms and each of them has a different name and is not numbered.

That is annoying. Either I take to time to fix the stuff somebody mesed up, so I
can work on an ordered set of files - or I just try to live whith the chaos.
Obviously I try to fix it. Renaming every file one by one.

Short intercept: If you would have a (somewhat) cosistent naming scheme, people
can make use of a tool or a script to automatically rename the files, but of
corse this is impossible if you do not put at least some effort into chosing
your file names.

### Suggestions - a.k.a. fixing your naming scheme
* Start with either no prefix or a static prefix. If you use a prefix never ever
change it, since it will screw up alphabetical order
* follow with the number of file - in the example of the lecture start with ```01```
and end with ... whatever
  * Please use leading zeros e.g., ```01```, ```02```, ... ```09```, ```10```,
  ```11```, ```12``` - when you display the files in lexicographic order (e.g.,
  opening the folder containing all the slides/files in your file browser) all the
  files will be in the intended order.
  If you do not do this ```1-filename.file```, ```2-filename.file``` and
  ```10-filename.file``` will be compared by first comparing ```1```, ```2``` and
  ```1```. Nothing special happend so far, right? But then ```-``` (hyphen),
  ```-``` (hyphen) and  ```0``` are compared to each other and zero is smaller
  than hyphen, so the files will be ordered
  ```1-filename.file```, ```10-filename.file```,  ```2-filename.file```
  You can avoid all this mess by just putting a leading zero.
  * And even if you do not know the overall amount of file names and therefore do
  not know how many leading zeros you will need: Use an episodic naming scheme
  similar to the one used for TV seriess: ```S01E01``` until ```S01E26``` and
  then easily switch to ```S02E01```. You can use the same schema by replacing
  the season information (```S01```) with the current year or any other prefix.
* Never upload the same file twice but with different file names. The more
similarity in the file names the wore your crime. This is why:
* Oh please, dont use commas, brackets, hashtags or other weird symbols in your
files. Just because you can, does not mean you should. Thaey make it easy to
create file names that look similar, but are not. Also they make it hard to use
tools or script to process your files.
* Decide whether you want to use capital letters or not. But please do not name
one file with a capital at the beginning and the otherones lowercase all the way
through. While this is technically fine it will lead to confusion: Was the thing
in ```filename.file``` or in ```Filename.file```, I can not remember. Oh, it can
get worse. UTF-8 symbols have many different symbols that look alike. For your
computer they are all different file names but for you they all look the same.
So do not do this. It is annoying people (including me, obviously).
* Back to the student example. If you already have an online course management
platform where all the teachers can upload stuff, then you already have a
central enitity where you can enforce consistent naming schemes. Either tool
assistet by just not allowing weird symbols and automatically putting a prefix
with a counter or the date before the filename - or by just forcing your people
with nasty popus like 'Invalid. Your file name must at least include 1 lowercase
letter, 1 number and 1 special character.".
* If you have a lot of different versions going arround, put a version number in
the file name - but append it at the end. Not in the middle and not in the
beginning. First I want to make sure I have the right file and only after that I
can look for the right version. Not the other way around.
* Even if you do not use Windows and therefore not rely on file names ending
with a correct file extension: Use them anyway. It is way easier (and faster)
when people know what they can expect in that file before they open it.
