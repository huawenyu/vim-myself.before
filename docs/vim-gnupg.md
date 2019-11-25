vim-gnupg

# QuickStart
   gx  open url in browser

# Setup gnupg Evn

https://www.madboa.com/geek/gpg-quickstart/
[doc](https://www.ruanyifeng.com/blog/2013/07/gpg.html)

   //$ yum install gnupg
   $ sudo apt-get install gnupg
   $ gpg --full-generate-key
   $ gpg --recipient "<name> <<email>>" --output demo.gpg --encrypt demo.txt
   $ gpg --decrypt demo.gpg --output demo.de.txt

   // The plugin only work with the file which's extension '.gpg'
   $ vi demo.gpg
