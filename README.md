## Laravel Ecommerce System Features

- Sell Simple or Variable Products
- Built-in Order Tracking page
- Unlimted Categories & Sub-Categories
- Filter Products (eg by size, color, brands, categories, etc.)
- Optional Wishlist
- Gallery lightbox for product images
- Product Image Zoom
- Color, Label, and Image Swatches
- Product Quick View
- Frequently Bought Together
- Advanced Typography
- Single checkout page
- Support many payment methods: PayPal, Stripe, Paystack, Razorpay, Mollie…
- Multi-currency
- RTL support.

- Page, blog, menu, contact, newsletter, slider… modules are provided with the use of components to avoid boilerplate code.
- Powerful media system, also support Amazon S3, DigitalOcean Spaces
- SEO & sitemap support: access sitemap.xml to see more.
- Google Analytics: display analytics data in admin panel.
- Translation tool: easy to translate front theme and admin panel to your language.
- Beautiful theme is ready to use.
- Powerful Permission System: Manage user, team, role by permissions. Easy to manage user by permissions.
- Admin template comes with color schemes to match your taste.
- Fully Responsive: Compatible with all screen resolutions.
- Coding Standard: All code follow coding standards PSR-2 and best practices.

## Screenshots

# Frontend
![alt tag](https://i.imgur.com/Lvm0yy4.jpg)


## Installation (Local)

*Download or clone the repository in your system.*

```
git clone --depth 1 https://github.com/rkdharecha/ecommerce-laravel.git
```

*Go to ecommerce-laravel folder and open terminal then follow below steps.*

*Install Composer:*
```
composer Install
```

*Make a copy of .env.example file to .env:*
```
cp .env.example .env
```

*Change APP_URL in .env to APP_URL=http://localhost:8000*

*Import Database from project root folder named (Database.sql)*

*Set the database credentials:*

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database_name
DB_USERNAME=root
DB_PASSWORD=
```

*Then Generate Application Key:*

```
php artisan key:generate
```

*Clear cache by below command:*
```
php artisan optimize
```

*Run php artisan serve. Open http://localhost:8000, you should see the homepage & Go to /admin to access to admin panel.*

*Admin Login*
```
username = botble 
password = 159357
```

*Customer Login*
```
username = john.smith@botble.com
password = 12345678
```

