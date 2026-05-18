# Arogya-Sahaya Local (Healthcare Android App)

## About the Project

Arogya-Sahaya Local is a simple Android application made to help people in rural areas manage their medicines and basic health tracking. Many elderly users miss their medicines or health check-ups because it becomes difficult to remember multiple timings and visit schedules. This app is designed to solve that problem in a very simple way.

The main idea is to act as a digital health companion that helps users follow their medical routine properly and keep track of basic health data.

---

## Problem Statement

In rural areas, elderly patients often forget to take medicines on time or miss health camp visits and ASHA worker schedules. This can lead to health complications that could have been avoided with proper reminders and tracking.

There is a need for a simple mobile application that helps users manage their health routine without being complicated.

---

## Features

Medical Profile  
Users can enter basic details like age and health conditions. This helps in organizing their medical information.

Medicine Reminder  
Users can add medicines with name, dosage, and timing. The app reminds them at the correct time for morning, afternoon, or night doses.

ASHA Connect  
A simple calendar view that shows upcoming health camps or ASHA worker visits. This is based on sample data.

Vital Log  
Users can record daily health readings like blood pressure or heart rate. The app stores this data and shows trends over time.

Emergency Mode  
A simple SOS button that can be used in case of emergency to simulate a call or message.

---

## How the App Works

The user first creates a basic medical profile. After that, they can add medicines and set timings for reminders. The app sends notifications at the correct time so that the user does not miss their medication.

Users can also enter daily health readings in the vital log section. This data is stored locally and can be viewed later as a graph to understand health trends.

The ASHA Connect section helps users stay aware of local health camps and visits.

---

## Technical Details

The app is built using Kotlin and Android SDK.

It uses Room Database to store all data locally on the device, including medicines and health logs.

For reminders, AlarmManager or WorkManager is used so that notifications work even if the app is closed.

The MVVM architecture is followed to keep the code organized. Repository pattern is used to manage data flow between database and UI.

For showing health trends, MPAndroidChart is used to display a simple 7-day graph.

---

## Impact of the Project

This app is mainly designed for rural healthcare support. It helps elderly users take medicines on time and track their health without needing help from others.

It also helps ASHA workers get a better understanding of a patient’s health history during visits. Overall, it supports preventive healthcare and reduces the chances of missing important medical routines.

---

## Success Criteria

- Notifications should work properly even when the app is closed or the phone is in power saving mode  
- Vital logs should show a correct 7-day graph  
- The UI should be simple and readable for elderly users  
- The project should follow proper MVVM and Repository structure  

---

## How to Run the Project

Clone the repository:

git clone https://github.com/JiyaAgarwal-06/Arogya-Sahaya.git

Then open the project in Android Studio.

Let Gradle sync finish and run the app on an emulator or physical device.

---

## Tech Stack

Kotlin  
Android SDK  
Room Database  
MVVM Architecture  
WorkManager / AlarmManager  
MPAndroidChart  

---
