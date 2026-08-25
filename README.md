Chain of Custody – Digital Forensic Investigation
Project Overview

This project demonstrates a digital forensic investigation and the proper handling and analysis of digital evidence while maintaining the principles of chain of custody. The investigation was performed on a forensic disk image using digital forensic tools to examine files, metadata, hashes, and other relevant artifacts.

The project focuses on preserving the integrity of digital evidence and documenting the investigation process in a structured and forensically sound manner.

Objective

The main objective of this project is to perform a systematic digital forensic investigation and demonstrate the process of maintaining the chain of custody of digital evidence. The project focuses on analyzing a forensic disk image using tools such as Autopsy, Sleuth Kit, and PowerShell, verifying the integrity of evidence through cryptographic hashing, examining files and metadata, and identifying relevant digital artifacts.

The investigation aims to ensure that digital evidence is collected, preserved, analyzed, and documented in a reliable and forensically sound manner without compromising its integrity.

Tools Used
Autopsy – Digital forensic investigation and evidence analysis
Sleuth Kit – File system and forensic artifact analysis
PowerShell – Hash generation and evidence integrity verification
Windows Environment – Supporting analysis and verification
Evidence Analyzed

The investigation was performed on an NTFS forensic disk image in E01 format.

The evidence files analyzed during the investigation included:

ntfs1-gen0.E01
ntfs1-gen1.E01

The forensic image was examined without modifying the original evidence.

Methodology

The investigation followed a structured digital forensic workflow:

Identification of the forensic evidence.
Verification of the evidence using cryptographic hashes.
Loading the E01 forensic image into Autopsy.
Examination of the NTFS file system.
Identification and analysis of files and folders.
Examination of file metadata and timestamps.
Analysis of recovered images and PDF files.
Examination of forensic artifacts such as $MFT and $LogFile.
Statistical analysis of the files and evidence.
Documentation of observations and findings.
Preservation of evidence integrity throughout the investigation.
Hash Verification

Cryptographic hashing was used to verify the integrity of the forensic evidence.

SHA-256 hashes were generated using PowerShell and compared/recorded as part of the evidence verification process.

Hash verification helps demonstrate that the forensic evidence has not been altered during the investigation.

File & Metadata Analysis

The forensic image was examined using Autopsy and Sleuth Kit to identify and analyze digital artifacts.

The analysis included:

File and folder identification
File size examination
MIME type identification
Metadata examination
Timestamp analysis
PDF file analysis
Image file analysis
Examination of NTFS artifacts
Identification of $MFT and $LogFile
Examination of recovered and compressed files

One of the identified files was report02-3.pdf, which was further examined for its file information and metadata.

Statistical Analysis

Statistical analysis was performed to understand the distribution and characteristics of the files present in the forensic evidence.

The analysis included:

Total number of identified files
File types and categories
MIME types
File sizes
Distribution of digital artifacts
Identification of image and document files

This analysis helped provide an overall understanding of the contents of the forensic image.

Key Findings

The investigation demonstrated the following key findings:

The NTFS E01 forensic image was successfully analyzed using Autopsy.
Cryptographic hashing was used to verify evidence integrity.
Multiple files and digital artifacts were identified from the forensic image.
Images and PDF documents were successfully located and examined.
Metadata and file information were analyzed.
NTFS forensic artifacts such as $MFT and $LogFile were identified.
Statistical analysis provided an overview of the evidence contents.
The investigation demonstrated the importance of maintaining evidence integrity and proper documentation during digital forensic analysis.
Screenshots

The following screenshots demonstrate important stages and results of the forensic investigation:

Evidence Hash Verification using PowerShell
report02-3.pdf File Analysis
Recovered Image Analysis
Statistics Analysis
Autopsy Evidence/File Analysis
Project Presentation

The complete project presentation is included in this repository:

Ridhi Jain Chain of Custody.pptx

Conclusion

This project provided practical experience in digital forensic investigation and evidence handling. The forensic disk image was examined using Autopsy and Sleuth Kit, while PowerShell was used for cryptographic hash verification.

The investigation demonstrated how digital evidence can be systematically examined, verified, and documented while maintaining its integrity. It also provided hands-on understanding of file systems, metadata, forensic artifacts, recovered files, and statistical analysis.

Overall, the project helped in understanding the practical application of digital forensics, evidence preservation, hash verification, and chain of custody principles.# Chain-of-Custody-Forensic-Analysis
