HR Attendance & Payroll - Phase 1
===================================
This is a Phase 1 Vite + React prototype implementing Admin and Employee portals with:
- Admin: Dashboard, Employee Management, User Management, Company Settings, Working Periods, Leave Policies, Leave Approvals, Holiday List, Payroll & Payslips, Attendance export.
- Employee: My Dashboard, My Profile, Clock In/Out (captures geolocation), My Payslips (generate sample), Apply Leave.
- Payslip preview + client-side PDF & image download using html2canvas + jsPDF.
- Data stored in browser localStorage (for prototype). Replaceable by backend.

How to run:
1. unzip hr-attendance-vite.zip
2. cd hr-attendance-vite
3. npm install
4. npm run dev

Sample accounts:
- admin / admin123
- employee / emp123

Notes:
- Geolocation requires browser permission.
- Reverse-geocoding not included; location saved as lat/lon.
- For production use, implement backend (auth, DB) and secure the app.

