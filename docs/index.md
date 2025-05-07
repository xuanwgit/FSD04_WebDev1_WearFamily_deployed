<link rel="stylesheet" href="assets/css/custom.css">

<!-- Header Section -->
<div class="header">
  <h1>WearFamily</h1>
  <p class="subtitle">An e-commerce platform for family matching outfits</p>
</div>

<div class="about-section">
  <h2>About the Application</h2>
  <p>
    WearFamily is a modern e-commerce platform built with Laravel, designed to provide a seamless shopping experience for families looking for matching outfits. The application features a responsive design, secure authentication, and a comprehensive product catalog.
  </p>
</div>

<table class="features-table">
  <tr>
    <td>
      <h3>User Features</h3>
      <ul>
        <li>User registration and authentication</li>
        <li>Product browsing by categories (Sets, Swimsuits, Pajamas, Dresses)</li>
        <li>Shopping cart functionality</li>
        <li>Order management</li>
        <li>Responsive design for all devices</li>
        <li>Newsletter subscription</li>
        <li>Social media integration</li>
      </ul>
    </td>
    <td>
      <h3>Admin Features</h3>
      <ul>
        <li>Product management</li>
        <li>Category management</li>
        <li>Order processing</li>
        <li>User management</li>
        <li>Newsletter management</li>
        <li>Social media integration management</li>
      </ul>
    </td>
    <td>
      <h3>Technical Features</h3>
      <ul>
        <li>Laravel 8.x</li>
        <li>PHP 8.1</li>
        <li>MySQL Database</li>
        <li>Docker for deployment</li>
        <li>Bootstrap for responsive design</li>
        <li>JavaScript for interactive features</li>
      </ul>
    </td>
  </tr>
</table>

<div class="get-started-section">
  <h2>Get Started</h2>
  <p>To run the application locally, clone the repository and follow these steps:</p>
  <div class="steps">
    <div class="step">
      <h4>Prerequisites</h4>
      <ul>
        <li>PHP 8.1 or higher</li>
        <li>Composer</li>
        <li>MySQL</li>
        <li>Node.js and NPM</li>
      </ul>
    </div>
    <div class="step">
      <h4>Installation Steps</h4>
      <pre><code># Clone the repository
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
</code></pre>
    </div>
    <div class="step">
      <h4>Environment Configuration</h4>
      <pre><code>DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=wearfamily
DB_USERNAME=root
DB_PASSWORD=
</code></pre>
    </div>
  </div>
</div>

<div class="live-demo-section">
  <h2>Live Demo</h2>
  <a href="https://fsd03-webdev1-wearfamily-jsd-1.onrender.com/" target="_blank">WearFamily Live Site</a>
</div>

<div class="project-structure-section">
  <h2>Project Structure</h2>
  <pre><code>WearFamily/
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
</code></pre>
</div>

<div class="features-detail-section">
  <h2>Features in Detail</h2>
  <h4>User Authentication</h4>
  <ul>
    <li>Secure login and registration system</li>
    <li>Password hashing and encryption</li>
    <li>Session management</li>
    <li>User profile management</li>
  </ul>
  <h4>Product Management</h4>
  <ul>
    <li>Categorized product listings</li>
    <li>Product search functionality</li>
    <li>Product filtering</li>
    <li>Shopping cart system</li>
  </ul>
  <h4>Newsletter System</h4>
  <ul>
    <li>Email subscription</li>
    <li>Privacy policy compliance</li>
    <li>Unsubscribe functionality</li>
  </ul>
  <h4>Social Media Integration</h4>
  <ul>
    <li>Social media sharing</li>
    <li>Social login options</li>
    <li>Social media feed integration</li>
  </ul>
</div>

<div class="deployment-section">
  <h2>Deployment</h2>
  <ul>
    <li><b>Service Name:</b> FSD03_WebDev1_WearFamily_JSD-1</li>
    <li><b>Runtime:</b> Docker</li>
    <li><b>Region:</b> Oregon</li>
    <li><b>URL:</b> <a href="https://fsd03-webdev1-wearfamily-jsd-1.onrender.com/" target="_blank">https://fsd03-webdev1-wearfamily-jsd-1.onrender.com/</a></li>
  </ul>
  <h4>Deployment Process</h4>
  <ol>
    <li>Push changes to the main branch</li>
    <li>Render automatically builds and deploys the application</li>
    <li>Database migrations run automatically</li>
    <li>Environment variables are configured in Render dashboard</li>
  </ol>
</div>

<div class="contributing-section">
  <h2>Contributing</h2>
  <ol>
    <li>Fork the repository</li>
    <li>Create your feature branch</li>
    <li>Commit your changes</li>
    <li>Push to the branch</li>
    <li>Create a new Pull Request</li>
  </ol>
</div>

<div class="license-section">
  <h2>License</h2>
  <p>This project is licensed under the MIT License.</p>
</div>

<div class="contact-section">
  <h2>Contact</h2>
  <p>For any inquiries, please reach out through:</p>
  <ul>
    <li>Website contact form</li>
    <li>Social media channels</li>
    <li>GitHub issues</li>
  </ul>
</div> 