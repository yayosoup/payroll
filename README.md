# 🧾 Payroll System

A full-stack employee time-tracking and payroll management system built with **.NET**, **React**, **Swift**, and **AWS**.
The platform allows employees to clock in/out via a mobile app, while administrators manage shifts, payroll, and employee data through a secure web dashboard.

## 🚀 Project Overview

*The Payroll System consists of three integrated applications that communicate through a unified REST API:*  
[**Backend API**](https://github.com/yayosoup/payroll-backend) ASP.NET Core Web API hosted on AWS Elastic Beanstalk. Handles business logic, and persistence to AWS RDS (PostgreSQL).

[**Admin Panel (Web)**](https://github.com/yayosoup/payroll-admin) React-based dashboard for HR and managers to view employees, shifts, and payroll summaries in real time.

[**iOS App (Employee)**](https://github.com/yayosoup/payroll-ios) Swift-based mobile client for employees to securely clock in/out. The app communicates with the backend via HTTPS requests.
