ESAHub Africa Website (v1)

Official website for ESAHub Africa, built with a lightweight, cost-effective stack suitable for shared hosting environments.
This version (v1) includes a public-facing website, blog system, and a simple admin panel for content management.

🔥 Project Goals

Establish a strong online presence for ESAHub Africa

Showcase programs, impact, and initiatives

Support blogging and announcements

Provide a simple admin interface for non-technical staff

Keep hosting and maintenance costs low

Enable future scalability when funding grows

🧱 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Hosting: Shared Hosting (cPanel compatible)

No heavy frameworks. No plugins. Clean and fast.

📂 Project Structure
/public
│
├── /assets
│   ├── /css
│   ├── /js
│   └── /images
│
├── /includes
│   ├── header.php
│   ├── footer.php
│   ├── navbar.php
│   └── config.php
│
├── /blog
│   ├── index.php        # Blog listing
│   └── post.php         # Single blog post
│
├── /admin
│   ├── login.php
│   ├── dashboard.php
│   ├── create-post.php
│   ├── edit-post.php
│   └── logout.php
│
├── index.php
├── about.php
├── programs.php
├── impact.php
├── contact.php
└── .htaccess

✨ Core Features (v1)
🌐 Public Website

Homepage with mission & CTA

About ESAHub Africa

Programs & initiatives (e.g. HDC)

Impact highlights

Contact form

📝 Blog System

Admin-created blog posts

Blog listing page

Single blog post view

SEO-friendly URLs

Publish/unpublish posts

🔐 Admin Panel

Secure admin login

Create, edit, delete blog posts

Upload featured images

Manage post visibility

Simple dashboard UI

🔐 Admin Panel Access
/admin/login.php


Authentication handled via PHP sessions.
Passwords stored using secure hashing.

🗄️ Database Tables (v1)
admins

id

username

password_hash

created_at

posts

id

title

slug

content

featured_image

status (draft/published)

created_at

updated_at

🎨 Branding

Primary brand colors extracted from ESAHub logo:

Navy Blue: #0B1F3B

Teal Blue: #1AA6C8

Light Teal: #5CCAE6

Dark Text: #2E2E2E

White: #FFFFFF

Colors are managed using CSS variables for consistency.

🚀 Deployment

Upload files to shared hosting via cPanel or FTP

Create MySQL database and user

Import SQL schema

Update database credentials in:

/includes/config.php


Access site via domain

🔒 Security Notes

Prepared statements for database queries

Password hashing (password_hash)

Session-based authentication

Basic input validation & sanitization

📈 Future Enhancements (Post v1)

Donation system

Program registration forms

Gallery & media manager

Role-based admin access

Analytics dashboard

Migration to Laravel / Headless CMS (when funded)

👤 Maintainer

Umar Abdulmalik
Program Partner & Technical Lead
ESAHub Africa

📄 License

This project is proprietary and intended for ESAHub Africa.
Reuse or redistribution requires permission.
