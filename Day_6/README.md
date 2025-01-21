# Marketplace_Builder_Hackathon_2025 

## Overview  
This project involves building a fully functional, responsive, and scalable marketplace application. Below is a detailed summary of the development process, organized by day, outlining all activities and progress made.

---

## Table of Contents  
- [Day 1: Defining Business Goals](#day-1-defining-business-goals)  
- [Day 2: Technical Requirements and System Architecture](#day-2-technical-requirements-and-system-architecture)  
- [Day 3: API Integration and Data Population](#day-3-api-integration-and-data-population)  
- [Day 4: Building Core Features](#day-4-building-core-features)  
- [Day 5: Testing and Refinement](#day-5-testing-and-refinement)  
- [Day 6: Deployment Preparation and Staging Setup](#day-6-deployment-preparation-and-staging-setup)  
- [Folder Structure](#folder-structure)  
- [Technologies Used](#technologies-used)  

---

## Day 1: Defining Business Goals  

### Goals Defined:  
1. **Problem Solved:** The marketplace aims to provide a seamless platform for connecting sellers and buyers.  
2. **Target Audience:** Small to medium businesses and individual consumers.  
3. **Products/Services Offered:** Various categories of goods and services tailored to users’ needs.  
4. **Unique Selling Points:** Speed, affordability, and extensive customization options.  

### Data Schema:  
- Drafted the initial data schema to define how products, categories, users, and orders are structured in the application.

---

## Day 2: Technical Requirements and System Architecture  

### Deliverables:  
1. **Technical Requirements:**  
   - Serverless architecture using Vercel for hosting.  
   - Next.js for the frontend and Sanity CMS for data management.  

2. **System Architecture:**  
   - Developed a system architecture diagram outlining the flow between:  
     - Frontend  
     - Backend  
     - API interactions  
     - Database (Sanity CMS)  

3. **API Requirements:**  
   - Drafted API specifications for retrieving and managing data, including endpoints for products, categories, and user data.  

4. **Schema Draft:**  
   - Finalized schema designs for Sanity CMS to structure data effectively.  

---

## Day 3: API Integration and Data Population  

### Steps Completed:  
1. **Utility Functions:**  
   - Created utility functions to fetch and handle API data efficiently.  

2. **Rendering Data:**  
   - Integrated dynamic data into Next.js components to display:  
     - Product listings  
     - Categories  

3. **API Testing:**  
   - Used Postman and browser developer tools to test endpoints and validate data consistency.  

4. **Sanity CMS Data Population:**  
   - Imported data into Sanity CMS using:  
     - Provided APIs  
     - External sources  
     - Manual uploads  

---

## Day 4: Building Core Features  

### Features Implemented:  
1. **Product Listing Page:**  
   - Displays dynamic data fetched from APIs or Sanity CMS.  

2. **Product Detail Pages:**  
   - Used dynamic routing for individual product pages.  

3. **Category Filters:**  
   - Advanced filters for segmenting products dynamically.  

4. **Search Bar:**  
   - Functional search bar to filter products by name or tags.  

5. **Additional Features:**  
   - Pagination for better navigation.  
   - Display of related products on detail pages.  

6. **Styling and Responsiveness:**  
   - Ensured components are responsive and visually appealing across devices.  

7. **Modular Components:**  
   - Built reusable components for scalability.  

---

## Day 5: Testing and Refinement  

### Deliverables:  
1. **Functional Testing:**  
   - Conducted testing using Postman, Lighthouse, and Cypress.  

2. **Testing Report:**  
   - Submitted a CSV report with detailed testing outcomes, including:  
     - Test Case ID  
     - Description  
     - Steps  
     - Expected and Actual Results  
     - Status (Passed/Failed)  

3. **Optimization and Error Handling:**  
   - Refined backend integration.  
   - Enhanced error handling mechanisms.  

---

## Day 6: Deployment Preparation and Staging Setup  

### Steps Completed:  

1. **Deployment Strategy Planning:**  
   - Selected Vercel for staging deployment.  

2. **Environment Variable Configuration:**  
   - Secured sensitive data using `.env` files and uploaded them to Vercel’s dashboard.  

3. **Staging Environment Setup:**  
   - Deployed the application to a staging environment for production-like testing.  

4. **Staging Environment Testing:**  
   - Conducted:  
     - **Functional Testing:** Verified workflows like product listing, filtering, and cart operations.  
     - **Performance Testing:** Analyzed speed and responsiveness using Lighthouse and GTmetrix.  
     - **Security Testing:** Ensured HTTPS usage and secure handling of sensitive data.  

5. **Documentation Updates:**  
   - Created this `README.md` summarizing all activities.  
   - Uploaded test reports, performance metrics, and deployment instructions to the GitHub repository.  

 

 