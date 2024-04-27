  
# Bandit - Level 4-5

## Approach

>The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.
## Explanation

Terdapat sebuah folder bernama **inhere**, di dalamnya berisi file dengan nama **-file00** sampai **-file09**

![image2](docs/3Level4-5-.png)

Kita berasumsi password berada pada salah satu dari file tersebut, gunakan perintah berikut untuk mengecek file satu per satu secara bersamaan

``` bash
file ./-*
```

![image2](docs/2Level4-5-.png)

Hanya satu file yang memiliki tipe **ASCII text** yaitu **-file07**

![images](docs/1.png)

Result: `lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR`
