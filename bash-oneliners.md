* Comparing 2 text files to get unique values:  
`( cat file1.txt file2.txt ) | sort | uniq -c | awk '$1==1 {print $2}'`
