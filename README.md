# File Packer/Unpacker

![Java](https://img.shields.io/badge/Java-Programming-orange)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue)
![Architecture](https://img.shields.io/badge/Architecture-Intel%2032%20Bit%20or%20Higher-blue)

## Overview

This Java-based application facilitates the zipping and unzipping of directories, offering a versatile solution for file management. The project supports both Command Line Interface (CLI) and Graphical User Interface (GUI) for user interaction.

## Platform and Architecture Requirements

- **Platform:** Windows or Linux Distributions
- **Architecture:** Intel 32 Bit Processor or Higher

## Technology Used

- **Programming Language:** Java

## Features

1. **Packing Activity:**
   - Combines metadata and data of multiple files from a specified directory into a single archive.

2. **Unpacking Activity:**
   - Extracts all data from packed files and creates individual files according to their metadata.

3. **Platform Independency:**
   - Utilizes Java for both frontend and backend, ensuring the application's compatibility across different operating systems.

## Usage

### Command Line Interface (CLI)

To pack files:
```bash
java -jar FilePackerUnpacker.jar pack <source_directory> <destination_archive_name>


To unpack files:
```bash
java -jar FilePackerUnpacker.jar unpack <packed_archive> <destination_directory>

Graphical User Interface (GUI)
Run the GUI application:
```bash
java -jar FilePackerUnpacker.jar gui



## ABOUT

This application is designed for packing and unpacking activities involving multiple types of files. In the packing process, a single file is maintained, containing metadata and data from various files within the specified directory. The unpacking process extracts data from packed files and recreates individual files based on their metadata. Java is employed for both frontend and backend development to ensure platform independency.

