1. `mkdir /tmp/missing`
3. `touch semester`
4. `echo "#\!/bin/sh" > semester`
   `echo "curl --head --silent https://missing.csail.mit.edu" >> semester`
7. `chmod +x semester`
8. `./semester | grep -i "last modified" > last-modified.txt`

