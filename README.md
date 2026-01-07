# WeaveDesk — E-Commerce Admin Dashboard (SSR)

# Project Overview
**WeaveDesk** is a server-side rendered (SSR) e-commerce administrative dashboard designed for efficient product and admin management in a real-world system.  
The application leverages **Next.js SSR** to deliver fast page loads, improved SEO, and a secure, scalable admin interface.
Administrators can manage products through advanced multi-step forms, visualize pricing and stock metrics using interactive charts, securely upload images, and onboard new admins with controlled access.

## Objective
To design and develop a **server-side rendered admin dashboard** that enables seamless management of e-commerce products while ensuring performance, security, and scalability.

# Key Features
- **Server-Side Rendering (SSR)** using Next.js for fast performance and SEO
- **Authentication & Authorization**
  - Secure admin login & logout
  - Admin-only access to dashboard features
- **Complete Product Management (CRUD)**
  - Create, view, edit, and delete products
  - Real-time UI updates after data changes
- **Multi-Step Product Creation Form**
  - Step 1: Basic Information
  - Step 2: Product Details
  - Step 3: Pricing (auto-calculates final price based on discount)
  - Step 4: Image Upload
- **Data Visualization**
  - Price chart (bar graph)
  - Stock chart (bar graph)
- **Secure Image Upload**
  - Cloud-based image storage
- **Admin Onboarding**
  - Add new admins via email
  - Restricted visibility (admin-only feature)
- **Clean Admin UI**
  - Sidebar navigation for Products, Charts, Add Product, Add Admin, and Logout


# Tech Stack
- Frontend & Backend: Next.js (SSR)
- Data Fetching: React Query
- Form Validation: Zod
- Charts: Recharts
- Image Storage: Cloudinary 
- Database: MongoDB
- Deployment: Vercel 

#Live Deployment
🔗 Live Application:https://admin-panel-ruddy-six.vercel.app/login
> The deployed application is publicly accessible and fully functional.
> Dummy Credentials-
> Email id- admin@dashboard.com
> Password- admin123

#Setup Instructions (Local)
1. Clone the repository:
   ```bash
   git clone https://github.com/KrutiSurati/final-admin-panel.git
2. Install dependencies:
    ```bash
    npm install
3. Create a .env.local file:
   ```bash
   MONGODB_URI=mongodb+srv://suratikr_db_user:Kruti@surati12@cluster1.iaen5rq.mongodb.net/ecommerce
4. Run the development server:
   ```bash
   npm run dev




