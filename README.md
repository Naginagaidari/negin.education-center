# negin.education-center
# آپلود کد به GitHub git init git add . git commit -m "Initial commit - Neghin Center Website" git branch -M main git remote add origin https://github.com/YOUR_USERNAME/neghin-center.git git push -u origin main
 ساختار فایل‌ها

neghin-center inborder-radius: 8px;
    padding: 20px;
    display: flex;
    gap: 15px;
    box-shadow: var(--shadow);
}

body.dark-mode .why-item {
    background: var(--dark-bg);
}

.why-icon {
    font-size: 24px;
    flex-shrink: 0;
}

/* Services Grid */
.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.service-card {
    background: white;
    border-radius: 8px;
    padding: 30px;
    box-shadow: var(--shadow);
}

body.dark-mode .service-card {
    background: var(--dark-bg);
}

.service-icon {
    font-size: 48px;
    margin-bottom: 15px;
}

.service-card h3 {
    color: var(--primary-color);
    margin-bottom: 15px;
}

.service-list {
    list-style: none;
    line-height: 2;
}

.service-list li:before {
    content: "✓ ";
    color: var(--primary-color);
    font-weight: bold;
    margin-right: 10px;
}

/* Process Timeline */
.process-timeline {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    margin-bottom: 30px;
}

.process-step {
    background: white;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: var(--shadow);
}

body.dark-mode .process-step {
    background: var(--dark-bg);
}

.process-number {
    font-size: 32px;
    font-weight: bold;
    color: var(--primary-color);
    margin-bottom: 10px;
}

/* Requirements Grid */
.requirements-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.requirement-box {
    background: white;
    border-radius: 8px;
    padding: 30px;
    box-shadow: var(--shadow);
}

body.dark-mode .requirement-box {
    background: var(--dark-bg);
}

.requirement-box h3 {
    color: var(--primary-color);
    margin-bottom: 15px;
}

.requirement-box ul {
    list-style: none;
    line-height: 2;
}

.requirement-box ul li:before {
    content: "• ";
    color: var(--primary-color);
    font-weight: bold;
    margin-right: 10px;
}

/* FAQ Section */
.faq-items {
    display: grid;
    gap: 20px;
}

.faq-item {
    background: white;
    border-left: 4px solid var(--primary-color);
    border-radius: 4px;
    padding: 20px;
    box-shadow: var(--shadow);
}

body.dark-mode .faq-item {
    background: var(--dark-bg);
}

.faq-item h3 {
    color: var(--primary-color);
    margin-bottom: 10px;
}

/* Support Grid */
.support-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.support-card {
    background: white;
    border-radius: 8px;
    padding: 30px;
    text-align: center;
    box-shadow: var(--shadow);
}

body.dark-mode .support-card {
    background: var(--dark-bg);
}

.support-icon {
    font-size: 48px;
    margin-bottom: 15px;
}

.support-card h3 {
    color: var(--primary-color);
    margin-bottom: 15px;
}

/* Usage Items */
.usage-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.usage-item {
    background: white;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: var(--shadow);
}

body.dark-mode .usage-item {
    background: var(--dark-bg);
}

.usage-item h3 {
    color: var(--primary-color);
    margin-bottom: 10px;
}

/* Partners List */
.partners-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
}

.partner-item {
    background: white;
    border-radius: 8px;
    padding: 15px;
    text-align: center;
    box-shadow: var(--shadow);
}

body.dark-mode .partner-item {
    background: var(--dark-bg);
}

/* Contact Grid */
.contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
}

.contact-info,
.contact-form {
    background: white;
    border-radius: 8px;
    padding: 30px;
    box-shadow: var(--shadow);
}

body.dark-mode .contact-info,
body.dark-mode .contact-form {
    background: var(--dark-bg);
}

.contact-item {
    margin-bottom: 25px;
    padding-bottom: 25px;
    border-bottom: 1px solid var(--border-color);
}

.contact-item:last-child {
    border-bottom: none;
}

