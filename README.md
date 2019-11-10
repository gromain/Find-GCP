# Find-GCP
Find ArUco markers in digital photos

This small utility can be used together with photogrammetric programs like Open Drone Map to create the necessary Ground Control Point (GCP) file containing image coordinates and projected coordinates of GCPs.

```
usage: gcp_find.py [-h] [-d DICT] [-o OUTPUT] [-i INPUT] [-s SEPARATOR] [-v]
                   [-l]
                   [file_names [file_names ...]]

positional arguments:
  file_names            image files to process

optional arguments:
  -h, --help            show this help message and exit
  -d DICT, --dict DICT  marker dictionary id, default=1 (DICT_4X4_100)
  -o OUTPUT, --output OUTPUT
                        name of output GCP list file, default stdout
  -i INPUT, --input INPUT
                        name of input GCP coordinate file, default None
  -s SEPARATOR, --separator SEPARATOR
                        input file separator, default space
  -v, --verbose         verbose output to stdout
  -l, --list            output dictionary names and ids and exit
```

