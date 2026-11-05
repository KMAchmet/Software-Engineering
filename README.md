# PR.I.M.A.L Scientific Book Store

**Professional Innovations in Modern Academic Learning**  
*“PRIMAL: Fueling Minds, Igniting Discovery”*

PR.I.M.A.L is an academic e-bookstore concept and software engineering project designed for students, members of the academic community, and readers interested in scientific and educational subjects. It combines an online bookstore with an e-book library and community-oriented features.

The project was developed as part of a Software Engineering course. It covers the software development process from requirements and UML modelling to a working graphical application and test scenarios.

## Table of Contents

- [Project Overview](#project-overview)
- [Main Features](#main-features)
- [User Roles](#user-roles)
- [Software Engineering and UML Documentation](#software-engineering-and-uml-documentation)
- [Technology Stack](#technology-stack)
- [Testing and Demonstrated Functionality](#testing-and-demonstrated-functionality)
- [Repository](#repository)
- [Project Scope and Notes](#project-scope-and-notes)

## Project Overview

The goal of PR.I.M.A.L is to make academic and scientific books easier to discover, purchase, organise, and read. Customers can browse the catalogue, search and filter books, manage a shopping cart, access their purchased books, write reviews, and participate in a reader community.

The system also defines a student customer category. Students are intended to receive free academic textbooks after institutional verification and access to special discounts on selected academic books.

Administrators manage the book catalogue, pricing and discounts, and moderate reported community content.

## Main Features

### Customer features

- **Book discovery:** Search by title, author, and keywords; browse categories; and sort search results by title or author.
- **Book details:** View book information, descriptions, author information, and ratings.
- **Shopping cart and checkout:** Add books to the cart and complete the checkout flow.
- **Personal library:** Access purchased books from a personal library.
- **E-book reader:** Read books and navigate between pages.
- **Reviews and ratings:** Rate books, write and publish reviews, and choose whether a review is anonymous.
- **Review rewards:** Earn badges based on the number of published reviews.
- **Community:** Publish posts, comment, react to content, manage personal posts and comments, and interact with other readers.
- **Notes:** Create, edit, sort, and delete personal notes.
- **Notifications:** View notifications, filter them by category, mark them as read, inspect their details, refresh the list, and delete individual notifications.
- **Wishlist and offline access:** Included in the documented requirements as intended platform capabilities.

### Administrator features

- **Book catalogue management:** Add and delete books and assign them to categories.
- **Discount management:** Apply discounts to book categories.
- **Content moderation:** Review reported comments and decide whether to delete or retain them.

### Student-specific concept

Students are intended to be able to obtain eligible academic textbooks for free following verification by their educational institution, and to receive student-only discounts.

## User Roles

| Role | Responsibilities |
| --- | --- |
| Customer | Search for, purchase, and read books; manage a library and notes; review books; and participate in the community. |
| Student | Customer with additional academic benefits, subject to institutional verification. |
| Administrator | Manage books and prices, apply discounts, and moderate reported content. |

## Software Engineering and UML Documentation

A major part of the project is its software engineering documentation. The submitted design material includes requirements, use-case descriptions, UML models, test scenarios, and interface mock-ups.

| Documentation | Purpose |
| --- | --- |
| Use-case descriptions and diagram | Describe the interactions between customers, administrators, and the system. |
| Sequence diagrams | Illustrate the interactions and order of operations for key use cases. |
| Robustness diagrams | Identify the boundary, control, and entity elements involved in key workflows. |
| Domain model | Describe the main domain concepts and their relationships. |
| Class diagram | Present the proposed software classes and their responsibilities. |
| Test cases | Demonstrate expected application behaviour through user and administrator scenarios. |
| UI mock-ups | Show the planned user interface and compare it with the implemented application. |
| SWOT analysis | Summarise strengths, weaknesses, opportunities, and threats relating to the project concept. |

The documented use cases cover:

1. Book search
2. Book purchase
3. Reading a book
4. Book reviews and ratings
5. Community browsing and interaction
6. Integrated notes
7. Notifications
8. Book uploads and catalogue management
9. Category-based discounts
10. Moderation and deletion of reported comments

The diagrams were created using **Lucidchart** and **draw.io**. The project documentation also references Google Docs for collaborative editing. Refer to the repository files for the full-size diagrams and supporting material.

## Technology Stack

| Technology / Tool | Use |
| --- | --- |
| Python | Application programming language |
| Kivy | Graphical user interface framework |
| KivyMD | Material Design components for the Kivy interface |
| pytest | Test execution; a notification test module is documented |
| PyCharm | Development environment |
| Visual Studio Code | Code editing |
| WSL / Ubuntu | Development environment |
| Lucidchart | Sequence and robustness diagrams |
| draw.io | Use-case, domain, and class diagrams |
| Google Docs | Collaborative project documentation |

## Testing and Demonstrated Functionality

The project report contains test scenarios and screenshots demonstrating customer and administrator workflows.

The documented demonstrations include:

- Searching for books and sorting results by author and title.
- Viewing book details and adding books to a shopping cart.
- Checking out with one or multiple books.
- Opening books from the personal library and navigating reader pages.
- Creating, publishing, sharing, and deleting reviews.
- Awarding review badges according to review count.
- Creating and managing community posts, comments, and reactions.
- Creating, editing, sorting, and deleting notes.
- Refreshing, filtering, viewing, marking as read, and deleting notifications.
- Adding and deleting catalogue books.
- Applying category discounts.
- Reporting comments and allowing an administrator to delete or retain reported content.

The report specifically documents a `pytest` run for notifications. Other workflows are illustrated through manual test scenarios and screenshots.

## Repository

The source code and project materials are hosted here:

**[PR.I.M.A.L – Software Engineering 2024–25](https://github.com/petros4ever/Softeware_Engineering-2024-25.git)**

The repository is the reference location for the application source code, diagrams, and supplementary project files.

## Project Scope and Notes

PR.I.M.A.L was developed as an academic software engineering project and prototype. The documentation describes a broader target system than the functionality demonstrated in the implementation screenshots. Features such as institutional student verification, a real external payment gateway, gift delivery, and complete offline synchronisation are part of the described requirements; their production-level integration is not established by the submitted project report.

The implementation section of the report identifies Python, Kivy, and KivyMD as the principal application technologies. It also notes that AI tools were used during code development.

---

*PR.I.M.A.L — Fueling Minds, Igniting Discovery.*
