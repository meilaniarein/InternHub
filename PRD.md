# Product Requirement Document (PRD)

## InternHub — Student Internship Finder Web Application

**Product Name:** InternHub  
**Product Type:** Student Internship Finder Web Application  
**Document Owner:** Project Team  
**Status:** Updated Draft for Review  
**Target Users:** University Students  
**Repository:** https://github.com/meilaniarein/InternHub  
**Figma Design:** https://www.figma.com/design/283K7KBUuAI0ZfnS6iv9dF/INTERN-HUB?node-id=34-2&t=s6F7hiObt468E5yn-1

---

## 1. Executive Summary and Problem Statement

### 1.1 Context and Background

University students often face difficulties finding internship opportunities because information is distributed across multiple job portals, company websites, and social media platforms. Students need additional time to search for relevant positions and compare opportunities that match their academic background, skills, and career interests.

Managing internship opportunities can also be challenging. Students may forget to revisit interesting vacancies, lose track of application progress, or struggle to find useful resources to prepare for internship applications.

InternHub is a web application designed to help university students discover and organize internship opportunities through a centralized platform. The application provides internship listings, search and filtering features, vacancy details, saved internships, application-related pages, and internship preparation resources.

The current project focuses on the frontend implementation using HTML and JavaScript, supported by internship data stored in JSON. The application's actual functionality depends on the features implemented in the current project.

### 1.2 Problem Statement

University students need a more organized and efficient way to discover and manage internship opportunities because information is scattered across different platforms, and the application process can be difficult to organize.

InternHub aims to simplify the internship search experience by providing a centralized interface for discovering vacancies, reviewing internship details, organizing opportunities, accessing application-related pages, and finding preparation resources.

### 1.3 Product Objectives

1. Help students discover internship opportunities more efficiently.
2. Allow students to search and filter vacancies based on available criteria.
3. Help students review and organize interesting internship opportunities.
4. Provide application-related pages that support the internship application flow.
5. Provide accessible resources to support internship preparation.
6. Offer a consistent and easy-to-navigate user experience across the main pages.

---

## 2. Target Persona

### 2.1 Primary User: University Student

**Name:** Maya  
**Age:** 20 years old  
**Occupation:** University student  
**Primary Goal:** Find internship opportunities that match her interests, skills, and academic background.

**Core Need**

Maya wants to discover relevant internship opportunities without searching through multiple platforms. She also wants to organize vacancies and navigate the application process more easily.

**Pain Points**

- Internship vacancies are scattered across different websites and platforms.
- Finding opportunities that match her interests and qualifications takes time.
- Interesting vacancies are difficult to organize when saved in different places.
- Managing the steps involved in applying for internships can be confusing.
- Finding useful resources for preparing internship applications requires additional effort.

**Expected Benefits**

- Discover internship opportunities through one interface.
- Find relevant vacancies using search and filters.
- Review vacancy information before applying.
- Access pages for managing or reviewing application-related information.
- Access internship preparation resources more easily.

---

## 3. Product Overview and User Flow

### 3.1 Product Overview

InternHub supports the internship search journey, from discovering vacancies to reviewing application-related information and accessing career preparation resources.

The main pages and supporting pages include the following.

**1. Home / Branda**

Introduces InternHub and helps users navigate to the main internship discovery features.

**2. Field Internship**

Displays internship opportunities and provides search and filtering controls to help users find relevant vacancies.

**3. Detail Lowongan**

Displays detailed information about a selected internship so users can evaluate the opportunity before proceeding to the next action.

**4. Saved**

Provides a dedicated interface for reviewing internship opportunities saved by users, according to the functionality implemented in the application.

**5. Applications**

Provides an interface for reviewing internship application-related information and statuses supported by the current implementation.

**6. ApplicationStep1**

Provides the initial page of the internship application flow for entering the information required by the implemented form.

**7. ApplicationReview**

Provides a review step where users can check the information entered before proceeding, according to the implemented application flow.

