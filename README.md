# Sorting-File-Data
### Description:<br />
This program parses through a set of companies and their incomes, returning different specified values. When the main function is run through testbench.asm the program will output the length of the data set in bytes, the maximum income value in the data set, the minimum income value in the data set, and the total sum of incomes in the data set.

### How to Run This Project:<br />
First, install RARS for RISC-V through the .jar file on this page (https://github.com/TheThirdOne/rars/releases/tag/v1.6). Then, download all the files in the repository and open them in RARS. Run testbench.asm to test all the files's functions against data.csv. If you would like to test the functions with another set of data, make sure to use a Windows computer when uploading the file. This is due to the differences in how Windows and Mac computers encode the new line character.<br />

### Authors:<br />
#### Amisha Nambiar and Professor Sagnik Nath from the University of California Santa Cruz
Amisha Nambiar authored length_of_file.asm, income_from_record.asm, maxIncome.asm, minIncome.asm, and totalIncome.asm.<br />
Professor Sagnik Nath authored allocate_file_record_pointers.asm, data.csv, and testbench.asm.<br />

### Files in This Repository:<br />
length_of_file.asm finds the number of bytes the data is (including new line characters).<br />
allocate_file_record_pointers.asm allocates the array of file record pointers to the starting memory location 0x10040000.<br />
income_from_record.asm returns the numerical value at the specified pointer location.<br />
maxIncome.asm returns the maximum numerical income in the data set.<br />
minIncome.asm returns the minimum numerical income in the data set.<br />
totalIncome.asm returns the total sum of numerical incomes in the data set.<br />
data.csv holds the data set of company names and numerical incomes separated by a comma.<br />
testbench.asm holds the main program that tests all functions with the data from data.csv.<br />