.contact-item h3 {
    color: var(--primary-color);
    margin-bottom: 10px;
}

.contact-item a {
    color: var(--secondary-color);
    text-decoration: none;
}

.contact-item a:hover {
    text-decoration: underline;
}

.social-btn {
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    margin-right: 10px;
    margin-top: 10px;
    transition: all 0.3s;
}

.social-btn:hover {
    background: var(--secondary-color);
}

/* Form */
.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 8px;
    color: var(--text-dark);
    font-weight: 500;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid var(--border-color);
    border-radius: 5px;
    font-size: 16px;
    background: white;
    color: var(--text-dark);
    transition: all 0.3s;
}

body.dark-mode .form-group input,
body.dark-mode .form-group select,
body.dark-mode .form-group textarea {
    background: #2a2a2a;
    color: var(--text-light);
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(46, 204, 113, 0.1);
}

.form-group textarea {
    resize: vertical;
}

/* Map Section */
.map-section {
    padding: 60px 20px;
    background: var(--light-bg);
}

.map-placeholder {
    background: white;
    border-radius: 8px;
    padding: 100px 20px;
    text-align: center;
    box-shadow: var(--shadow);
    min-height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 48px;
}

body.dark-mode .map-placeholder {
    background: var(--dark-bg);
}

/* CTA Section */
.cta-section {
    padding: 60px 20px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    text-align: center;
}

.cta-section h2 {
    font-size: 36px;
    margin-bottom: 15px;
}

.cta-section p {
    font-size: 18px;
    margin-bottom: 30px;
}

/* About Home Section */
.about-home {
    padding: 60px 20px;
}

.about-home h2 {
    text-align: center;
    font-size: 36px;
    margin-bottom: 30px;
}

.about-home p {
    font-size: 18px;
    line-height: 1.8;
    margin-bottom: 20px;
    text-align: justify;
}

.action-buttons {
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-top: 30px;
    flex-wrap: wrap;
}

/* WhatsApp Button */
.whatsapp-btn {
    position: fixed;
    bottom: 20px;
    left: 20px;
    width: 60px;
    height: 60px;
    background: #25d366;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    transition: all 0.3s;
    z-index: 99;
}

.whatsapp-btn:hover {
    transform: scale(1.1);
    background: #20ba5a;
}

.whatsapp-btn svg {
    width: 30px;
    height: 30px;
}

/* Footer */
.footer {
    background: var(--text-dark);
    color: var(--text-light);
    padding: 40px 20px;
    margin-top: 60px;
}

body.dark-mode .footer {
    background: #0a0a0a;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-bottom: 30px;
}

.footer-section h4 {
    margin-bottom: 15px;
    color: var(--primary-color);
}

.footer-section p {
    line-height: 1.8;
    opacity: 0.9;
}

.footer-section a {
    color: var(--primary-color);
    text-decoration: none;
}

.footer-section a:hover {
    text-decoration: underline;
}

.footer-bottom {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid rgba(255,255,255,0.1);
}

/* Animations */
@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Responsive */
@media (max-width: 768px) {
    .hamburger {
        display: block;
    }

    .nav-menu {
        position: absolute;
        top: 100%;
        right: 0;
        background: white;
        flex-direction: column;
        width: 100%;
        text-align: center;
        display: none;
        gap: 0;
        box-shadow: var(--shadow);
    }

    body.dark-mode .nav-menu {
        background: var(--dark-bg);
    }

    .nav-menu.active {
        display: flex;
    }

    .nav-menu a {
        padding: 15px;
        border-bottom: 1px solid var(--border-color);
    }

    .hero-content h2 {
        font-size: 32px;
    }

    .pillars-grid,
    .stats-grid,
    .features-grid,
    .coverage-grid {
        grid-template-columns: 1fr;
    }

    .accessibility-toolbar {
        left: auto;
        right: 20px;
        flex-direction: row;
        gap: 5px;
    }

    .accessibility-toolbar button {
        width: 40px;
        height: 40px;
        font-size: 14px;
    }

    .header-content {
        flex-direction: column;
        gap: 15px;
    }

    .navbar {
        width: 100%;
    }
}

