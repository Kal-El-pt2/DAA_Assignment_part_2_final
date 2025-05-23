# 1.Execution instruction

Downloading and Extracting the files :

    - Download the repo 

"DAA_Assignment_part2" from 

https://github.com/Kal-El-pt2/DAA_Assignment_part_2_final

    - Extract the zip file "DAA_Assignment_part2.zip" .

OR

If git is installed run the following in terminal :

    git clone https://github.com/Kal-El-pt2/DAA_Assignment_part_2_final.git

make sure you've the following files :

    Algo_1.cpp
    Algo1_gml.cpp
    Algo_4.cpp
    Algo4_gml.cpp
	and download these datasets (explained below)
    as-733
    as-caida
    ca-hepth
    netscience
    yeast

Ensure that you have a working C++ compiler (like g++).


Compilation :

Before compiling, make sure you are running the correct code file depending on the dataset:

For .txt datasets (As-733, As-Caida, Ca-HepTh, Yeast):

    g++ -O2 -std=c++17 Algo_1.cpp -o algo1
    g++ -O2 -std=c++17 Algo_4.cpp -o algo4


For netscience (GML format):

    g++ -O2 -std=c++17 Algo1_gml.cpp -o algo1_gml
    g++ -O2 -std=c++17 Algo4_gml.cpp -o algo4_gml

Executing the Files:

    ./algo1.exe  -all   <folderName>   # for as733.txt, as-caida.txt, ca-hepth.txt, yeast
    ./algo4.exe  -all   <folderName> <H>
	ex : ./algo1.exe -all As-733 3  (for 3 H-Cliques)
    ./algo1_gml.exe -all <folderName>   # for netscience
    ./algo4_gml.exe -all <folderName> <H>
 

Results (Output Files + Report):
https://drive.google.com/drive/folders/10T8kRRK-CSzIELPiCv45E3FR_LGpdh0x?usp=sharing

# 2.Dataset Preparation :

DATASET LINKS : 

https://snap.stanford.edu/data/as-733.html
https://snap.stanford.edu/data/as-Caida.html
https://dip.doe-mbi.ucla.edu/dip/Stat.cgi 
http://www.personal.umich.edu/ ̃mejn/netdata/

# 3. Individual Contributions

The process of exploring and implementing the CDS algorithms was both challenging and rewarding.

We: Dhairya, Aariv, Saumya, Animish, and Shreejeet worked together to successfully implement and test these papers.

Dhairya (2022A7PS1377H) and Shreejeet (2022A7PS0036H):

    Studied and implemented the Exact algorithm (Algorithm 1).
    
    Wrote Algo_1.cpp and Algo1_gml.cpp.
    
    Helped in preparing datasets and input handling.

Aariv(2022A7PS0052H) and Animish(2022A7PS1367H) :

    Studied and implemented the CoreExact algorithm (Algorithm 4).
    
    Wrote Algo_4.cpp.

    Focused on optimizing flow network construction and core pruning.

    Handled GML datasets and parsing.

Saumya(2022A7PS1318H) :

    Focused on Yeast dataset integration.

   	 Studied and implemented the CoreExact algorithm (Algorithm 4).
		
	Wrote :  Algo4_gml.cpp.

    Processed outputs and helped validate correctness.

    Prepared experimental results.

