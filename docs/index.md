# WearFamily

An e-commerce platform for family matching outfits

## About the Application

WearFamily is a modern e-commerce platform built with Laravel, designed to provide a seamless shopping experience for families looking for matching outfits. The application features a responsive design, secure authentication, and a comprehensive product catalog.

### User Features

* User registration and authentication
* Product browsing by categories (Sets, Swimsuits, Pajamas, Dresses)
* Shopping cart functionality
* Order management
* Responsive design for all devices
* Newsletter subscription
* Social media integration

### Admin Features

* Product management
* Category management
* Order processing
* User management
* Newsletter management
* Social media integration management

### Technical Features

* Laravel 8.x
* PHP 8.1
* MySQL Database
* Docker for deployment
* Bootstrap for responsive design
* JavaScript for interactive features

## Get Started

To run the application locally, clone the repository and follow these steps:

1. **Prerequisites**
   * PHP 8.1 or higher
   * Composer
   * MySQL
   * Node.js and NPM

2. **Installation Steps**
   ```bash
   # Clone the repository
   git clone [repository-url]

   # Install PHP dependencies
   composer install

   # Install NPM dependencies
   npm install

   # Create environment file
   cp .env.example .env

   # Generate application key
   php artisan key:generate

   # Run database migrations
   php artisan migrate

   # Start the development server
   php artisan serve
   ```

3. **Environment Configuration**
   Configure your `.env` file with the following:
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=wearfamily
   DB_USERNAME=root
   DB_PASSWORD=
   ```

## Live Demo

Visit our live website: [WearFamily](https://fsd03-webdev1-wearfamily-jsd-1.onrender.com/)

## Project Structure

```
WearFamily/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Middleware/
│   ├── Models/
│   └── Providers/
├── config/
├── database/
│   └── migrations/
├── public/
│   ├── css/
│   ├── js/
│   └── images/
├── resources/
│   └── views/
└── routes/
```

## Features in Detail

### User Authentication
* Secure login and registration system
* Password hashing and encryption
* Session management
* User profile management

### Product Management
* Categorized product listings
* Product search functionality
* Product filtering
* Shopping cart system

### Newsletter System
* Email subscription
* Privacy policy compliance
* Unsubscribe functionality

### Social Media Integration
* Social media sharing
* Social login options
* Social media feed integration

## Deployment

The application is deployed on Render:
* **Service Name**: FSD03_WebDev1_WearFamily_JSD-1
* **Runtime**: Docker
* **Region**: Oregon
* **URL**: https://fsd03-webdev1-wearfamily-jsd-1.onrender.com/

### Deployment Process
1. Push changes to the main branch
2. Render automatically builds and deploys the application
3. Database migrations run automatically
4. Environment variables are configured in Render dashboard

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, please reach out through:
* Website contact form
* Social media channels
* GitHub issues 