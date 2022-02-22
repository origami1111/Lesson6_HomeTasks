# Generics and Collections

Collection part:
- Reuse your console application from HW for Lecture #5;
- As an input now you have a folder with several .txt and .csv files;
- Each line in file now MUST contain more than 2 numbers;
- Program should be modified to be able to work with several input files (with the same extension);
- Data from all input files should be read and aggregated into 1 list, then, for each line with the numbers, 
  sum and multiplication result should be calculated and saved into the file.
  
Generic part:  
You need to implement 2 various of FileReader class:
- FileReader should be as a Generic class;
- FileReader  should have a Generic method;

FileReader as a Generic class should read file, deserialize it and increase age to +1:
- Input file example: { "Name": "John", "Age": 33 }
- Output file example: { "Name": "John", "Age": 34 }

FileReader with Generic method should read file, deserialize it and decrease count to –1:
- Input file example: { "Type": "Table", "Count": 5 }
- Output file example: { "Type": "Table", "Count": 4 }
