
# UiPath Email Parsing and RPA Challenge Automation

This RPA with UiPath project demonstrates reading structured data from an email inbox, parsing the content, and automating data entry on [rpachallenge.com](http://rpachallenge.com). Designed as a tutorial basis, the branches legacy/* showcase outdated coding practices and lack modern best practices.

## Project Overview

This automation performs the following steps:
1. Connects to an email inbox using Orchestrator-stored credentials.
2. Reads and parses structured content from emails.
3. Enters parsed data into [rpachallenge.com](http://rpachallenge.com).

### Branches
- **legacy/REFramework2016**: Contains code with outdated practices and minimal configurability, serving as an example of non-compliant code.

## Requirements

- **UiPath Studio**: Tested with version 2024.10.x.
- **Orchestrator Credentials**: Requires credentials stored in UiPath Orchestrator for mail server access.

## Project Details

- **Orchestrator Integration**: Credentials for the email server are securely retrieved from UiPath Orchestrator.
- **Minimal Configurability**: This project has several hardcoded values for educational purposes, demonstrating limitations of low-configurability design.

## Getting Started

1. Clone the repository and switch to the `legacy/REFramework2016` branch.
2. Open the project in **UiPath Studio 2024.10.x**.
3. Ensure Orchestrator credentials are set up and available for the project.
4. Run the automation to observe the email parsing and data entry flow.

## Purpose

This project is intended as a base for tutorials, illustrating:
- Legacy coding practices in UiPath.
- Hardcoded, low-configurability structures.
- Potential refactoring opportunities for modern UiPath standards.
