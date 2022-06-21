How do I create a hidden file or folder? How do I display it in the CLI?
How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
How do I append a message to a file, without a newline character, so the output would be:

```
first message
second message
```

1a) 

for folder - $ mkdir .myHiddenFolder 
for file - $ touch .myHiddenFile

1b) ls -a or ls -A

2) mkdir -p testGrandfother/testFather/testChild

3) echo hi > name of file
echo bye >> name of file
cat name of file


