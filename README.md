!/usr/bin/bash
currentdir=$PWD
mkdir Hello
cd Hello
mkdir Five
cd Five
mkdir Six
cd Six
touch c.txt
mkdir Seven
cd Seven
touch error.log
cd ../../../
mkdir one
cd one
touch a.txt b.txt
mkdir Two
cd Two
touch d.txt
mkdir Three
cd Three
touch e.txt
mkdir Four
cd Four
touch access.log
cd ../../../../../
cd Hello
tree
find -name "*.log"
cd Five/Six/Seven
rm error.log
cd ../../../
cd one/Two/Three/Four
rm access.log
cd ../../../../
cd one
echo "unix is family of multitasking, multiuser computer operating systems that derive from the original AT&T unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and Others">> a.txt
cd ../
rm -r Five
mv one uno
cd uno
mv a.txt Tw0
