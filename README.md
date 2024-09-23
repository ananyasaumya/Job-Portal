# Job Portal (MERN Stack)

This is a full-stack job application built using the MERN Stack, MUI (Material UI), Datagrid, cookies, and more. It’s part of a YouTube series designed to teach how to build a full-stack app step by step.

### How to use the app:
1. Clone this repository.
2. In the root of the "bonus" folder, create a `.env` file with the following variables:
   - `PORT=9000`
   - `DATABASE=YOUR_MONGO_URL`
   - `JWT_SECRET=fidbfbFCDSm1558`
   - `NODE_ENV=development` (for development) or `NODE_ENV=production` (for deployment).
3. Run `npm install` in the root of the "bonus" folder.
4. Navigate to the "frontend" folder inside "bonus" and run `npm install`.


## Features:
- **Software Architecture**: Uses the MVC pattern.
- **HOC (Higher Order Component)**.
- **Dark & Light Theme** with Material UI.
- **Admin and User Dashboards**: Includes pagination, Datagrid, CSV download, etc.
- **Sidebar**: Open/close functionality for the dashboard.
- **Admin Functionality**: Create jobs, categories, and more.
- **Dashboard Analytics**.
- **Responsive Design** using Material UI.
- **User Dashboard**: View job history.
- **Authentication**: Log in and register forms with Formik and Yup validation.
- **Modern Authentication**: JWT and cookie-based system.
- **Job Search and Filters**: Filter by category and location.
- **Job Application**: Apply to jobs if the user is logged in.
- **Notifications**: Toast notifications for user actions.
