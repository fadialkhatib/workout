# 🏋️ Home Workout Platform

> Personalized fitness application generating safe home workout plans based on user health conditions and goals.

[![Laravel](https://img.shields.io/badge/Laravel-8-red?style=flat&logo=laravel)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.0-blue?style=flat&logo=php)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql)](https://mysql.com)

## 🎯 Mission
Make fitness accessible to everyone by providing safe, personalized home workout plans — especially during times when gyms are inaccessible (pandemic, cost, location).
This app was released when the coronavirus was at its peak, so its existence was essential.

## ✨ Key Features

### 📋 Smart Plan Generator
- **Health Assessment:** Users input injuries, diseases, and physical limitations.
- **Goal Mapping:** Weight loss, muscle gain, or endurance training.
- **Safety Logic:** Algorithm excludes unsafe exercises based on medical constraints.

### 🏠 Home-Friendly Workouts
- No equipment required exercises.
- Time-efficient sessions (15-45 minutes).
- Progress tracking & weekly adjustments.

### 👤 User Dashboard
- Workout history & completion tracking.
- Visual guides for exercises.
- Feedback loop for plan improvement.

## 🏗️ Architecture Highlights
- **Rule-Based Logic:** Backend algorithm matching user constraints to exercise database.
- **Safety First:** Validation layer preventing conflicting health/exercise combinations.
- **Scalable Design:** Modular exercise catalog for easy content expansion.

## 🚀 Quick Start
```bash
git clone https://github.com/fadialkhatib/workout-app.git
cd workout-app
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
