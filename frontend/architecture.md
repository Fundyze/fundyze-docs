<div align="center">
    <img src="../assets/logo_transparent.png" alt="Fundyze's logo" width="150" height="150">
    <h1 align="center">Fundyze - Architecture</h1>
    <p align="center">
        Fundyze is an intelligent platform that helps analyze emerging companies, evaluate their potential, and identify promising investment opportunities.
    </p>
</div>

## 1. Main Pages

### 1.1. Public Home (`/`)
- **Description**: Landing page presenting Fundyze’s purpose and main features.
- **UI Layout**:
    - Hero section with tagline and call-to-action.
    - Short explanation of the platform’s value.
    - Links to About, Contact, and Signup.

### 1.2. User Home (`/home`)
- **Description**: Main user page after login, focused on discovery and research.
- **UI Layout**:
    - **Search bar** at the top to look up a specific company.
    - **Trending companies section**: ~10 cards with companies selected daily (precomputed).
    - **Trending cryptocurrencies section**: ~10 cards with cryptocurrencies selected daily (precomputed).
    - **Favorites section**: User’s favorited companies and cryptocurrencies.
    - Each card redirects to a detailed company report.

### 1.3. Company Report (`/company/:id`)
- **Description**: Dedicated page displaying a full analysis of a company.
- **Features**:
    - Key financial metrics.
    - Hierarchy and leadership (CEO, execs).
    - Products & services overview.
    - Recent trends and analysis summary.
    - Visual charts and graphs.

### 1.4. Cryptocurrency Report (`/crypto/:id`)
- **Description**: Dedicated page displaying a full analysis of a cryptocurrency.
- **Features**:
    - Key financial metrics.
    - Market trends and analysis summary.
    - Visual charts and graphs.

### 1.5. User Profile (`/profile`)
- **Description**: User account management.
- **Features**:
    - Edit personal info (name, email, password).
    - Manage preferences (language, notifications).
    - Security settings (2FA, passkeys).
- **UI Layout**:
    - Aside navigation for sections.
    - Main content with editable fields.

### 1.6. Login (`/login`)
- **Description**: Secure login for existing users.
- **Features**:
    - Email/password login.
    - Google OAuth.
    - Passkey support.
- **UI Layout**:
    - Large illustrative image on left.
    - Login form on right.

### 1.7. Signup (`/signup`)
- **Description**: Account creation page.
- **Features**:
    - Email/password registration.
    - Google signup option.
- **UI Layout**:
    - Large illustrative image on left.
    - Signup form on right.