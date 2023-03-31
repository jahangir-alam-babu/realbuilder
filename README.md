
# RealBuilder

This Laravel-based real estate website provides a comprehensive platform for buying, selling, and renting properties. Users can easily search for properties by location, price, and other criteria, view detailed property listings with photos and descriptions, and contact agents or owners directly. The website also offers a property management system, allowing owners to list their properties and manage tenant applications and payments. Built with Laravel's robust framework, the website offers secure user authentication and a responsive design for optimal performance on any device. With a sleek and intuitive interface, this real estate website is a powerful tool for connecting buyers, sellers, and renters in the ever-evolving real estate market.





## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Features

### Admin can handle:
- Facilities
- Cities
- Categories
- Properties
- Reviews
- Users
- Change Password
- Site settings
### User can:
- Surf properties
- Handle their profile
- Change Password
- Save and review properties if logged in
- The project is a college project and nothing serious is expected to happen.


## Run Locally

Clone the project:

```bash
  git clone 
```

Go to the project directory:

```bash
  cd realbuilder
```

Install the project dependencies using Composer:

```bash
  composer install
```

Create a copy of the .env.example file and rename it to .env:

```bash
  cp .env.example .env
```

Generate an application key:

```bash
  php artisan key:generate
```

Set up your database by editing the .env file and entering your database credentials.

Run database migrations:

```bash
  php artisan migrate
```

That's it! You've successfully installed a Laravel project from Git. You can now run the project locally by starting the development server using the command:

```bash
  php artisan serve
```

If you are using laragon then you can ignore artisan serve


## User Login

Email: admin@demo.com
Password: 12345678


## Author

- [@jahangir-alam-babu](https://www.github.com/jahangir-alam-babu)

