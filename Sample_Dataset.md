Day 12 – Sample Dataset Preparation
Introduction

A sample dataset is required to perform file deletion and recovery experiments. Different types of files are created and stored in the file system to simulate real-world data.

Dataset Description

The following file types were selected:

Text Files
notes.txt
project.txt
Document Files
report.docx
assignment.docx
PDF Files
sample.pdf
guide.pdf
Image Files
image1.jpg
image2.png
Purpose of Dataset

The dataset is used to:

Store files in XFS and Btrfs file systems.
Perform deletion operations.
Recover deleted files using forensic tools.
Analyze recovered metadata.
Dataset Characteristics
File Type	Purpose
TXT	Simple text data
DOCX	Document recovery testing
PDF	Structured file recovery
JPG/PNG	Image recovery testing
Storage Procedure
Create a directory named TestData.
Store sample files inside the directory.
Verify file accessibility.
Record file information before deletion.
Expected Outcome

The dataset will serve as the primary source for testing deleted file recovery and metadata analysis in both XFS and Btrfs file systems.

Outcome

A sample dataset containing multiple file formats was prepared successfully for future recovery experiments.
