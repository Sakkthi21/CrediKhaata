# CrediKhaata - Loan Ledger UI

## Overview
CrediKhaata is a responsive React.js web application designed for small shopkeepers to manage customer credit and track transactions. It provides a user-friendly dashboard for managing loans, recording repayments, and monitoring outstanding balances.

## Features
- User Authentication (Login/Signup)
- Customer Management Dashboard
- Transaction History Tracking
- Loan Management System
- Repayment Recording
- Overdue Loan Highlighting
- Dark Mode Support
- Mobile Responsive Design
- PDF Statement Generation
- Real-time Toast Notifications

## Tech Stack
- **Frontend**: React.js (v18+)
- **State Management**: Context API/useReducer
- **Routing**: React Router DOM
- **Form Handling**: React Hook Form
- **Styling**: Tailwind CSS
- **PDF Generation**: jsPDF
- **Notifications**: React Toastify

## Setup and Installation
1. Clone the repository
```bash
git clone [repository-url]
cd credi-khaata
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
- Create a `.env` file in the root directory
- Copy contents from `.env.template`
- Update with your configuration values

4. Start development server
```bash
npm run dev
```

## Environment Variables
```env
VITE_APP_API_URL=your_api_url
```

## Core Components
- **Login/SignUp**: User authentication interface
- **Dashboard**: Main customer overview
- **CustomerDetail**: Individual customer transaction history
- **AddCustomerForm**: New customer registration
- **AddLoanForm**: New loan creation
- **RepaymentForm**: Payment recording

## State Management
The application uses Context API/useReducer for managing:
- User authentication state
- Customer data
- Transaction records
- Theme preferences

## Form Validation
- Client-side validation using React Hook Form
- Required field checks
- Amount and date validations
- Real-time error feedback

## Mobile Responsiveness
- Mobile-first design approach
- Responsive layout using Tailwind CSS
- Optimized for various screen sizes

## Dark Mode
- Toggle between light/dark themes
- Persistent theme preference
- CSS variables for theme colors

## Future Improvements
1. **Enhanced Analytics**:
   - Customer payment patterns
   - Default risk assessment

2. **Export Features**:
   - Bulk statement generation
   - Data export in multiple formats

3. **Advanced Notifications**:
   - Payment reminders
   - Overdue alerts
