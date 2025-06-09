## Usage:
```qsub -t <threads> -vf <memory> [-g L4] [-p] -i <image> <script.sh>```

please modify image_url.list
## Options:
`-t| -threads` threads |default: 1

`-vf| -virtual_free` memory |default: 4

`-g| -gpu` gpu | [L4]

`-p| -parallel` parallel

`-i| -image` image |default: miniconda

`-s| -show` show command

`-h | -help` help message
