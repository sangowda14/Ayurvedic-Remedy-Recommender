# Ayurvedic-Remedy-Recommender
An Android application that enables users to search Ayurvedic remedies based on symptoms, view detailed information, and manage favorite formulations. Designed with offline support, login/signup functionality, and educational resources to digitize classical Ayurvedic knowledge.

## Features
- Symptom-based search using keyword mapping
- Save and manage favorite remedies
- User authentication: login and sign-up
- Static "About" page for app information

## Tech Stack
- Platform*: Android (Java)
- UI Framework*: XML layouts
- Data Handling: Static datasets with mock search logic
- Storage: Room Database (for favorites)
- Navigation: Intent-based activity flow

## App Structure
SplashActivity → LoginActivity / SignUpActivity → HomeActivity
    ├── SearchActivity → DetailsActivity
    ├── AboutActivity
    └── SavedFormulationsActivity → DetailsActivity
    
## My Contribution
This project was completed as a group project.
Sanjana B.K contributed to:
- Building a structured symptom-based search feature using XML databases with synonym mapping and contraindication filters  
- Developing multiple app modules including login/signup, remedy search and remedy details 
