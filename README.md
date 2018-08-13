# cigar_coordinates

## 1 Introduction

`cigar_coordinates` is a tool To get the coordinates of a given CIGAR string. CIGARs are in respect of the reference sequence. By Guanliang MENG, see https://github.com/linzhi2013/cigar_coordinates. 

`cigar_coordinates` understands the following CIGAR characters:

       seq - - - N N N O O O
    refseq - N O N - O O N -
     cigar P n D B u U M N I


## 2 Installation

    pip install cigar_coordinates

There will be a command `cigar_coordinates` created under the same directory as your `pip` command.

## 3 Usage
    
    $ cigar_coordinates
    usage: cigar_coordinates [-h] -c <STR> [-s <INT>] [-q] [-d {+,-}]

    To get the coordinates of a given CIGAR string. By Guanliang MENG, see
    https://github.com/linzhi2013/cigar_coordinates.

    optional arguments:
      -h, --help  show this help message and exit
      -c <STR>    input CIGAR string
      -s <INT>    the start coordinate on the sequence, whatever the gene
                  direction is, this option is always the smaller one. [1]
      -q          the '-s' option is about query sequence, not refseq [True]
      -d {+,-}    the gene direction [+]


## 4 Author
Guanliang MENG

## 5 Citation
Currently I have no plan to publish `cigar_coordinates`.







