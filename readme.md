# W3 Replication - Practicum01

belajar membuat website menyerupai w3schools
 
## References

```
Cheatsheet untuk markdown:
> https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
```

## Step untuk tambah key ke github
tujuan dari penambahan github key, yaitu agar, kita bisa push ke repository dengan lebih leluasa.
```
step:
1. ssh-keygen -t rsa -b 4096 -C "andrideng@gmail.com"
. mengenerate keygen
. berinama nama file keygen contoh: [4jan23]
. maka akan tergenerate private key dan public key
. public key adalah key yang kita upload di github

2. sesuai di add, next step kita jalankan perintah
eval "$(ssh-agent -s)"

3. ssh-add [keygen][private]
contoh: 4jan23

4. git push ke github

references: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=mac
```
