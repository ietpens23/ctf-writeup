# Bandit - Level 01

## Approach

> The goal of this level is for you to log into the game using SSH. The host to which you need to connect is **bandit.labs.overthewire.org**, on port 2220. The username is **bandit0** and the password is **bandit0**. Once logged in, go to the [Level 1](https://overthewire.org/wargames/bandit/bandit1.html) page to find out how to beat Level 1.

## Explanation

Diberikan sebuah alamat SSH`bandit.labs.overthewire.org` dengan port tertera 2220, serta username __bandit0__ dan password __bandit0__. 

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

![SSH](docs/Level0-1.png)

Setelah menghubungkan menggunakan SSH, terdapat prompt untuk memasukkan password, masukkan **bandit0** lalu enter.
