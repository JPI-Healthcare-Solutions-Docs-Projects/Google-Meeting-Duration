# Google-Meeting-Duration
Understanding How to retrieve a Google Meeting total duration

## Pre-requisites:
Tool to extract .ZIP Files
Reputable Tools:
- [Winrar](https://www.win-rar.com/download.html?&L=0)
- [7Zip](https://www.7-zip.org/download.html)

## Table of Contents
- Exporting Google Data
    - How To Export Data
- Understanding Google Meets Exported Data
    - How to understand Google Meets data 

## Exporting Google data

Data used within Google's applications is tracked and can be exported

### How to export data

1. Navigate to the Google Meets website:

[Google Meet Link](https://meet.google.com/)
  
2. Click on the settings button on the top right:

<img src="https://github.com/user-attachments/assets/1150a368-ab25-4557-a2b2-796352299ccc" alt="drawing" width="700"/>

3. Clicking on the settings button will open a settings popup

Navigate to the **Call history**

<img src="https://github.com/user-attachments/assets/ac6d159e-6398-47b2-bc7d-96cd97b20a37" alt="drawing" width="400"/>

4. You will finally have access to exporting your call history:

Click on **Export your history**

<img src="https://github.com/user-attachments/assets/cfdc31ad-ba56-4e95-8402-d340adfecc7d" alt="drawing" width="400"/>

Case Scenario:

You may set your call history to be automatically deleted after a certain age:

<img src="https://github.com/user-attachments/assets/808e52b9-c3ac-430a-8e87-30858b835c13" alt="drawing" width="300"/>

5. Exporting your Google data history

Clicking on Export your history will navigate you to Google Takeout.
Here you can export data from the Google applications you are using.

Unselect all and look for Google meets

https://github.com/user-attachments/assets/7c7a9fde-c20b-4b21-9060-67e8dff0a0d2

## Opening Google Meetings Data

### How to get to Google Meets Data

So far, we have exported the data from Google. Depending on how many Google meetings you have saved, it may take mere seconds to a whole day.
Once the data is successfully exported, you will receive an email from Google Takeout:

![email](https://github.com/user-attachments/assets/8264e0c9-484b-48b5-b21b-8ee97f473574)

1. Click on **Download your files**, where it will prompt you to log in. Once logged in, Google will automatically download the file.

2. Click on the downloaded file. Your installed tool to extract .zip files will automatically open in a new window.

3. You can drag the file onto your desktop and open the file with Excel, or any other applications to open a .csv file.

4. Navigate the following path: Google Meet(Folder) -> Conference History(Folder) -> conference_history_records.csv(File)

5. Once you open the file name conference_history_records.csv(File), you will see a list of encrypted code and text.
What we will be focusing on is the Column named **Meeting Code**, **Start Time**, **End Time**, and **Duration**.

### Video Tutorial

https://github.com/user-attachments/assets/a9f6deec-d872-43ea-922c-6374dca5d681

## Find your Specific Google Meeting Code

1. Navigate to your calendar and find the specific meeting you want to find a duration for

2. Click on the meeting, and the meeting code will be seen in the picture below
  
3. Navigate back to the conference_history_records.csv(File) and find the respective meeting code and the specific date.

4. You have now located the duration for a specified Google meeting that took place.

Video Tutorial:

https://github.com/user-attachments/assets/20c6812a-1043-4288-ba2f-1230060a5d22

## FAQ

For any additional questions Email: brandon.chin@jpihealthcare.com



