# CASE Eagle Libraries
This is a collection of libraries for the pcb software EAGLE from Autodesk.
This repository is made to maintain and share common components found in the CASE LAB in Chalmers.
Since Eagle doesn't provide a good way of sharing libraries across different accounts this is one of sharing.
The libraries contain symbols, footprints and devices.(No 3D packages yet)

### Installation
To use the libraries do the following:
1. Clone this repository to your EAGLE library folder. (Usually installed in `%HOME%\EAGLE\libraries`.) 
    `git clone https://github.com/caselabbet/case-eagle-libraries`
    You can find this path by opening EAGLE and going in the navigation bar -> `Options`-> `Dictories`-> Click `Browse...`and looking at the folder path.
2. Open EAGLE and goto `Libraries`-> `libraries`-> `case-eagle-library`
3. Enable all libraries by left-clicking the gray dot to the right of name.
4. You are now able to search and use the libraries in your designs.

### Update
To check for updates and update if available do the following:
1. Change directory to where you downloaded the libraries, usually `%HOME%\EAGLE\libraries\case-eagle-library`
    ```sh
    $ cd %HOME%\EAGLE\libraries\case-eagle-library
    $ git pull
    ```
2. If you get `Your branch is up-to-date with 'origin/master'` you are already up to date.

### Contributors
- Viktor Lindström  - Creation of initial libraries
- Isak Åslund - Git setup and documentation (README)
