# Bandit - Level 3-4

## Approach

> The password for the next level is stored in a hidden file in the **inhere** directory.

## Explanation

Dari soal diatas terdapat sebuah file tersembunyi di sebuah folder hidden , ketika masuk di file tersebut dan coba menampilkan file tersembunyi dengan perintah `ls -a` terlihat sebuah file `.hidden` , langsung saja coba melihat file tersebut dengan perintah `cat .hidden`
```
bandit3@bandit:~$ ls -a
bandit3@bandit:~$ cd inhere/
bandit3@bandit:~/inhere$ cat .hidden
```

![!image](./docs/image.png)

Result: `2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe`

