# Compose_Camp_2022_App

App developed by Diptadip Mallik (GDSC IIT Patna Android Dev Lead 2022-23)

## Problem Statement:

Mobile app for quick, convenient, and hassle-free note-taking. 


## Proposed Solution with Screenshots:

We have developed an App using Jetpack Compose for creating, reading, updating, and deleting notes.

Screenshots –https://drive.google.com/drive/folders/18JU13NRho8Go8mH8CvTyQLXChADY1s0v?usp=sharing 


## Functionality and Concepts used:

This app is a clean architecture Note App made with Jetpack compose. It uses Model-View-ViewModel (MVVM) concept and CRUD operations on the room database. It also uses Dagger-Hilt and Kotlin coroutines to ease the app's readability, understandability, and code synchronization.
The App architecture is divided into three main layers - Data layer, Domain layer, and Presentation layer. The Data layer consists of the room database and its implementation where the CRUD operation is done. The Domain layer consists of the database model and the possible use cases that the users can do in the app, such as adding, deleting, or editing a note. The Presentation layer handles primarily what the user sees, using all the use cases it provides interactive functionality in the app.


## Application Link and Future Scope:

GitHub Link - https://github.com/dsciitpatna/Compose_Camp_2022_App

APK - https://drive.google.com/drive/folders/18X2SNXhUQ2mUGBrDPgM_WFEdondYzJv_?usp=sharing 

One-Pager App Intro Submission - https://docs.google.com/document/d/1l0q6PQce-vtJ3CUVKHhvUVYZGXpRlqDNeFotWMCSVjo/edit?usp=sharing

This application can be improved by allowing users to store their notes in the cloud to access them across devices which can be implemented using Google authentications by Firebase.

