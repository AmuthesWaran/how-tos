# How to store the output of a linux command to a log file?

The below command will overwrite the log.txt file with output of the echo statement

```echo "Hello" > log.txt```

If incase you want to append the file, use >> as below

```echo "Hello" >> log.txt```

In both cases, log.txt file gets created if it doesn't exists in the working directory.

This works for any linux/gcloud command as well

```ls -ltr >> log.txt```