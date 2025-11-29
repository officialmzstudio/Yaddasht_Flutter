# Yaddasht - Flutter Note Taking App [WIP]

This is a modern, lightweight note-taking application built using the **Flutter** framework. The project is **currently under active development** with a focus on delivering a clean, efficient, and **Offline-First** user experience across multiple platforms.

| Project Status | Details |
| :--- | :--- |
| **Status** | **Active Development** (Pre-Release) 🚀 |
| **Technology** | Flutter SDK |
| **Language** | Dart |
| **Focus** | Local Data Persistence & Clean Architecture |
| **Platforms** | Android, iOS (Target) |

## Current Functional Features

The current implementation provides the core foundational elements for note management:

* **Full CRUD Functionality:** Basic functionality to **C**reate, **R**ead, **U**pdate, and **D**elete notes is functional.
* **Offline-First Persistence:** All memo data is stored securely and locally on the device (using a database layer).
* **Timestamping:** Automatically records the creation date and the last modification time.
* **Clean User Interface (UI/UX):** The initial minimalist design structure is implemented.

## Planned Features & Roadmap

Future development will focus on the following enhancements:

* Advanced Search and Filtering capabilities.
* User interface customization (e.g., Dark Mode support).
* Categorization and Tagging system for notes.
* Improved input handling (e.g., Rich Text formatting).

## Technical Implementation & Architecture

The project leverages modern Flutter techniques to ensure scalability and maintainability, serving as a solid demonstration of Flutter application architecture.

## Core Libraries & Dependencies

| Area | Package (Likely Used) | Purpose in Project |
| :--- | :--- | :--- |
| **State Management** | `provider` / `flutter_bloc` | Handles application state and business logic separation. |
| **Local Database** | `sqflite` / `hive` | Manages persistent, local storage of all note data. |
| **Formatting** | `intl` | Used for localizing and formatting dates and times. |

## Architectural Pattern

The code adheres to the **Repository Pattern** to maintain a clean separation of concerns:

* **View Layer (Widgets):** Responsible only for rendering the UI.
* **State Management Layer:** Manages application state and business logic.
* **Data/Repository Layer:** Abstract layer communicating with the underlying **Local Database**.

  
🤝 Contribution & Feedback
As this project is a Work in Progress (WIP), all forms of feedback, bug reports, and code contributions are highly welcome and appreciated!

If you find any bugs or areas for improvement, please open an Issue.

For code contributions, please submit a Pull Request referencing the relevant issue.

Developed by: Mohammad Zibanchi - MZDEV
