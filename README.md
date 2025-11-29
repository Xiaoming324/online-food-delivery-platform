# Online Food Delivery Platform

A full-stack online food delivery platform with a Spring Boot backend, a Vue 2 + Element UI admin dashboard, and a WeChat Mini Program client.  
It supports end-to-end management of employees, categories, dishes, set meals, and customer orders.

---

## Tech Stack

- **Backend:** Spring Boot, MyBatis, Spring Cache, Spring Task, JWT
- **Admin Frontend:** Vue 2, Element UI, Axios
- **Client:** WeChat Mini Program
- **Database & Infrastructure:** MySQL, Redis, WebSocket
- **Analytics & Reporting:** ECharts, Apache POI

---

## Main Features

- Admin dashboard for managing employees, categories, dishes, set meals, and orders  
- WeChat OAuth login with JWT-based authentication and role-based access control  
- Redis caching for frequently accessed menu data  
- Scheduled tasks for auto-canceling unpaid orders and auto-completing deliveries  
- Real-time order notifications via WebSocket  
- Business dashboards and Excel reports for basic analytics

---

## Project Structure

```text
online-food-delivery-platform/
├── online-food-delivery-platform-server          # Spring Boot backend
├── online-food-delivery-platform-admin-vue       # Admin dashboard (Vue 2 + Element UI)
├── online-food-delivery-platform-admin-vue-nginx # (Optional) Nginx deployment config
└── online-food-delivery-platform-client-weixin   # WeChat Mini Program client