/* Focus styles for keyboard navigation */
a:focus,
button:focus {
    outline: 3px solid var(--primary-color);
    outline-offset: 2px;
}


⚙️ فایل: js/main.js

// Dark Mode Toggle
const darkModeToggle = document.getElementById('darkModeToggle');
const body = document.body;

// Load saved preference
if (localStorage.getItem('darkMode') === 'enabled') {
    body.classList.add('dark-mode');
    darkModeToggle.textContent = '☀️';
}

darkModeToggle.addEventListener('click', () => {
    body.classList.toggle('dark-mode');
    if (body.classList.contains('dark-mode')) {
        localStorage.setItem('darkMode', 'enabled');
        darkModeToggle.textContent = '☀️';
    } else {
        localStorage.setItem('darkMode', 'disabled');
        darkModeToggle.textContent = '🌙';
    }
});

// Font Size Control
const fontSizeUp = document.getElementById('fontSizeUp');
const fontSizeDown = document.getElementById('fontSizeDown');
const resetButton = document.getElementById('resetButton');
let currentFontSize = parseInt(localStorage.getItem('fontSize')) || 16;

function updateFontSize() {
    document.documentElement.style.setProperty('--font-size', currentFontSize + 'px');
    localStorage.setItem('fontSize', currentFontSize);
}

fontSizeUp.addEventListener('click', () => {
    if (currentFontSize < 24) {
        currentFontSize += 2;
        updateFontSize();
    }
});

fontSizeDown.addEventListener('click', () => {
    if (currentFontSize > 12) {
        currentFontSize -= 2;
        updateFontSize();
    }
});

resetButton.addEventListener('click', () => {
    currentFontSize = 16;
    body.classList.remove('dark-mode');
    localStorage.clear();
    updateFontSize();
    darkModeToggle.textContent = '🌙';
});

updateFontSize();

// Mobile Menu Toggle
const hamburger = document.getElementById('hamburger');
const navMenu = document.getElementById('navMenu');

if (hamburger) {
    hamburger.addEventListener('click', () => {
        navMenu.classList.toggle('active');
    });

    // Close menu when a link is clicked
    document.querySelectorAll('.nav-menu a').forEach(link => {
        link.addEventListener('click', () => {
            navMenu.classList.remove('active');
        });
    });
}

// Active Link Highlight
function setActiveLink() {
    const currentLocation = location.pathname.split('/').pop() || 'index.html';
    document.querySelectorAll('.nav-menu a').forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href') === currentLocation) {
            link.classList.add('active');
        }
    });
}

setActiveLink();

// Contact Form
const contactForm = document.getElementById('contactForm');
if (contactForm) {
    contactForm.addEventListener('submit', function(e) {
        e.preventDefault();
        
        const name = document.getElementById('name').value;
        const email = document.getElementById('email').value;
        const subject = document.getElementById('subject').value;
        const message = document.getElementById('message').value;
        
        // Validate form
        if (!name || !email || !subject || !message) {
            alert('لطفاً تمام فیلدهای ضروری را پر کنید');
            return;
        }
        
        // Create WhatsApp message
        const whatsappMessage = `سلام نگین%0A%0Aنام: ${name}%0Aایمیل: ${email}%0Aموضوع: ${subject}%0A%0Aپیام:%0A${message}`;
        
        // Open WhatsApp
        window.open(`https://wa.me/932483380?text=${whatsappMessage}`, '_blank');
        
        // Reset form
        contactForm.reset();
        alert('پیام شما به طور موفق ارسال شد. تشکر!');
    });
}

// Smooth scroll for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({ behavior: 'smooth' });
        }
    });
});


📄 فایل: _config.yml

# Site settings
title: مرکز نگین
description: مرکز آموزشی و توانبخشی کودکان دارای معلولیت
url: "https://qhaidari.github.io/neghin-center"
baseurl: "/neghin-center"

