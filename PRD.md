# Product Requirement Document (PRD)

**Product Name:** InternHub  
**Product Type:** Student Internship Finder Web Application  
**Author / PM Role:** Technical Lead PM  
**Status:** Draft for Review  
**Target User:** University Students

## 1. Executive Summary & Problem Statement

### 1.1 Context & Background

University students often face difficulties finding internship opportunities because information is distributed across multiple job portals, company websites, and social media platforms. Students must spend additional time searching for relevant positions and comparing opportunities that match their academic background, skills, and career interests.

Managing internship opportunities can also be challenging. Students may forget to revisit interesting vacancies, lose track of application progress, or struggle to find useful resources for preparing their applications.

InternHub is a web application designed to help university students discover and organize internship opportunities through a centralized platform. The application provides internship listings, search and filtering features, detailed vacancy information, saved internships, application tracking, and internship preparation resources.

### 1.2 Problem Statement

University students need a more organized and efficient way to discover and manage internship opportunities because information is scattered across different platforms and application progress can be difficult to track.

InternHub aims to simplify the internship search process by bringing essential internship discovery and organization features into one platform.

### 1.3 Product Objectives

1. Help students discover internship opportunities more efficiently.
2. Allow students to narrow down vacancies using search and filtering features.
3. Help students organize interesting internship opportunities in one place.
4. Provide a centralized view of internship application records and statuses.
5. Provide accessible resources to support internship preparation.

## 2. Target Persona

### 2.1 Primary User: University Student

**Name:** Maya  
**Age:** 20 years old  
**Occupation:** Second-year university student  
**Primary Goal:** Find an internship that matches her interests, skills, and academic background.

**Core Need:** Maya wants to find relevant internship opportunities without searching through multiple platforms and wants to organize her internship search more easily.

**Pain Points:**
- Internship vacancies are scattered across different websites and platforms.
- Finding opportunities that match her interests and qualifications takes time.
- Interesting vacancies are difficult to organize when they are saved in different places.
- Keeping track of internship applications and their progress can be confusing.
- Finding useful resources for preparing internship applications requires additional effort.

**Expected Benefits:**
- Discover internship opportunities in one platform.
- Find relevant vacancies using search and filters.
- Save interesting internships for later review.
- Review application records and statuses in one place.
- Access internship preparation resources more easily.

## 3. Context: Design & User Flow

### 3.1 Product Overview

InternHub is designed to support the internship search journey, from discovering vacancies to organizing applications and accessing career preparation resources.

The main pages of InternHub are:

**1. Home / Branda**

Provides an introduction to InternHub and helps users navigate to the main internship discovery features.

**2. Field Internship**

Displays internship opportunities and provides search and filtering options to help users find relevant vacancies.

**3. Detail Lowongan**

Displays detailed information about a selected internship, allowing users to review the opportunity before deciding on their next action.

**4. Saved**

Provides a centralized list of internship opportunities that users have saved for future reference.

**5. Applications**

Provides a view of internship application records and their statuses, helping users organize their application process.

**6. Resources**

Provides internship-related information and learning resources to support users during their internship preparation.

### 3.2 Expected User Flow

1. The user opens the InternHub homepage.
2. The user navigates to the internship listings page.
3. The user searches or applies available filters to find relevant opportunities.
4. The user opens a vacancy detail page to review the opportunity.
5. The user saves an interesting vacancy for later reference.
6. The user reviews saved opportunities and organizes application records.
7. The user accesses the Resources page when additional preparation materials are needed.

The flow describes the intended product experience. Features requiring persistent data storage, authentication, or external integrations must be evaluated separately if they are not yet implemented.

## 4. User Story

**Primary User Story**

- As a university student looking for an internship,
- I want to discover and filter internship opportunities in one platform,
- So that I can find relevant opportunities more efficiently and organize my internship search.

**Supporting User Stories**

1. As a student, I want to view detailed internship information so that I can evaluate whether an opportunity matches my needs.
2. As a student, I want to save interesting internship vacancies so that I can review them later.
3. As a student, I want to review my internship application records and statuses so that I can keep track of my application progress.
4. As a student, I want to access internship preparation resources so that I can better prepare for internship applications.

## 5. In-Scope (MVP)

The Minimum Viable Product (MVP) includes the following proposed capabilities:

