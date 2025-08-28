# Google Location History Takeout Parser

Announcing Version 1.4.1, with added Horizontal Accuracy KML files for Records.JSON data and Parking Events!

<img width="1032" height="667" alt="1 4 1_image" src="https://github.com/user-attachments/assets/98048d1b-860d-49dc-b6a6-2a3dd7827f69" />

Parsing Google Takeout Location History Timeline Exports or Google Semantic Location History Warrant Return Data in a forensic manner.

## What's New

Records.JSON data and Parking Events location points, which inherently both have horizontal accuracy values, can now visually display this data with two new added KML files! 

Location_Data_Records_Hori_Acc.kml pairs with Location_Data_Records_JSON_Data.kml and Activity_Segment_ParkingEvent_Hori_Acc.kml pairs with Activity_Segment_ParkingEvent.kml to show both the horizontal accuracy, the point itself, or both.

Here, depicted through overlapping KML files opened using Google Earth, is one example:

<img width="1002" height="879" alt="Example_Hori_Acc" src="https://github.com/user-attachments/assets/f1abdfed-ba75-4e55-8631-a11662154535" />

## Recent Prior Additions

 • Multithread performance for faster background processing.

 • Time elapsed tracking for greater visibility into processing stages.

 • Input file / folder size calculation.

 • Expanded support for location data related files, including HTML, CSV, and TXT.

 • TimeSpans and description have been added for location data with duration values, starting and ending timestamps.
![PlaceVisit](https://github.com/user-attachments/assets/cd45b0e9-0f78-42df-9b59-84e08da44152)

 • LineString additions have been added alongside our prior KML support. Location data possessing multiple points for one object can be viewed by point or LineString, such as Activity Segments, Waypoints, and Simplified Raw Paths.
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

Special thanks to our community members:
- @Goncalo-sousa and @stark4n6 for troubleshooting and assisting in the process
- @andyzukunft for the TimeSpan focus
- @roswitina for giving the horizonal accuracy KML inspiration that helped version 1.4.1 come to life

We have a great DFIR Community!

This application was created by James R. McGee, Director of Digital Forensics Research, Senior Digital Forensic Examiner, for use by the Digital Forensic Incident Response Community. James and Metadata Forensics, LLC, are proud to give back to our great Community.
