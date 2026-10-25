# InternHub

InternHub is a web application designed to help university students discover, explore, and organize internship opportunities in one platform.

## 1. Background

University students often struggle to find internship opportunities because vacancy information is distributed across multiple job portals, company websites, and social media platforms. InternHub aims to make the internship search process more organized and efficient by providing a centralized platform for exploring and managing internship information.

## 2. Objectives

- Help students discover internship opportunities.
- Provide search and filtering features to find relevant vacancies.
- Allow students to save interesting internship opportunities.
- Help students review internship application records and statuses.
- Provide resources to support internship preparation.

## 3. Main Features

- **Home:** Introduces the InternHub platform.
- **Internship Listings:** Displays available internship opportunities with search and filtering controls.
- **Internship Details:** Provides information about selected internship vacancies.
- **Saved Internships:** Provides access to saved internship opportunities.
- **Applications:** Displays internship application records and their statuses.
- **Application Process:** Provides pages for the internship application workflow.
- **Resources:** Provides internship preparation materials and related links.

Feature availability and behavior depend on the current implementation.

## 4. Technologies

- HTML5
- JavaScript
- JSON for internship data
- Visual Studio Code
- Git and GitHub

## 5. Project Structure

- `Branda.html` — Home page.
- `FieldInternship.html` — Internship listings, search, and filtering.
- `DetailLowongan.html` — Internship vacancy details.
- `Saved.html` — Saved internship opportunities.
- `Applications.html` — Internship application overview.
- `ApplicationStep1.html` — Application process page.
- `ApplicationStep2.html` — Application process page.
- `ApplicationReview.html` — Application review page.
- `ApplicationSuccess.html` — Application success page.
- `ApplicationError.html` — Application error page.
- `Resources.html` — Internship preparation resources.
- `PRD.md` — Product Requirements Document.
- `prompt-log.md` — Documentation of AI prompts and manual improvements.
- `assets/` — Project images, icons, and other supporting assets.
- `data/` — Project data directory, if used.

The exact file locations should match the current repository structure.

## 6. How to Run

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Open `Branda.html` in a browser, or use a local development server.
4. Navigate through the available pages.
5. Test the search, filtering, saved internship, and application features.

Some features may depend on JavaScript, local data files, or the environment used to run the application.

## 7. Design

The interface and user flow were designed in Figma.

Figma prototype:  
https://www.figma.com/design/283K7KBUuAI0ZfnS6iv9dF/INTERN-HUB?node-id=34-2&t=s6F7hiObt468E5yn-1

## 8. Contributions

- Designed the InternHub interface and user flow in Figma.
- Developed HTML pages based on the project design.
- Organized image and icon assets.
- Implemented and reviewed page navigation.
- Worked on internship data display, search, and filtering.
- Reviewed HTML validity and page behavior.
- Prepared the Product Requirements Document.
- Documented AI prompts and manual improvements.

## 9. AI Usage and Manual Improvements

AI assistance was used during the development process. The prompts used and relevant development notes are documented in `prompt-log.md`.

AI-generated output was reviewed and adjusted manually to improve HTML structure, page navigation, asset paths, content consistency, and alignment with project requirements.

The final implementation should be evaluated based on the actual code and tested behavior.

## 10. Data Source and Form Behavior

Internship listing data is managed using JSON files within the project.

The application uses the data and functionality implemented in the current project version. Form submission, saved internship persistence, and application status storage depend on the implemented mechanisms.

No external backend or persistent database is claimed in this documentation unless one is explicitly configured and verified.

## 11. Feature Verification

The following areas should be checked during browser testing:

- **Internship Listings:** Verify that internship vacancies appear on `FieldInternship.html`.
- **Search and Filters:** Verify that search and filtering controls return the expected results.
- **Internship Details:** Verify that selecting a vacancy opens the correct details.
- **Saved Internships:** Verify the save interaction and the contents of `Saved.html`.
- **Applications:** Verify the application records and displayed statuses.
- **Application Process:** Test the available application steps, review page, and success or error pages.
- **Resources:** Verify that `Resources.html` and its available links can be accessed.
- **Page Navigation:** Verify that menus, links, and buttons navigate to the intended pages.

Testing results should reflect the behavior observed in the current version of the application. Browser testing alone does not establish that data is stored permanently on a backend.

## 12. Live Website

**Live URL:** cute-hummingbird-70ec10.netlify.app 

The deployed website should be tested through its public URL to verify page navigation, internship data display, search and filtering, and form behavior.

## 13. Project Repository

GitHub repository:  
https://github.com/meilaniarein/InternHub
