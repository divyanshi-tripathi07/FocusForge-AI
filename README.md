# FocusForge-AI
Developed a modern study productivity platform that helps students manage daily tasks, track study streaks, monitor progress, and improve learning efficiency. Integrated an AI-powered mentor for personalized study guidance and designed a responsive UI with Dark/Light mode support using Figma, React, and Spring Boot.

# 🚀 FocusForge AI – Smart Study Planner & AI Learning Assistant



A modern, AI-powered study productivity platform designed to help students plan, track, and optimize their learning journey. FocusForge AI combines task management, study analytics, streak tracking, and an intelligent AI mentor into a single productivity ecosystem.



# 🎯 Overview


FocusForge AI is a full-stack web application that empowers students to stay consistent, organized, and productive. Users can create study plans, track progress, maintain study streaks, visualize performance through analytics, and receive personalized guidance from an AI-powered study mentor.



# ✨ Features

# 📚 Study Planner

Create, edit, and delete study tasks

Organize tasks by subject and priority

Set deadlines and estimated study duration

Mark tasks as completed

# 🔥 Study Streak System

Daily study streak tracking

Longest streak records

Consistency badges and achievements

Productivity scoring

# ⏱️ Pomodoro Study Timer

Focus Mode (25 minutes)

Short Break (5 minutes)

Long Break (15 minutes)

Study session history

# 📊 Progress Analytics

Weekly study trends

Subject-wise study distribution

Productivity performance charts

Monthly learning reports

# 🎯 Milestone Tracker

Create academic goals

Track completion percentage

Deadline monitoring

Achievement system

# 🤖 AI Study Mentor

Personalized study plans

Concept explanations

Learning recommendations

Productivity guidance

Academic Q&A support

# 👤 User Profile

Profile management

Study goals

Achievement badges

Progress overview

# 🎨 Modern UI/UX

Responsive Design

Dark/Light Theme

Glassmorphism Components

Mobile-Friendly Interface

Smooth Animations

# 🏗️ Project Structure

FocusForge-AI/

│

├── frontend/

│   │

│   ├── components/

│   │   ├── Header.tsx

│   │   ├── Sidebar.tsx

│   │   ├── StatCard.tsx

│   │   ├── ProgressCard.tsx

│   │   ├── MilestoneCard.tsx

│   │   ├── TimerCard.tsx

│   │   ├── TodoCard.tsx

│   │   ├── WisdomCard.tsx

│   │   ├── StudyTrendChart.tsx

│   │   └── icons/

│   │

│   ├── pages/

│   │   ├── HomePage.tsx

│   │   ├── DashboardPage.tsx

│   │   ├── AiMentorPage.tsx

│   │   └── ProfilePage.tsx

│   │

│   ├── services/

│   │   └── geminiService.ts

│   │

│   ├── context/

│   ├── hooks/

│   ├── assets/

│   └── styles/

│

├── backend/

│   │

│   └── src/main/java/com/focusforge/

│       ├── controller/

│       ├── service/

│       ├── repository/

│       ├── model/

│       ├── dto/

│       ├── security/

│       ├── config/

│       └── exception/

│

├── database/

│   └── schema.sql

│

├── README.md

└── pom.xml

# 💻 Technology Stack

Frontend

Technology	Purpose

React.js	User Interface

TypeScript	Type Safety

HTML5	Structure

CSS3	Styling

React Router	Navigation

Recharts	Data Visualization

Backend

Technology	Purpose

Java	Backend Development

Spring Boot	REST API Framework

Spring Security	Authentication

Spring Data JPA	Database Operations

JWT	Secure Authentication

Database

Technology	Purpose

MySQL	Data Storage

AI Integration

Technology	Purpose

Google Gemini API	AI Study Assistant

# 🔐 Authentication

Features

User Registration

Secure Login

JWT Authentication

Protected Routes

Password Encryption

Profile Management

# 📊 Dashboard Modules

Overview Cards

Today's Study Hours

Completed Tasks

Current Study Streak

Weekly Productivity Score

Upcoming Milestones

Analytics

Weekly Study Trend

Monthly Performance

Subject Distribution

Goal Progress Tracking

# 🤖 AI Mentor Capabilities



The AI Mentor can:



Generate personalized study plans

Explain difficult concepts

Recommend learning resources

Create revision schedules

Answer academic questions

Suggest productivity improvements

# 🎨 UI/UX Highlights

Clean and Modern Interface

Responsive Design

Glassmorphism Cards

Smooth User Experience

Dark/Light Mode Support

Accessibility-Friendly Layout

Mobile & Desktop Compatibility

# 🚀 Installation

Clone Repository

git clone https://github.com/your-username/focusforge-ai.git



cd focusforge-ai

Frontend Setup

cd frontend



npm install



npm run dev

Backend Setup

cd backend



./mvnw spring-boot:run

Database Setup

CREATE DATABASE focusforge_ai;



Configure database credentials inside:



application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/focusforge_ai

spring.datasource.username=root

spring.datasource.password=yourpassword

# 📈 Future Enhancements

Study Group Collaboration

Real-Time Notifications

AI Performance Prediction

Voice-Based AI Mentor

Calendar Integration

Mobile Application

Cloud Deployment

Export Reports (PDF/Excel)

# 🎯 Resume Description



FocusForge AI – Smart Study Planner & AI Learning Assistant



Developed a full-stack productivity platform that enables students to manage study tasks, track learning progress, maintain study streaks, and receive AI-powered academic guidance. Implemented responsive UI/UX with Dark/Light mode support and integrated Google Gemini API for personalized study assistance. Built secure backend services using Spring Boot, JWT Authentication, and MySQL.



# 👩‍💻 Developed By



Divyanshi Tripathi

AI & ML Engineering Student
