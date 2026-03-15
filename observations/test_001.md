# Test 001

Testing github markdown preview for subdirectories.

Generally, github shows README.md's rendered preview in repositories home page.  
But will it work the same way for markdown files in subdirectories?

After careful consideration,
```
e07431d test[1]: reverts 4bc5ead
4bc5ead test[1]: renamed README to index
20e60fd test[1]: added README file
6c3b301 test[1]: testing github's preview for subdirectories
0cd0afc Initial commit
```
and some searching on the internet,  
it is concluded that github infact shows rendered preview of README.md even in subdirectories. Like [this.](./)

*Note:* Remember that github autodetects README file, but it ignores any other markdown files for subdirectory preview.  
It will show their rendered preview when opened (like `repo_link/blob/main/docs/index.md`) but not in subdirectory page (like `repo_link/tree/main/docs`).

