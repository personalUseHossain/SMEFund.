# [Business Funding Platform](https://smefund.co.uk)
![Dashboard Preview](https://raw.githubusercontent.com/personalUseHossain/SMEFund./refs/heads/main/SMEFund.png)

The **Business Funding Platform** is a digital solution designed to streamline the process of managing business investments, funding applications, profit repayment, and KYC verification. It features dedicated modules for business users and platform administrators to ensure a smooth, secure, and transparent funding experience.

## Live Demo
Check out the live version of the app: [Business Funding Platform](https://smefund.co.uk)

## Features

### 👤 User Module (Business Owners)

#### 1. Signup & Login
- Register using **email and password**
- **OTP email verification** is required for account activation

#### 2. Dashboard & Account Setup
- 3-step onboarding with a progress tracker:
  - **KYC Verification** (via Veriff or similar service)
  - **Business Information Submission**
  - **Business Type Selection** (with dynamic document upload)
- Users can register and manage **two separate businesses** under one account
- KYC is required **once per user**, but business info is submitted **per business**

#### 3. Bank & Payment Setup
- Enter **bank account details**
- Optionally provide **mobile financial services** info (e.g., Payoneer)
- **Manual transfer handling** by the admin

#### 4. Funding Application
- Businesses can apply for funding (e.g., 500,000 BDT)
- Admin can **approve, reject, or modify** the requested amount

#### 5. Profit Repayment
- Monthly profit repayments required
- Two available payment gateways:
  - **Stripe** (International)
  - **SSLCommerz** (Local)

#### 6. Funding & Profit Dashboard
- Visual analytics (line/bar graphs) showing:
  - Total funds received
  - Total profit paid
  - Pending dues

#### 7. Business Performance Score
- Admin assigns a hidden score based on:
  - On-time payments
  - Document accuracy
  - Overall behavior

> Note: The score is **not visible to users**, only to admins.

---

### 🛠️ Admin Module (Platform Management)

#### 1. KYC & Business Info Verification
- View, approve, or reject:
  - KYC documents
  - Business information submissions

#### 2. Funding Management
- Manage all funding requests
- Modify approved amounts
- Assign **funder IDs** (no external funder portal)
- Set **profit/return ratio** for each funding

#### 3. Profit Schedule Management
- Set custom **monthly due dates** per business
- View upcoming and pending payment schedules

#### 4. Score Tracking
- Monitor business performance using:
  - Timely payments
  - Application completeness
  - Manual evaluations

#### 5. System & User Management
- View all users and registered businesses
- Filter and manage:
  - KYC/document status
  - Profit history
  - Funding records

## Technologies Used
- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Firebase Auth (OTP Email Verification)
- **Payment Gateways**: Stripe, SSLCommerz
- **Hosting**: Vercel

---

