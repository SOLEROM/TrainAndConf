# udimy offline

* git project https://github.com/r0oth3x49/udemy-dl
* get cookie token https://github.com/r0oth3x49/udemy-dl/issues/389#issuecomment-491903900


```
udimyDWoder$ tree -L 1
.
├── AUTHOR.md
├── CHANGELOG.md
├── CONTRIBUTORS.md
├── LICENSE
├── README.md
├── requirements.txt
├── token
├── udemy
└── udemy-dl.py


udimyDWoder$ cat token
access_token=xxxx................xxxx

```


```
udimyDWoder$ python udemy-dl.py https://www.udemy.com/ourse/xxxxxxxxx -k token  -o "/data/xxxxxxxxxxxxxx"

```
