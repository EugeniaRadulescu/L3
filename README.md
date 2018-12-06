# L3
Network-based prediction of protein interactions
doi: https://doi.org/10.1101/275529

All data files used in the manuscript are publicaly available at the references in the paper. Here we share the core network files and codes to help the use of our method on other datasets.

To complie the code, type:
g++ -O3 L3.cpp -o L3.out

To run the code on a tab-separated network file of 3 columns (numerical_id_1 tab numerical_id_2 tab weight), run:
./L3.out hi-ii-14.txt

The output lists all new predicted links ordered by their L3 score in the 3rd column.