# Theme
theme: jekyll-theme-cayman
markdown: kramdown

# Plugins
plugins:
  - jekyll-feed
  - jekyll-seo-tag

# Exclude
exclude:
  - Gemfile
  - Gemfile.lock
  - README.md
  - node_modules


📄 فایل: README.md

# 🌟 مرکز نگین - Neghin Center

مرکز آموزشی و توانبخشی کودکان دارای معلولیت با ابزارهای هوش مصنوعی

## 🎯 درباره پروژه

مرکز نگین یک پلتفرم آنلاین، آموزشی، درمانی و تفریحی کاملاً رایگان است که برای حمایت و توانمندسازی کودکان دارای معلولیت در افغانستان طراحی شده است.

## ✨ ویژگی‌های اصلی

- 🌐 **وبسایت کامل و واکنش‌گرا**: سازگار با تمام دستگاه‌ها
- 🌙 **حالت شب و روشن**: برای راحتی چشم
- ♿ **دسترسی‌پذیری کامل**: برای تمام کاربران
- 📱 **منوی تعاملی**: آسان و سریع
- 🎓 **بانک دانش جامع**: اطلاعات کامل درباره معلولیت‌ها
- 🤖 **ابزارهای AI**: ۵۰+ ابزار برای کمک
- 📋 **روتین‌های روزانه**: برنامه‌های آماده
- 🎨 **ابزارهای بصری**: PECS و نمایشگرهای تصویری

## 📁 ساختار فایل‌ها


neghin-center/
├── index.html # صفحه اصلی
├── about.html # درباره ما
├── services.html # خدمات
├── knowledge-bank.html # بانک دانش
├── admission.html # راهنمای پذیرش
├── support.html # حمایت از ما
├── contact.html # تماس
├── css/
│ └── style.css # استایل‌های کامل
├── js/
│ └── main.js # JavaScript
└── assets/
└── logo.png # لوگوی مرکز



## 🚀 شروع کار

### 1. Clone مخزن
```bash
git clone https://github.com/qhaidari/neghin-center.git
cd neghin-center

2. آپلود برای GitHub Pages

git add .
git commit -m "Initial commit"
git push origin main

3. فعال کردن GitHub Pages


رفتن به Settings > Pages

انتخاب main branch

ذخیره تنظیمات


🎨 تخصیص‌پذیری

تغییر رنگ‌ها

فایل css/style.css را باز کنید و متغیرها را تنظیم کنید:


:root {
    --primary-color: #2ecc71;
    --secondary-color: #3498db;
    /* ... */
}

اضافه کردن لوگو


فایل لوگو را در assets/ قرار دهید

نام فایل را در HTML تغییر دهید


📱 صفحات


index.html - صفحه اصلی با آمار و ویژگی‌ها

about.html - داستان نگین و بنیان‌گذاران

services.html - خدمات و پوشش معلولیت‌ها

knowledge-bank.html - بانک دانش جامع

admission.html - راهنمای پذیرش

support.html - راه‌های حمایت

contact.html - فرم تماس و اطلاعات تماس


♿ دسترسی‌پذیری


✅ حالت شب/روشن

✅ تغییر اندازه فونت

✅ ناوبری با صفحه‌کلید

✅ پشتیبانی از نرم‌افزارهای خواننده صفحه

✅ تضاد رنگی بهینه


📞 تماس


📍 کابل، پروژه وزیر آباد، سرک ۳۷

📞 ۰۷۸۶۸۳۸۰۰۲

✉️ negineducationcenter@gmail.com

💬 واتس‌اپ


📝 لیسانس

این پروژه تحت لیسانس MIT منتشر شده است.


🙏 تشکر

تشکر از تمام کسانی که در ایجاد این پروژه کمک کردند.



ساخته‌شده با ❤️ برای کودکان دارای معلولیت



---

## 📄 فایل: .gitignore


OS

.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db


IDE

.vscode/
.idea/
*.swp
*.swo


م!
