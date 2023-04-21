# csv_file_merge_program
Program to merge csv files in a folder that have the same configuration

This program combines multiple CSV files into a single dataframe and saves it as a new CSV file.

The program first sets the directory containing the CSV files and creates an output directory where the combined CSV file will be saved. It then gets a list of all CSV files in the directory using the glob module.

Using pandas' concat method, the program combines all CSV files in the directory into a single dataframe. It displays a progress bar using the tqdm module to show the user the progress of the operation.

Finally, the program saves the combined dataframe as a new CSV file in the output directory. The index=False parameter in the to_csv method ensures that the dataframe index is not included in the output file.
