# ASGS-Coding-Challenge

Hello! Please see below for instructions on how to run this site locally. :)

There are a ton of ways to run this site locally depending on what kinds of
technology you have access to.

<br />

## 1. File Explorer and Default Browser
Since this is a static site and I made sure to keep all assets in the same directory as index.html, you can simply:
1. Download this repository from github
2. Open its location in your file explorer
3. Double click on the index.html file, and it should open on your default web brower.

For future reference, if there were to be a static site with assets in separate directories, the src paths from index.html to those assets would not work becuase the computer is interpreting those relative paths as absolute paths. So in order for
the static site to run properly, you would have the src paths be absolute paths, which is impractical since the site would only ever run correctly on the machine the code was written on.

## 2. VSCode Live Server
If you have VSCode installed, you can install the live server extention and open the site from there.

1. Download this repository from github
2. Open the repository folder in VSCode
3. Add the "Live Server" extention to VSCode
4. Start a live server by clicking the "go live" button on the bottom toolbar

## 3. Python Simple Http Server
If you have python installed, you can run the site through your computer's terminal (i.e. powershell, command prompt).

1. Download this repository from github
2. Open your terminal (powershell, command prompt)
3. Navigate to where the repository is stored (using the "cd" command)
4. Depending on which version of python you have installed either type:
    - Python v3 and up: `python3 -m http.server`
    - Python v2 and lower: `python -m SimpleHTTPServer`

## 4. Node Local Server
If you have node installed, you can run the site using the npx serve command.

1. Download this repository from github
2. Open your terminal (powershell, command prompt)
3. Navigate to where the repository is stored (using the "cd" command)
4. Type the command `npx http-server`