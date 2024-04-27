# Bandit - Level 5-6

## Approach

>The password for the next level is stored **somewhere on the server** and has all of the following properties:

- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

## Explanation

Dari soal diatas setelah dipahami terdapat sebuah file 
```
bandit5@bandit:~/inhere$ cat $(find -size 1033c)
```

![!image](./docs/image.png)

Result: `P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU`

