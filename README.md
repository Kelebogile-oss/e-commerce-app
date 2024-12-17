# e-commerce-app

Build a proof-of-concept e-commerce store using Angular, .NET, and Stripe for payment processing.

## Features

### Developer Environment Setup
- Setting up the developer environment.
- Creating a multi-project .NET Core application using the dotnet CLI.

### Frontend Development
- Creating a client-side front-end Angular UI for the store using the Angular CLI.
- Building a great-looking UI using Angular Material and Tailwind.
- Using Angular modules to create lazy-loaded routes.
- Making reusable form components using Angular Reactive Forms.

### Backend Development
- Implementing the Repository, Unit of Work, and Specification patterns in .NET Core.
- Using multiple DbContext as context boundaries.
- Utilizing ASP.NET Identity for login and registration.

### Core Features
- Paging, Sorting, Searching, and Filtering.
- Using Redis to store the shopping basket.
- Creating orders from the shopping basket.
- Accepting payments via Stripe, including support for EU standards for 3D secure payments.

### Additional Features
- Role-based authentication.
- SignalR for real-time communication.
- Publishing the application to Azure.
- Many more features.

## Tools Used
- **Frontend:** Angular, Angular Material, Tailwind CSS
- **Backend:** .NET Core, ASP.NET Identity
- **Database:** Redis (for shopping basket storage)
- **Payment Gateway:** Stripe
- **IDE:** Visual Studio Code

## Getting Started

### Prerequisites
- Install Node.js
- Install Angular CLI
- Install .NET SDK
- Install Redis
- Create a Stripe account for payment processing
- Set up an Azure account for deployment (optional)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Kelebogile-oss/e-commerce-app.git
   cd e-commerce-app
   ```
2. Set up the backend:
   - Navigate to the backend folder and configure the `appsettings.json` file with your database and Stripe credentials.
   - Run the following command to start the backend server:
     ```bash
     dotnet run
     ```
3. Set up the frontend:
   - Navigate to the frontend folder.
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the Angular development server:
     ```bash
     ng serve
     ```

### Usage
- Visit `http://localhost:4200` to access the application.
- Use the admin panel to manage roles and perform administrative tasks.

## Contributing
Contributions are welcome! Please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries, feel free to reach out via [GitHub](https://github.com/Kelebogile-oss/e-commerce-app).

