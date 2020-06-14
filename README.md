# Playing-with-gitignore
a few tests with gitignore
I was just trying to remove the node modules, it turns out that the solution started with removing "node_modules" from the cache with:
## git rm -r --cached "Folder-01/node_modules" "Folder-01/node_modules" "Folder-01/node_modules"
... and then I had to put "**/node_modules/" in the .gitignore file
