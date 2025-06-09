## Usage:
```qsub -t <threads> -vf <memory> [-gpu L4] [-p] -i <image> <script.sh>```

please modify image_url.list
## Options:
`-t` threads |default: 1

`-vf` memory |default: 4

`-gpu` gpu | [L4]

`-p` parallel

`-i` image |default: miniconda

`-s` show command

`-h | -help | --help` help message
```
