3. `openssl aes-256-cbc -salt -in cpu.py -out cpu.py.enc`
   `openssl aes-256-cbc -d -in cpu.py.enc -out cpu.dec.py`
4.1 `ssh-keygen -t ed25519` 
4.2 `gpg --gen-key`
4.3 `curl https://keybase.io/anish/key.asc | gpg --import\n`
    `gpg --encrypt --sign --armor -r aathalye@mit.edu anish.txt`
4.4 `git commit -S -m "Signed Commit"

