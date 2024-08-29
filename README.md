# IB Coursework Evaluation Web Application

## Objective

This is a web application for evaluating International Baccalaureate (IB) coursework using
Next.js 14, TailwindCSS, Zustand, and Shadcn UI components. The application should closely
resemble the provided "ZuAi" interface design.


## Tech Stack

- **Next.js 14**: Framework for building the application.
- **TailwindCSS**: For styling and responsive layouts.
- **Zustand**: State management for handling global states.
- **Shadcn UI**: Component library for user interface elements.

## Key Features

### 1. File Upload

- Drag-and-drop support for PDF files.
- Manual file upload option.
- Display file size limit (e.g., "Limit 25 MB per file").
- Store uploaded files using browser local storage.

### 2. Local Storage Implementation

- Save uploaded files and their metadata locally.
- Ensure data persistence across page reloads.
- Efficient retrieval of stored files and associated data.

### 3. Coursework Details Form

- Dropdowns for selecting "Coursework Type" and "Subject".
- Text input for entering the essay title.
- Store form data locally and link it with the uploaded file.

### 4. Evaluation Display

- Use of dummy data for all evaluation criteria.
- Overall score displayed with a circular progress indicator.
- Detailed breakdown of scores by criteria (A, B, C).
- Display evaluation date and allow local storage and retrieval of results.

### 5. Coursework List

- List previously uploaded coursework with relevant details (title, subject, word count, etc.).
- Data is fetched from local storage.

### 6. Explore Coursework Section

- Tabbed interface to switch between different coursework categories.
- Grid layout to display coursework examples visually.

## Bonus Features

### 1. Animations

-  Smooth transitions between states
-  Micro-interactions for enhanced user feedback

### 2. User Gratification
-  Congratulatory messages for good scores
-  Encouraging feedback for areas of improvement

### 3. Accessibility

- Keyboard navigation support

### 4. Advanced Local Storage Features

- Mock API integration for simulating server-side persistence

## About This Repository

This repository contains a web application designed to evaluate International Baccalaureate (IB) coursework. The application is built with modern web technologies and follows a clean, user-friendly interface inspired by the provided "ZuAi" design.


## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/vaibhav0006/ib-coursework-evaluation.git

   ```

2. Install dependencies:

   ```bash
   npm install

   ```

3. Running the Development Server

   ```bash
   npm run dev

   ```

4. Building for Production

   ```bash
   npm run build

   ```
## Contact
If you have any questions or need further assistance, you can contact the project maintainer at vaibhavrajput0006@gmail.com