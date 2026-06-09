# Perry_et_al_2026

Repository with the analyses from Perry_et_al_2026.

The repository has all the results of running qiime2 in our data with the exception of the imported data artifacts as these are too big.

If you want to rerun the analyses, the data used is available at Zenodo: 



Download the data, unzip the file, and add the `data` directories for Bacteria and Fungi for the 2018/2020 and 2023, to the corresponding directories in the repository.

To run all the analyses for Bacteria and for Fungi, start at the `2023` directory and run the notebook `01-Process2023.ipynb` (you need to edit the `manifest.txt` file to point to your `data` directory). Move to the `2018/2020` directory and run the notebook `02-Process2020.ipynb`. Finally, run the analyses in the notebook `03-merge.ipynb` in the `03-Merge-years` directory. This will run all the analyses.



