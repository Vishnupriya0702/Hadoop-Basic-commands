# Hadoop-Basic-commands :  TO check if a directory is present or not: 
Command : if $(hdfs dfs -test -d directory name); then echo 'ok'; else 'not ok'; fi

To check if a target directory exists or not:
Command : if $(hdfs dfs -test -e directory name); then echo 'ok'; else 'not ok'; fi

To check if a file in the directory exists or not:
Command : if $(hdfs dfs -test -f  filename); then echo 'ok'; else 'not ok'; fi

To check if a file or directory is empty or not:
Command : if $(hdfs dfs -test -z  filename); then echo 'ok'; else 'not ok'; fi

TO copy the directory to another directory
Command : hdfs dfs -cp source directory target directory

-getmerge command - to merge multiple input files and put into one single output file.

hdfs fsck /




