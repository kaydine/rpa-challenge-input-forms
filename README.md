# R001 RPA Challenge Input Forms

## Project Details

### Process Overview
<!--- Brief description of what the process does -->
Below is the instructions for this challenge.
1. The goal of this challenge is to create a workflow that will input data from a spreadsheet into the form fields on the screen.
2. Beware! The fields will change position on the screen after every submission throughout 10 rounds thus the workflow must correctly identify where each spreadsheet record must be typed every time.
3. The actual countdown of the challenge will begin once you click the Start button until then you may submit the form as many times as you wish without receiving penalties.

This project solves the Input Forms challenge in rpachallenge.com.
It uses the uipath-template transactional process type to implement the dispatcher-performer model to demonstrate robustness, scalability, and maintainability. The dispatcher downloads the input Excel file, creates the transactions based on the data in the file, and add the transactions to the Orchestrator queue. The performer then gets these transactions and process each.

### Robot Type
<!--- Attended / Unattended -->
Unattended

## Getting Started

### Applications Used And Installation
<!--- Which version of UiPath, other applications used by the robot, application version, and how to install them -->
- Excel
- Microsoft Edge - UiPath Web Automation extension should installed

### Configurations
<!--- Any pre-requisites (like input files in certain directories, queue and assets in Orchestrator, etc.) -->
- Orchestrator queue *(see Config generalSettings\queueName for the queue name used)*

## Documentations

### Solution Design Document
N/A

### User Manual
N/A