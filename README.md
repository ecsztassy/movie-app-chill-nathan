# CHILL - Movie Streaming Landing Page

CHILL adalah website streaming film sederhana yang dibuat sebagai project frontend menggunakan HTML, CSS, dan JavaScript dasar.  

Project ini menampilkan tampilan seperti platform streaming modern dengan halaman login, register, dan beranda yang responsif untuk desktop maupun mobile.

---

## Preview Project

CHILL memiliki 3 halaman utama:

- Login Page  
- Register Page  
- Home Page  

Konsep desain terinspirasi dari platform streaming seperti Netflix dengan tampilan modern dan clean.

---

## Features

### 1. Login Page
- Form login username dan password  
- Forgot password button  
- Login with Google button  
- Redirect ke halaman home  

### 2. Register Page
- Form registrasi akun baru  
- Confirm password  
- Register with Google button  
- Redirect ke halaman login  

### 3. Home Page
- Navbar navigasi  
- Hero banner movie utama  
- Section movie list horizontal  
- Continue Watching section  
- Trending Movies section  
- Top Rating Movies section  
- New Release section  

### 4. Interactive UI
- Dropdown profile menu  
  - Profil Saya  
  - Ubah Premium  
  - Logout  

- Mobile footer dropdown  
  - Genre  
  - Bantuan  

### 5. Responsive Design
Tampilan sudah menyesuaikan ukuran layar:

- Desktop  
- Tablet  
- Mobile  

---

## Technologies Used

Project ini dibuat menggunakan:

- HTML5  
- CSS3  
- JavaScript (basic interaction only)

Tidak menggunakan framework tambahan seperti:

- Bootstrap  
- React  
- Vue  
- Tailwind  

---

## Folder Structure

```bash
CHILL/

│── index.html
│── register.html
│── home.html

│
├── assets/
│   ├── logo.png
│   ├── bg-login.jpg
│   ├── bg-register.jpg
│   ├── banner.jpg
│   ├── profile.jpg
│   └── movie-images...

```

---

## UI Components

### Authentication
- Login form  
- Register form  
- Google authentication button  

### Navigation
- Navbar menu  
- Profile dropdown  

### Homepage
- Hero banner  
- Movie cards  
- Movie carousel section  
- Footer navigation  

---

## Responsive Layout

Website telah dioptimasi untuk:

### Desktop
- Full navigation menu  
- Large hero banner  
- Full footer layout  

### Mobile
- Compact navbar  
- Smaller movie cards  
- Mobile dropdown footer  

---

## JavaScript Functions

Project menggunakan JavaScript ringan untuk interaksi sederhana.

### Profile Dropdown

```javascript
function toggleDropdown() {
    document
        .getElementById("dropdown-menu")
        .classList.toggle("show");
}
```

### Mobile Footer Dropdown

```javascript
function toggleMenu(id) {
    document
        .getElementById(id)
        .classList.toggle("show");
}
```

---

## Purpose of Project

Project ini dibuat untuk latihan frontend development dan implementasi slicing UI menggunakan HTML, CSS, dan JavaScript dasar.

Tujuan project:

- Mempelajari layouting website  
- Membuat responsive web design  
- Membuat tampilan streaming app modern  
- Melatih struktur frontend project sederhana  

---

## Future Improvements

Beberapa fitur yang dapat dikembangkan:

- Real authentication system  
- Backend integration  
- Database user account  
- Movie API integration  
- Search movie feature  
- Watchlist feature  
- Dark mode customization  

---

## Author

Created by Nathan Ahnaf

Frontend Project - Movie Streaming App