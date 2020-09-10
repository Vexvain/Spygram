# Spygram
-----------------------------------
An Instagram discovery tool that displays info about an Insta user of your choosing.

-----------------------------------
**YOU MUST BE ROOT**

# Installation
    git clone https://github.com/Vexvain/Spygram
   
    cd Spygram
  
    sudo chmod +x install.sh
 
    sudo bash install.sh
-----------------------------------
# How to Use

    spygram --help

```
usage: spygram [-h] -U USERNAME [--get-posts] [-O OUTPUT]

optional arguments:
  -h, --help            show this help message and exit
  -U USERNAME, --username USERNAME
                        Username to spy [example: --username/-U johndoe]
  --get-posts           Get information on the users posts (MUST BE PUBLIC ACCOUNT)
  -O OUTPUT, --output OUTPUT
                        Output information to file [example: --output/-O username.txt]
```
-----------------------------------
# Examples

    spygram  --username yourusername

```
spygram  --username yourusername  --get-posts
```
-----------------------------------
# Output to File

    spygram  --username yourusername  --get-posts  --output yourusername.txt