1. **Internship Listings:** Display internship vacancies with essential information.
2. **Search & Filters:** Allow users to search and filter internship opportunities using the available criteria.
3. **Internship Details:** Display detailed information about a selected vacancy.
4. **Saved Internships:** Allow users to save and review interesting internship opportunities.
5. **Application Tracking:** Display internship application records and their associated statuses.
6. **Internship Resources:** Provide access to internship-related preparation materials.
7. **Page Navigation:** Allow users to navigate between the main InternHub pages.

The implementation of each capability must be verified against the current HTML files and any available application logic.

## 6. Out of Scope

The following capabilities are excluded from the initial MVP unless they are explicitly added to the project requirements:

1. Automatic submission of internship applications to external companies.
2. Direct messaging between students and recruiters.
3. AI-powered personalized internship recommendations.
4. Recruiter dashboards and employer account management.
5. Real-time synchronization with external job portals.
6. Automated interview scheduling with companies.
7. Advanced analytics and personalized career prediction.

## 7. Functional Requirements

### FR-01: Internship Listings

The system shall display a list of internship opportunities with relevant information, such as position title, company name, location, and other available vacancy details.

### FR-02: Search and Filtering

The system shall provide search and filtering controls to help users narrow down internship opportunities based on the criteria supported by the application.

### FR-03: Internship Details

The system shall provide a detail page for a selected internship containing the available vacancy information.

### FR-04: Saved Internships

The system shall provide a dedicated page for viewing saved internship opportunities. If persistent saving is required, the application must support an appropriate data storage mechanism.

### FR-05: Application Tracking

The system shall provide an application overview containing available internship application records and their statuses. Automatic status updates must not be assumed unless the relevant functionality is implemented.

### FR-06: Internship Resources

The system shall provide access to internship-related resources that help students prepare for applications.

### FR-07: Navigation

The system shall provide navigation links between the homepage, internship listings, internship details, saved internships, applications, and resources pages.

## 8. Acceptance Criteria

### AC-01: Internship Listings
- Users can access the internship listings page.
- Available internship opportunities are displayed in a readable format.
- Each listing provides a way to access its details.

### AC-02: Search and Filtering
- Users can enter a search query.
- Users can interact with the available filtering controls.
- The displayed results reflect the search and filtering criteria when the functionality is implemented.

### AC-03: Internship Details
- Users can open a selected internship's detail page.
- The page displays the available information for that internship.
- Users can navigate back to the internship discovery experience.

### AC-04: Saved Internships
- Users can access the Saved page.
- Saved internship records are displayed when available.
- Persistence across page reloads must be verified if persistent saving is part of the implementation.

### AC-05: Application Tracking
- Users can access the Applications page.
- Available application records and statuses are displayed clearly.
- Status changes are only considered supported if the application provides the relevant functionality.

### AC-06: Internship Resources
- Users can access the Resources page.
- Available resources are presented clearly.
- Users can open the relevant resource when a destination or content link is provided.

### AC-07: Navigation
- Users can navigate between the main application pages using the available navigation elements.
- Navigation links point to the correct existing pages.
- Page links work with the actual filenames and their capitalization.

## 9. Non-Functional Requirements

### NFR-01: Usability
The interface should be understandable and easy for university students to navigate.

### NFR-02: Consistency
Page layouts, navigation elements, and information presentation should remain consistent throughout the application.

### NFR-03: Accessibility
HTML elements should use appropriate semantic structure, meaningful link text, and accessible labels where applicable.

### NFR-04: Maintainability
The project should use clearly organized files and consistent naming conventions to make future updates easier.

### NFR-05: Compatibility
The web pages should be tested in a modern web browser to verify that their content and navigation work as intended.

## 10. Assumptions & Dependencies

1. University students are the primary users of InternHub.
2. Internship vacancy information must be available from a defined data source or supplied content.
3. The initial product scope focuses on internship discovery and organization rather than direct recruitment management.
4. Persistent saved internships and application records may require backend services or browser-based storage, depending on the chosen implementation.
5. External application submission and synchronization are not included in the initial scope.

## 11. Success Criteria

The initial product can be evaluated using the following criteria:

1. Users can access and navigate all main InternHub pages.
2. Users can discover internship listings and open vacancy details.
3. Users can use the available search and filtering controls.
4. Users can access saved internship and application overview pages.
5. Users can access internship preparation resources.
6. The implemented features behave consistently with their documented requirements.

Quantitative performance targets should be defined after usability testing or user feedback is collected.

## 12. Future Enhancements

Potential improvements for future versions include:

1. Student registration and login.
2. Persistent user profiles and saved internship records.
3. Application status updates and notifications.
4. Personalized internship recommendations.
5. Integration with external internship platforms.
6. Additional career development and interview preparation resources.
