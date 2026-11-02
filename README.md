# FlexiGo Campus Shuttle Scheduler & Reservation Tool

# CS 19300 Final Project
A lightweight Java application that helps Purdue University students quickly check FlexiGo shuttle schedules, find campus bus stop locations, and calculate the optimal departure times for campus shuttles/transit.

# Project Goal
Purdue's campus shuttle app, "FlexiGo," often makes students manually check scheduled routes, figure out when to request on-demand rides, and decide the best pick-up and drop-off spots. This project provides a terminal-based tool to help students quickly check fixed shuttle times, look up stop locations, and calculate when they need to request an on-demand ride when necessary.

# MVP Scope
**Local CSV Data Parsing:** Reads and parses FlexiGo route schedules, stops, and distance data from a local CSV file using BufferedReader.
**Interactive Terminal Menu:** Prompts users via standard Scanner input to search schedules by route name, location, and data.
**Route & Time Calculations:** Matches user inputs against shuttle times to determine the best bus stops, calculate distances, and compute upcoming departure or on-demand timing.
**Formatted Output:** Displays clear upcoming ride times and trip estimates in the terminal as formatted strings.

# Future Plans
**Graphic UI:** A desktop UI
**Live Transit API Integration:** Connecting to real-time GPS from busses to track shuttle locations.
**Automated Notifications:** SMS/Email/Notication alerts reminding students when to head to a stop.

# Tech Stack & Structure
**Language:** Java
**Libraries:**
    java.util.Scanner
    java.io.BufferedReader
    java.time.LocalTime
    java.util.ArrayList
**Data Storage:** Local CSV file imported from FlexiGo data (could be mock schedule)

# Folder Structure
```text
CS193FinalProject/
├── data/
│   └── flexigo_routes.csv
├── docs/
│   ├── SystemDiagram.png
│   └── EisenhowerMatrix.pdf
├── src/
│   ├── Main.java
├── tests/
│   ├── .gitkeep
└── README.md
