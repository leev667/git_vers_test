#This is a test for version control and different commits, commit 1
# This is an edit on Github not local
# This is a test for version control, commit 2
# 3rd commit on UI
#4th commit on local
#5th commit to new July15 Branch
#New Feature Branch
#New Feature 2 Branch

Adding a Large amount of text and code to test merges

FS='/';NUMRESULTS=20;resize;clear;date;df -h $FS; echo "Largest Directories:";\du -x $FS 2>/dev/null| sort -rnk1| head -n $NUMRESULTS| awk '{printf "%d MB %s\n",\
$1/1024,$2}';echo "Largest Files:"; nice -n 19 find $FS -mount -type f -ls \
2>/dev/null| sort -rnk7| head -n $NUMRESULTS|awk '{printf "%d MB\t%s\n",\
($7/1024)/1024,$NF}'