**8. ApplicationSuccess**

Displays a confirmation page when the implemented application flow reaches its success state.

**9. ApplicationError**

Provides an error-state page for displaying application-related errors or unsuccessful outcomes, according to the implemented behavior.

**10. Resources**

Provides internship-related information and preparation resources to help students prepare for internship applications.

### 3.2 Expected User Flow

The primary internship discovery flow is:

1. The user opens the InternHub homepage.
2. The user navigates to the internship listings page.
3. The user searches or applies available filters to find relevant opportunities.
4. The user opens a vacancy detail page.
5. The user reviews the internship information.
6. The user saves the opportunity or proceeds to the available application action.
7. The user accesses the Saved page to review saved opportunities, if the saving functionality is available.
8. The user accesses the Applications page to review application-related information.

The application flow is designed to follow these steps:

1. The user opens the application form through the available application action.
2. The user enters the required information on ApplicationStep1.
3. The user proceeds to ApplicationReview to review the entered information.
4. The user continues through the available confirmation action.
5. The application flow displays ApplicationSuccess when the implemented success condition is reached.
6. ApplicationError is available for the error state supported by the implementation.

The Resources page provides a separate path for users who need additional preparation materials.

These flows describe the intended user experience. Their actual behavior must be verified against the current HTML files, JavaScript logic, and available data.

---

## 4. User Stories

### 4.1 Primary User Story

As a university student looking for an internship, I want to discover and filter internship opportunities in one platform so that I can find relevant opportunities more efficiently.

### 4.2 Supporting User Stories

1. As a student, I want to view detailed internship information so that I can evaluate whether an opportunity matches my needs.
2. As a student, I want to save interesting internship vacancies so that I can review them later.
3. As a student, I want to access application-related information so that I can better organize my internship search.
4. As a student, I want to enter and review application information before continuing so that I can check the details I have provided.
5. As a student, I want to receive clear feedback from the application flow so that I understand whether the process reached a success or error state.
6. As a student, I want to access internship preparation resources so that I can prepare more effectively.

---

## 5. Scope of the Minimum Viable Product (MVP)

The current MVP focuses on the frontend experience and the features implemented in the project.

### 5.1 In-Scope Features

**1. Internship Listings**

Display internship vacancies with essential information.

**2. Search and Filtering**

Provide search and filtering controls for finding relevant internship opportunities based on the available criteria.

**3. Internship Details**

Display detailed information about a selected vacancy.

**4. Saved Internships**

Provide a dedicated page for reviewing saved internship opportunities, according to the implemented saving mechanism.

**5. Application-Related Pages**

Provide pages for reviewing application-related information and statuses supported by the current implementation.

**6. Multi-Step Application Flow**

Provide the ApplicationStep1 and ApplicationReview pages to support the implemented application workflow.

**7. Application Feedback States**

Provide ApplicationSuccess and ApplicationError pages for the success and error states supported by the application.

**8. Internship Resources**

Provide internship preparation information and links to available resources.

**9. Page Navigation**

Allow users to navigate between the main discovery pages and supporting application pages.

**10. Internship Data**

Use the available internship data file, `data/internships.json`, as a source of vacancy information where supported by the implementation.

### 5.2 Implementation Boundaries

The presence of an HTML page does not necessarily mean that every feature is fully functional.

Search, filtering, saving, form validation, data transfer between application steps, success and error handling, and application status tracking must be tested against the actual JavaScript implementation.

Features that require authentication, persistent user-specific data, a backend, or external integrations are not considered complete unless those capabilities have been implemented and verified.

---

## 6. Out of Scope

The following capabilities are excluded from the initial MVP unless they are explicitly implemented as part of the project requirements:

