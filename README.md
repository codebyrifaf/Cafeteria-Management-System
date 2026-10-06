**```markdown
# Cafeteria Management System

A desktop-based cafeteria management system built with C# and Windows Forms. The application manages student registration, authentication, meal selection, cafeteria orders, menu management, and administrative order monitoring.

## Features

- Student registration and login
- Residential and non-residential student management
- Meal selection by day and meal type
- Breakfast, lunch, and dinner ordering
- Platter selection
- Automatic meal price calculation
- Residential order management
- Non-residential order and payment management
- Admin dashboard
- Order viewing and clearing
- Cafeteria menu management
- Microsoft Access database integration

## Meal Pricing

| Meal | Price |
|------|------:|
| Breakfast | 50 |
| Lunch | 100 |
| Dinner | 120 |

## Technology Stack

- C#
- .NET Framework 4.7.2
- Windows Forms
- Microsoft Access
- ADO.NET / OleDb
- Guna UI

## Database

The application uses a local Microsoft Access database:

```text
cms.accdb
```

Main database tables:

- `st_table` — Student information and authentication
- `order_table` — Residential student orders
- `nonres_order_table` — Non-residential orders and payment information

## Project Structure

```text
Cafeteria Management System/
├── Admin_Form.cs
├── dashboard.cs
├── firstForm.cs
├── Form1.cs
├── Form2.cs
├── Login.cs
├── Nonres_Dash.cs
├── Order.cs
├── student.cs
├── management.cs
├── Program.cs
├── App.config
└── cms.accdb
```

## Installation

### Requirements

- Windows
- Visual Studio
- .NET Framework 4.7.2
- Microsoft Access Database Engine
- Guna UI

### Run the Project

Clone the repository:

```bash
git clone https://github.com/codebyrifaf/Cafeteria-Management-System.git
```

Open the solution in Visual Studio:

```text
Cafeteria Management System.sln
```

Make sure `cms.accdb` is available in the application's working directory, then build and run the project.

## Future Improvements

- Secure password hashing
- Dedicated admin authentication
- Persistent menu management
- Online payment integration
- Order status tracking
- Sales and analytics dashboard
- Centralized database support
- Web and mobile versions

## Author

**Rifaf Rahman**

GitHub: https://github.com/codebyrifaf
```

