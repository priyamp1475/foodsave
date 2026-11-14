# FoodSave – Food Waste Reduction Management System

FoodSave is a small web app that connects people with extra food (restaurants, hotels, shops, homes) to NGOs who can collect and distribute it. I built it for my Software Engineering assignment.

**Live demo:** https://priyamp1475.github.io/foodsave/

## Features

- Register and log in as a Donor or NGO
- Donors add food with name, quantity, pickup location and best-before time
- NGOs browse available food and send a request
- Donor or admin confirms the request and marks it completed
- Notifications for new food, requests and confirmations
- Admin dashboard with totals, users and all donations

## Roles

| Role  | What they can do |
|-------|------------------|
| Donor | Add donations, confirm requests, mark pickups completed |
| NGO   | Search available food, request donations |
| Admin | Monitor users, donations and requests |

Admin login for testing: `admin@foodsave.com` / `admin123`

## Tech

HTML, CSS and JavaScript in a single `index.html`. Data is saved in the browser's localStorage, so it works without a server. Because of that, data stays on one device and is not shared between users.

## Run locally

Download or clone the repo and open `index.html` in a browser.

## Possible next steps

- Backend with Flask and MySQL
- GPS-based search for nearby donations
- Mobile app and volunteer delivery tracking
