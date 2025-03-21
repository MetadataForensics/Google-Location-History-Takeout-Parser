# Google Location History Takeout Parser

Announcing Version 1.3.0.0, with improved KML output functionality and support!

![Image](https://github.com/user-attachments/assets/eeb39577-f4df-4498-a097-c343c8fd456e)

Parsing Google Takeout Location History Timeline Exports or Google Semantic Location History Warrant Return Data in a forensic manner.

More details within our blog post, available at https://metadataperspective.com/2024/02/17/google-location-history-data-parser/

## What's New

TimeSpans and description have been added for location data with duration values, starting and ending timestamps.
![PlaceVisit](https://github.com/user-attachments/assets/cd45b0e9-0f78-42df-9b59-84e08da44152)

LineString additions have been added alongside our prior KML support. Location data possessing multiple points for one object can be viewed by point or LineString, such as Activity Segments, Waypoints, and Simplified Raw Paths.
![ActivitySegmentLineString](https://github.com/user-attachments/assets/c0ce4f09-485a-40f6-85d8-5d013b80932c)

## Downloading

Navigate to the Google Location History Data Parser Setup.exe above. Select "More file actions" on the right, shown by an "..." icon, and choose "Download".

When downloading, you may be met with a download issue requiring you to trust the application to open it. This is because the application is new and not commonly downloaded. Selecting "More actions" will allow you to "Keep" the file and complete the download. 

## Usage

You may also be required to take additional steps when running the tool the first time, through Microsoft Defender SmartScreen. In the Microsoft Defender SmartScreen select "More info" and "Run anyway" to launch the application the first time. 

## Parsing a Google Takeout Location History Export or Google Semantic Location History Warrant Return

Run the application, browse to either your input .zip file or your folder containing numerous .zip files (if your data is within several .zip files), browser to your output folder, and select "Process." Your Google data will be parsed into several CSV files, the original files will be exported for data validation, and an information .txt file will all be saved to your output location!

## Acknowledgement

This software includes the CustomTkinter library, which is licensed under the MIT License. Copyright (c) 2023 Tom Schimansky. The full license text can be found in the LICENSE file provided here: https://github.com/TomSchimansky/CustomTkinter.

We would like to extend our gratitude, and provide reference to, the Returns Logs Events And Properties Parser (RLEAPP) for inspiration to this project! Further thanks to Alexis Brignoni (@abrignoni) the creator of RLEAPP and all the LEAPP projects! RLEAPP supports Google Location History (Timeline) data and is a great resource for verifying results. Available here: https://github.com/abrignoni/rleapp

This application was created by James R. McGee, Digital Forensic Examiner, for use by the Digital Forensic Incident Response Community. James and Metadata Forensics, LLC, are proud to give back to our great Community.
