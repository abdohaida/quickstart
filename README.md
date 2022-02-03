## Prerequisites
This project needs the following tools / services:

    -An HTML5-compliant web browser (Firefox, Chrome, Opera, Safari, Edge, etc.)
    -A free account on GitHub, referenced as <GitHub Handle>
    -A shell terminal with bash, zsh or ksh, including the standard Unix toolset (ls, cd, etc.) with:
    -GNU Make in version 3.81+
    -Git (command line) in version 2+
    -Go Hugo v0.80+
    -The student needs to be able to spawn up a clean Ubuntu 18.04 system. Therefore Docker is recommended with NO prior knowledge.
    -A text editor or IDE (Integrated Development Editor) of your convenience (Visual Code, Notepad++, Vim, Emacs, IntelliJ, etc.)
## Lifecycle
   
    Build: Generate the website from the markdown and configuration files in the directory dist/.
    Clean: Cleanup the content of the directory dist/
    Post: Create a new blog post whose filename and title come from the environment variables POST_TITLE and POST_NAME.