1. Automatic submission of applications to external companies.
2. Direct messaging between students and recruiters.
3. AI-powered personalized internship recommendations.
4. Recruiter dashboards and employer account management.
5. Real-time synchronization with external job portals.
6. Automated interview scheduling with companies.
7. Advanced analytics and personalized career prediction.
8. Full account management and authentication backed by a server.
9. Permanent cloud-based storage of user-specific application records unless a backend is added.

---

## 7. Functional Requirements

### FR-01: Internship Listings

The system shall display a list of internship opportunities on the FieldInternship page.

Each listing shall present the available vacancy information and provide access to the corresponding detail page.

### FR-02: Search and Filtering

The system shall provide search and filtering controls on the internship listings page.

Users shall be able to interact with the available controls to find relevant internship opportunities. The actual search and filtering behavior must match the implemented functionality.

### FR-03: Internship Details

The system shall provide a DetailLowongan page that displays information about a selected internship.

Users shall be able to access the detail page from the internship listings.

### FR-04: Saved Internships

The system shall provide a save action for internship opportunities and a dedicated Saved page.

The page shall display saved opportunities according to the saving mechanism implemented in the current application. Persistent saving across sessions shall not be assumed unless verified.

### FR-05: Application Information

The system shall provide an Applications page for displaying the application-related information and statuses supported by the implementation.

The system shall not be described as providing complete application tracking unless the data and status-update mechanisms have been verified.

### FR-06: Application Form

The system shall provide an ApplicationStep1 page containing the fields required by the implemented application flow.

Required-field validation and progression to the next step shall follow the behavior supported by the current implementation.

### FR-07: Application Review

The system shall provide an ApplicationReview page where users can review the information entered during the application process.

The review page shall display the information supported by the current form implementation.

### FR-08: Application Success and Error States

The system shall provide ApplicationSuccess and ApplicationError pages for communicating the relevant outcomes of the application flow.

The conditions that lead to each page shall be consistent with the implemented application logic.

### FR-09: Internship Resources

The system shall provide a Resources page containing internship-related preparation information and links to available resources.

Links shall direct users to the intended destinations.

### FR-10: Navigation

The system shall provide navigation between the homepage, internship listings, internship details, saved internships, applications, application steps, and resources where applicable.

Navigation links shall point to the correct existing HTML files, using the actual filenames and capitalization in the repository.

### FR-11: Internship Data

The system shall use the available internship data in `data/internships.json` where the current implementation supports JSON-based vacancy data.

The displayed information should correspond to the available data and the structure expected by the application.

---

## 8. Acceptance Criteria

### AC-01: Internship Listings

- Users can open the FieldInternship page.
- Internship listings are displayed in a readable format.
- Vacancy information is consistent with the available data.
- Users can access the corresponding detail page from a listing.

### AC-02: Search and Filtering

- Users can interact with the search field.
- Users can interact with the available filtering controls.
- Search and filtering return the expected results according to the implemented logic.

### AC-03: Internship Details

- Users can open the DetailLowongan page from an internship listing.
- The detail page displays the available vacancy information.
- Users can navigate back to the internship discovery experience.

### AC-04: Saved Internships

- Users can interact with the save action where available.
- Users can open the Saved page.
- The page displays saved opportunities according to the implemented saving mechanism.
- Any persistence limitations are documented accurately.

### AC-05: Application Information

- Users can open the Applications page.
- Available application-related records and statuses are displayed clearly.
- The displayed information reflects the current implementation.

### AC-06: Application Form and Review

- Users can open ApplicationStep1 through the available navigation or application action.
- The form displays the required fields supported by the implementation.
- Users can proceed to ApplicationReview when the implemented validation conditions are satisfied.
- The review page displays the entered information correctly, where this behavior is implemented.

### AC-07: Application Outcome

- The success page can be reached through the implemented success flow.
- The error page is displayed through the implemented error flow, where applicable.
- Users receive clear feedback about the outcome.
- The pages do not imply that an application has been submitted to an external company unless that action is actually implemented.

### AC-08: Internship Resources

- Users can open the Resources page.
- Available resources are presented clearly.
- Resource links lead to the intended destinations.

