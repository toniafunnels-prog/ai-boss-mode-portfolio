# ai-boss-mode-portfolio
AI-powered SaaS platform for home service businesses. Built with React, FastAPI, Supabase, GoHighLevel and Stripe. Developed by Anthonia Dada | ToniaFunnels
# AI Boss Mode Platform

AI-powered SaaS platform for home service businesses. Lisa is an AI voice receptionist that answers calls 24/7.

## Tech Stack

- **Frontend:** React.js -- deployed on Vercel
- **Backend:** FastAPI (Python) -- deployed on Railway
- **Database:** Supabase (PostgreSQL)
- **CRM:** GoHighLevel (GHL)
- **Billing:** Stripe
- **Email:** SMTP via Gmail

## Project Structure

aibossmode-app/
├── frontend/ # React frontend
│ ├── src/
│ │ ├── pages/ # Login, AdminPanel, ProviderDashboard, ProviderSignup
│ │ ├── components/ # Sidebar, Navbar
│ │ └── config.js # API URL config
├── backend/ # FastAPI backend
│ ├── main.py # All API endpoints
│ ├── database.py # Supabase functions
│ ├── ghl.py # GoHighLevel API
│ ├── email_service.py # Email notifications
│ ├── stripe_service.py # Stripe billing
│ └── .env # Environment variables


## Environment Variables

### Backend (.env)

APP_NAME=AI Boss Mode
ENVIRONMENT=production
SECRET_KEY=your_secret_key
GHL_API_KEY=your_ghl_api_key
GHL_LOCATION_ID=your_location_id
GHL_AGENCY_API_KEY=your_agency_key
GHL_AGENCY_RELATIONSHIP_NUMBER=your_relationship_number
GHL_COMPANY_ID=your_company_id
GHL_SNAPSHOT_ID=your_snapshot_id
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
STRIPE_SECRET_KEY=your_stripe_key
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=aiboss@aibossmode.ai
SMTP_PASSWORD=your_app_password
FROM_EMAIL=aiboss@aibossmode.ai


### Frontend (.env)
REACT_APP_API_URL=https://your-railway-url.railway.app

## Admin Credentials

- **Leah:** leah@aibossmode.ai / aibossmode2026
- **Fred:** fred@aibossmode.ai / aibossmode2026

## Provider Default Password

All providers use `provider2026` as default password until they change it.

## Features

### Admin Panel
- View all providers
- Approve/Suspend/Reactivate providers
- GHL auto-deployment on approval
- Stripe customer creation on approval
- Automated email notifications
- Audit log with event tracking
- Real revenue calculation
- Search and filter providers

### Provider Dashboard
- View their own data only
- Edit business profile
- Change password
- Lisa configuration panel
- Call log
- Appointments
- Billing info
- Support contact

## Developer

**Anthonia Dada | ToniaFunnels**
AI Engineer
