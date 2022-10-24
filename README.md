[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=sundeepk1_ACPP&metric=alert_status)](https://sonarcloud.io/dashboard?id=sundeepk1_ACPP)

# ACPP
Anti Cancer Peptide Predictor

1. Introduction
   =============
    ACPP is a Support Vector Machine based tool to predict whether the given peptide is an Anti-cancer peptide or Not. The three different modes include (i) Protein scan with apoptotic domain prediction; (ii) Multiple peptide mode; and (iii) Peptide mutation mode for prediction and design of anti-cancer peptides.
Refer: ["ACPP: A Web Server for Prediction and Design of Anti-cancer Peptides." International Journal of Peptide Research and Therapeutics 21.1 (2015): 99-106"](http://link.springer.com/article/10.1007%2Fs10989-014-9435-7) for more deatils. Supplementary file could be found above as file named "supp.rar"

2. Installation
   ============
2.1 Linux OS
   (a) Download ACPP from github.
   (b) Extract the files to the desired location.
   (c) Provide executable permission to ACPP file (if it doesn't have executable rights).
   (d) Provide read and write permission to the folder you are putting the extacted files (if it doesn't have read and write permission).
   (e) make sure java 1.6 or higher is installed in your system.
   (f) make sure PERL 5.0 or higher version is installed in your system.

2.2 Running the application as a Docker contianer
    <<TO_DO>>
   3. Instructions
   ===============
    Execute the program by typing the following command after installation.
    ./ACPP
    The program is interactive and self explanatory. For more details about Mutate option refer "Mutate Help" file provided in the repository, for others refer "Help" file in the repository.

   4. License
   =======
   ACPP V1.0 is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation version 2.0 of the License.
   This software is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License contained in the file LICENSE for more details.

