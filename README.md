## Usage:
```qsub -t <threads> -vf <memory> [-gpu L4] [-p] -i <image> <script.sh>```

please modify image_url.list
## Options:
`-t| -threads| --threads` threads |default: 1

`-vf| -virtual_free| --virtaul_free` memory |default: 4

`-g| -gpu| --gpu` gpu | [L4]

`-p| -parallel| --parallel` parallel

`-i| -image| --image` image |default: miniconda

`-s| -show| --show` show command

`-h | -help | --help` help message
