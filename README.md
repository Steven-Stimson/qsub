## Usage:
```qsub -t <threads> -vf <memory> [-g 3080Ti] [-p] -i <image> <script.sh>```

## Options:
`-t| -threads`  threads | default: 1

`-vf| -virtual_free`  memory | default: 4

`-g| -gpu`  gpu | [3080Ti | L4]

`-p| -parallel`  parallel

`-i| -image`  image

`-u| -url`  image url

`-s| -show`  show command

`-h | -help`  help message
