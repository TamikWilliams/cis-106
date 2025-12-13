
    - How to install and remove software using the APT command?
  ## Formula
    -  sudo  apt install package name
  -  you can install/remove multiple programs by adding the package name with a space between each package
  -  You can also remove packages by adding the - sign at the end of the package name
  -  You can add and remove package at the same time by using a +and - at the end of each package
  

  
    - How to create a shell script step by step including screenshots and how to run it. Try to be as detailed as possible.
    - open a text editor 
    - save file as file_name.sh
    - The first line in the file must be shebang or shell interpreter. In the case of bash it would be:
    - #!/bin/bash
    - The rest of the script includes the commands you want the shell to execute when the files is run.
    - To run the script, use the following command:
    - bash /path/to/script/scripts_name.sh
  - ## example on how to run shell script
  - #!/bin/bash 
  - echo then "hello world"