

## A Cyberinfrastructure to Analyze Large-Scale Genome Data

## BoaG: Boa for Genomics

BoaG is a domain-specific language and infrastructure on top of Hadoop for genomics data.
The infrastructure is publicly available here: http://boa.cs.iastate.edu/boag/index.php

#### BoaG example on the infrastructure: 
http://boa.cs.iastate.edu/examples/boag/index.php


### Dataset: Non Redundant (NR) and CD-HIT clustering information
Protobuffer schema and the step by step data generation is shown [here](https://github.com/boalang/NR_Dataset/blob/master/supplemental/Data_Generation.md).


## Interpreting BoaG Output
BoaG can be integrated with jupyter notebook. 
The output can easily be further analyzed with R, Python, Bash, Perl, etc.
The most time-consuming part of the analysis is done via the BoaG infrastructure. 
More examples can be found in the  [jupyter notebooks folder](jupyter_notebooks).

## BoaG Compiler source code
BoaG compiler is written in Java and the source code is available [here](compiler)
* This is a video on step by step instructions to set up programming environment on Eclipse for Boa compiler. [link](https://www.youtube.com/watch?v=s4-xfprwJ0c)


