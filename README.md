# Extracting Image and Video Metadata Using Kali Linux
## Project Description

A practical digital forensics investigation project demonstrating how to extract, analyze, and interpret image and video metadata using Kali Linux and forensic tools such as **ExifTool**.

The project explores how metadata can reveal valuable digital footprints, including timestamps, device information, file properties, and potential geolocation data. These details support digital investigations, cybercrime analysis, and digital evidence examination.

## Practical Guide

This practical demonstrates how to investigate digital files by extracting and examining embedded metadata to understand their properties and identify potentially useful forensic information.

### Objectives

By the end of this practical, you should be able to:

1. Understand digital footprints and metadata in multimedia files.
2. Identify image and video file properties using Kali Linux.
3. Install and use ExifTool for metadata extraction.
4. Examine timestamps, camera information, file details, and available GPS coordinates.
5. Interpret metadata for digital forensic investigations.
6. Document findings and present forensic observations.

## Tools and Technologies

- **Operating System:** Kali Linux
- **Primary Tool:** ExifTool
- **Investigation Area:** Digital Forensics
- **Evidence Types:** Images and Videos

## Ethical Considerations

All investigations should be conducted using legally obtained files and with appropriate authorization. Digital evidence should be handled responsibly to preserve its integrity and maintain privacy.
# Step-by-Step Guide

## 1. Start Kali Linux

- Start your Kali Linux virtual machine or physical computer.
- Log in to your account.
- Open the Terminal using the keyboard shortcut:

```bash
Ctrl + Alt + T
```

## 2. Install ExifTool

Run the following command to install ExifTool:

```bash
sudo apt update
sudo apt install libimage-exiftool-perl -y
```

## 3. Verify ExifTool Installation

Run:

```bash
exiftool -ver
```

If the installation is successful, the terminal will display the installed ExifTool version.

![Version](img/version.png)

## 4. Create a Working Directory

Create a folder for the practical on your desktop:
Move to Desktop
```bash
cd Desktop
```

Create the folder:
```bash
mkdir Metadata_Lab
```

Navigate into the folder:
```bash
cd Metadata_Lab
```

Inside `Metadata_Lab` folder Create the folder `sample-files` and Navigate into the folder:
```bash
mkdir sample-files
cd sample-files
```
![filenavigation](img/filenavigation.png)
<img src="img/filenavigation.png" alt="filenavigation" width="300" height="200">

## 5. Add Sample Files

Prepare the following sample files:

- One JPG/JPEG image.
- One PNG image.
- One MP4 video.

You may use photographs taken with your phone or other sample media you have permission to examine. Transfer or copy all the files into the `sample-files` folder using the Kali Linux File Manager.

## 6. Verify the Sample Files and Identify the File Types

Run:
```bash
ls -lh
```
This command lists the files in the working directory, together with their sizes and permissions.

Run:
```bash
file *
```
Examine the output and identify:
- The JPEG image files.
- The PNG image file.
- The MP4 video file.
- The file sizes and formats.

**Observation:** Record the file types and sizes. Note that a file extension does not always indicate its actual file format.

---

## Am still working on this project, soon will update with screenshots and all resources required........



## Conclusion

Metadata analysis is an important component of digital forensics. By using Kali Linux and ExifTool, investigators can uncover useful information embedded within multimedia files, helping them understand digital activities and establish potential investigative leads.

## Prepared by Mr. Jefferson Mwatati