### AC-09: Navigation

- Users can navigate between the main InternHub pages.
- Navigation links point to the correct HTML files.
- Links use the actual filenames and capitalization in the project.
- No broken internal links remain in the tested user flows.

### AC-10: Internship Data

- The application can access the internship data file where required by the implemented logic.
- Displayed vacancy information matches the available data.
- The application handles unavailable or invalid data appropriately where error handling is implemented.

---

## 9. Non-Functional Requirements

### NFR-01: Usability

The interface should be understandable and easy for university students to navigate.

### NFR-02: Consistency

Page layouts, navigation elements, and information presentation should remain consistent throughout the application.

### NFR-03: Accessibility

HTML elements should use appropriate semantic structure, meaningful link text, accessible form labels, and suitable alternative text for informative images where applicable.

### NFR-04: Maintainability

The project should use clearly organized files, consistent naming conventions, and understandable code to support future updates.

### NFR-05: Browser Compatibility

The web pages should be tested in a modern web browser to verify that the content, forms, data access, and navigation work as intended.

### NFR-06: Data Integrity

Vacancy and application-related information should be presented consistently with the available data and implemented logic.

### NFR-07: Error Handling

The application should provide appropriate feedback when an implemented operation cannot be completed or when the application flow reaches an error state.

---

## 10. Assumptions and Dependencies

1. University students are the primary users of InternHub.
2. Internship vacancy information is provided through the available data source or supplied content.
3. The initial product scope focuses on internship discovery and organization rather than complete recruitment management.
4. The project uses HTML and JavaScript for its frontend implementation, with JSON-based internship data where applicable.
5. Saved internships and application records may require browser storage or backend services for persistence, depending on the implementation.
6. Application-related pages represent the implemented frontend workflow and should not be assumed to submit applications to external companies.
7. The accuracy of the functional requirements depends on verification of the current HTML files, JavaScript behavior, and data structure.
8. External application submission and synchronization are excluded from the initial scope unless explicitly implemented.

---

## 11. Success Criteria

The initial InternHub MVP is considered to meet its intended objectives when:

1. Users can access the internship listings and view available vacancies.
2. Users can use the available search and filtering controls as intended.
3. Users can open internship detail pages from the listings.
4. Users can use the save action and access the Saved page according to the implemented behavior.
5. Users can access application-related information and displayed statuses.
6. Users can navigate through the implemented application form and review flow.
7. Users receive appropriate success or error feedback from the implemented application flow.
8. Users can access internship preparation resources and open the available links.
9. Users can navigate between the main application pages without incorrect page links.
10. The application displays vacancy information consistently with the available data.

These criteria should be confirmed through functional testing. The existence of a page alone does not demonstrate that all associated functionality is complete.

---

## 12. Future Enhancements

Potential improvements for future versions include:

1. Student registration and login.
2. Persistent user profiles and saved internship records.
3. Backend-based application record management.
4. Application status updates and notifications.
5. Personalized internship recommendations.
6. Integration with external internship platforms.
7. Additional career development and interview preparation resources.
8. Improved form validation and user feedback.
9. Expanded usability and cross-browser testing.

---

## 13. Project References

**GitHub Repository:**  
https://github.com/meilaniarein/InternHub

**Figma Design (Module 5):**  
https://www.figma.com/design/283K7KBUuAI0ZfnS6iv9dF/INTERN-HUB?node-id=34-2&t=s6F7hiObt468E5yn-1

**Implementation Reference:**  
The current HTML pages, JavaScript files, and `data/internships.json` in the project repository serve as the reference for verifying the implemented functionality.

---

## 14. Document Maintenance

This PRD should be updated when the product scope, user flow, page structure, or implemented functionality changes.

Before marking a requirement as complete, verify it against the current implementation and the corresponding acceptance criteria. Planned functionality, implemented functionality, and tested functionality should be distinguished clearly.
