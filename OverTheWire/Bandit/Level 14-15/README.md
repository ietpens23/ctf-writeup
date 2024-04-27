# Bandit - Level 14-15
## Approach

> The password for the next level can be retrieved by submitting the password of the current level to **port 30000 on localhost**.

## Explanation

Dari soal yang diberikan untuk mendapatkan password next level perlu mengirimkan password level ini localhost dengan port 30000, dengan soal yang diberikan dapat digunakan perintah nc seperti berikut

```
echo fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq | nc 127.0.0.1 30000
```

![!image](docs/image.png)

Result: `jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt`
