<div align="center">
    <img src="../assets/logo_transparent.png" alt="Fundyze's logo" width="150" height="150">
    <h1 align="center">Fundyze - Architecture</h1>
    <p align="center">
        Fundyze is an intelligent platform that helps analyze emerging companies, evaluate their potential, and identify promising investment opportunities.
    </p>
</div>

## 1. Principales Pages
### 1.1. Home (`/`)
- **Description**: The home page provides an overview of the Fundyze app
### 1.2. Dashboard (`/dashboard`)
- **Description**: Main user interface where users can view their analyses, recent activity, and quick access to features.
- **UI Layout**: 
    - Header with Logo, new analysis button, and user profile access.
    - A last analyzed section displaying recent analyses with filter options (type, date, ...).
### 1.3. New Analysis (`/new-analysis`)
- **Description**: Page where users can start a new investment analysis by uploading financial documents or entering asset details.
- **UI Layout**: 
    - Step-by-step wizard guiding users through the analysis setup process.
    - Options to upload documents, select analysis type (company, stock, crypto).
### 1.4. Analysis Results (`/analysis/:id`)
- **Description**: Displays the results of a specific analysis, including insights, recommendations, and visualizations.
- **Features**:
    - Interactive charts and graphs for data visualization.
    - Summary of key findings and recommendations.
    - Option to export results as PDF.
    - Possibility to share link results with others.
- **UI Layout**: 
    - Descriptive header with analysis title, date, sell/buy indicators, and action buttons (export, share).
    - Main content area with tabs for Overview, Financials, and Recommendations.

### 1.5. User Profile (`/profile`)
- **Description**: Allows users to view and edit their profile information, preferences, and settings.
- **Features**:
    - Edit personal information (name, email, password).
    - Manage language preferences.
    - Security settings (2FA, passkey management).
- **UI Layout**: 
    - Aside navigation for different settings sections (personal info, security).
    - Main content area displaying the selected settings section.
### 1.6. Login (`/login`)
- **Description**: Secure authentication page for existing users.
- **Features**:
    - Traditional login with email and password.
    - OAuth login with Google for quick access.
    - Passkey support for enhanced security.
- **UI Layout**: Large illustrative image on the left; login form on the right.

### 1.7. Signup (`/signup`)
- **Description**: Registration page for new users to create an account.
- **Features**:
    - Email and password registration.
    - Option to sign up with Google.
- **UI Layout**: Large illustrative image on the left; Step-by-step signup form on the right.
### 1.8. About (`/about`)
- **Description**: Information about Fundyze, its mission, and team.
### 1.9. Contact (`/contact`)
- **Description**: A page with a contact form for users to reach out for support or inquiries.