This is the script used to grab a csv from our S3 bucket, merging the data from this file with a docx file to take all the instances of a column name referenced as '<<column>> to be replaced with the value that is in each row. Itterating each row and creating a new portion of the template every row. 
TLDR: Merging a s3 csv with a .docx template copied from dockerfile and exporting a new .txt file that can be exported into another s3 bucket.
