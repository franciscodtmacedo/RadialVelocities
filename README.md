'espresso_data' contains all of the data of the 20 spectra studied as well as the notebooks used to transpose the information in a complex table system of the fits format to plain ASCII text.

'Sun' contains an initial training test used to learn how to work with ARES and a basic analysis of a simple and small spectrum of the Sun.

'rejt_relation' has files numbered from 0 to 9 which are files returned by ARES (using the Sun test spectrum) with a rejt value ranging from 0.990 to 0.999 with a 0.001 step. It also contains a notebook
comparing the result for these different values.

'S1D' contains the notebooks for the first 6 S1D spectra as well as the data necessary to run them (in 'dados'). It also has a notebook named 'S1D_all_values' which was used to compare all of the data from the 
6 S1D spectra.

'S2D' contains the notebooks for the all of the S2D spectra (1 to 20) as well as the data necessary to run them (in 'data'). It also has a notebook named 'S2D_all_values' which was used to compare all of 
the data from the 20 S2D spectra. 'S2D_1' is in the directory '1'. 'values' contains the necessary data to run 'S2D_all_values'.


This part of the readme was created by Francisco:
The folders inside "Francisco contribution" present the exact same structure as Matilde's Folders, the difference being that the contents of the folders, the notebooks, are slightly altered. For the S1D spectra the alterations correspond strictly to the correction of the +f0 term and Sqrt(N) mistakes in the semi-group of 3741 lines, whilst
for the S2D spectra the alterations consist of new areas of code to determine the TOTDATA matrices, in both the start of the S2D notebooks and the end where the
3741 line semi-group is being treated. In the S2D spectra folder the data folders used are not found here due to github's restrictions, in case you need them,
access the following link : https://astrocloud.ddns.net/index.php/s/qyD9JT4imbQqme8
