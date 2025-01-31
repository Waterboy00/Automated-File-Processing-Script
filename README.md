# Automated-File-Processing-Script
A script to automatically process and print files based on their names.
Automated File Renaming and Printing Script

What It Does

This script automates the renaming and printing of files in a folder. It’s set up to rename files (like bills of lading or shipping labels) based on their order number, move them to a "processed" folder, and print them if needed. It runs on macOS and uses AppleScript.

What You’ll Need

AppleScript (already on macOS)
A printer (you’ll need to update the script with your printer name)
How To Set It Up

Download the repo or copy the script.
Open AppleScript Editor on your Mac.
Copy and paste the script into the editor.
Find and update these placeholders in the script:
 Path to the folder where your files will be downloaded.
 Path to the folder where processed files will go.
  Printer name 
Save the script and run it in the background.
How It Works

It watches a folder for new files.
Renames files based on order numbers in their names.
Moves renamed files to a processed folder.
If the file is a shipping label or bill of lading, it’ll print.
Example Flow

Drop files in the source folder.
The script renames them based on the order number.
It’ll print the labels or bills of lading if needed.
Renamed files are moved to the processed folder for record-keeping.
