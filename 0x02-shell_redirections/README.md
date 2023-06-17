this is about shell redirections
echo "Hello, World":prints and followed by a nw line in the standard output
echo "\"(Ôo)'":script that displays a confused smiley
cat /etc/passwd:display the content
cat /etc/passwd /etc/hosts:display the content
tail /etc/passwd:display last 10 lines
head /etc/passwd:display the first ten lines
head -n 3 iacta | tail -n 1:duplicates the last line
echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)":creating a file
ls -la >> ls_cwd_content:a script that writes into another
echo -en "" | tail --lines=1 iacta >> iacta:display the last line
find . -name '*.js' -type f -delete:deletes all regular files
find -mindepth 1 -type d | wc -l:counts number of directories
ls -t1 | head -n 10:displays the 10 newest files in the current directory.
sort | uniq -u:takes a list of words as input and prints only words that appear exactly once.
grep root /etc/passwd:
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f:script that lists all the files with a .gif extension in the current directory and all its sub-directories.
