
# Event Management ASP.NET Core MVC — Assignment Project

## Overview

This repository holds an ASP.NET Core MVC web application created as part of an Internet programming module assignment.
The project was initially scaffolded with empty or partially completed files; the goal was to write missing code and fix gaps so the application runs correctly. It demonstrates my work on MVC structure, controllers, data models, views, and basic ASP.NET Core setup.

## Current state

* Project contains the base folder structure, models, controllers, views, and migrations from the assignment.
* Some files were empty or missing code during the assignment; this repo reflects the version created for learning, review, and portfolio use.
* The application is **not** a polished, production app—think of it as a functioning school project that shows understanding of MVC patterns and ASP.NET Core.

## Features implemented

* Basic event and attendee management structure:

  * Models for Event and Attendee.
  * Repositories for data access.
  * Controllers for events and attendees.
  * Views for listing, registering, and viewing details.
* Starter styling and layout using provided styles and libraries.
* Database context and migration setup for local development.

## What to improve or add next

* Full UI polish and responsive design.
* Robust input validation and error handling.
* User-friendly navigation or authentication if needed.
* Additional tests or deployment pipeline.
* Performance or security tweaks for future versions.

## How to run locally

Below is a general way to get started. Exact commands may vary slightly depending on your setup and .NET SDK version.

1. **Clone the repository**

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. **Ensure .NET SDK is installed**
   Install the required SDK version matching the project if not already on your machine.

3. **Restore packages**

```bash
dotnet restore
```

4. **Apply migrations and update the database**

```bash
dotnet ef database update
```

*If migrations are already applied or if using a pre-populated DB file, skip as needed.*

5. **Run the application**

```bash
dotnet run
```

6. **Open in browser**
   Typically at `https://localhost:5001` or the URL shown in the console.

*Note: exact steps may differ based on environment, SDK, or project settings. Adjust as needed.*

## Technologies used

* ASP.NET Core MVC
* C#
* Entity Framework Core for data access
* Razor views for frontend templates
* Basic frontend assets for styles and layout

## Learning and purpose

This project was built to practice structuring a .NET MVC application, understanding how models, views, controllers, and data access interact, and fixing incomplete code in a real assignment scenario. It acts as a portfolio example of working with backend logic and typical web app architecture.

## References & guidance

A good README helps visitors understand what the project does, why it’s useful, and how to get started. GitHub’s own guidance emphasizes using a README to communicate important information about a project and assist visitors. ([GitHub Docs][1])
Community and tutorial guidance also stresses covering what, why, and how in a README, along with installation or run instructions. ([FreeCodeCamp][2]) ([FreeCodeCamp][3])

## Author
Owethu Gweba
