# Token Sale Management

> **Developed by [Arslan Malik](https://github.com/arsalanmaalik461)**
> 📱 WhatsApp: [+92 300 8987448](https://wa.me/923008987448) · 🌐 Website: [arslanmalik.tech](https://arslanmalik.tech)

A complete ICO / token sale platform built with Laravel.

## 📌 About

Token Sale Management is a Laravel-based web application for running a token sale (ICO). It handles investor registration, KYC-style user accounts, token purchase flows with integrated payment gateways (Stripe, PayPal), referral QR codes, Google 2FA authentication, and an admin panel to manage stages, pricing, and transactions.

## ✨ Features

- Investor registration and account management
- Token purchase flow with Stripe and PayPal Checkout
- Google 2FA two-factor authentication
- Referral system with QR code generation
- Admin dashboard for managing sale stages, pricing, and transactions
- Email notifications (SendGrid, Mailgun, Postmark drivers)
- One-click web installer for easy deployment

## 🛠️ Tech Stack

- **Backend:** Laravel 9, PHP 8.1+
- **Frontend:** Blade templates, Laravel Mix, Bootstrap
- **Database:** MySQL (via PDO)
- **Payments:** Stripe, PayPal Checkout SDK
- **Auth/Security:** Google 2FA, Laravel Socialite, Laravel UI
- **Testing:** PHPUnit

## 🚀 Getting Started

```bash
git clone https://github.com/arsalanmaalik461/Token-Sale-Management.git
cd Token-Sale-Management
composer install
cp .env.example .env
php artisan key:generate
```

Configure your database and mail settings in `.env`, then:

```bash
php artisan migrate --seed
php artisan serve
```

Visit [http://localhost:8000](http://localhost:8000) in your browser.

## 📁 Project Structure

- `app/` — Application logic (models, controllers, helpers)
- `routes/` — Web and API routes
- `resources/` — Views, assets, language files
- `database/` — Migrations and seeders
- `documentation/` — Project documentation

## 📄 License

Developed and maintained by Arslan Malik.

<div align="center"><b>Developed with ❤️ by <a href="https://github.com/arsalanmaalik461">Arslan Malik</a></b><br>📱 <a href="https://wa.me/923008987448">WhatsApp</a> · 🌐 <a href="https://arslanmalik.tech">arslanmalik.tech</a></div>
