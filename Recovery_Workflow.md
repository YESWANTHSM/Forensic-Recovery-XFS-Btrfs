Day 13 – Recovery Workflow Design
Introduction

A recovery workflow defines the sequence of steps followed to recover deleted files and analyze metadata from file systems. This workflow helps in conducting recovery experiments systematically.

Recovery Workflow
Create Sample Files
        ↓
Store Files in File System
        ↓
Delete Files
        ↓
Use Recovery Tools
(TestDisk / PhotoRec)
        ↓
Recover Deleted Files
        ↓
Analyze Metadata
        ↓
Compare XFS and Btrfs Results
Workflow Description
Step 1: Create Sample Files

Various files such as TXT, PDF, DOCX, and JPG files are created for testing.

Step 2: Store Files

The files are stored in XFS and Btrfs file systems.

Step 3: Delete Files

Selected files are intentionally deleted.

Step 4: Recovery Process

Recovery tools are used to recover deleted files.

Step 5: Metadata Analysis

Recovered files are analyzed for:

File Name
File Size
Timestamps
Permissions
Step 6: Result Comparison

The recovery performance of XFS and Btrfs is compared.

Importance of Workflow
Provides a structured recovery process.
Helps in forensic investigation.
Ensures consistency during testing.
Outcome

The recovery workflow for deleted data and metadata analysis was successfully designed and documented
