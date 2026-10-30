Assignment 3: Terminal Navigation Practice Sheet
Practice Exercise

Task 1: Create website/ containing index.html, css/style.css, and images/.

cd ~
mkdir website
cd website
mkdir css
mkdir images
New-Item index.html -ItemType File
New-Item css/style.css -ItemType File

Task 2: Go into css, then return to website using cd ...

cd css
cd ..

Task 3: List everything recursively.

ls -Recurse

Task 4: Rename index.html to home.html, then rename it back.

Rename-Item index.html home.html
Rename-Item home.html index.html

Task 5: Open the folder in VS Code.

code .
Conclusion

In this assignment, I practiced terminal navigation, directory creation, file creation, renaming files, listing directory contents, and opening a project folder in VS Code. These commands are useful for managing files and folders during web development.