# Vynx: A Microservices-Based Video Streaming Platform

Vynx is a modern, scalable short video streaming platform built using a microservices architecture and deployed on Google Cloud Platform (GCP). Developed as the end-semester project for SE-315 Cloud Computing, Vynx demonstrates the power of cloud-native technologies in building robust, production-ready applications.

## Features

- User Authentication: Secure login and registration powered by Firebase Authentication
- Video Management: Cloudinary integration for efficient video hosting with storage limits and alerts
- Usage Monitoring: Real-time bandwidth tracking and comprehensive API request logging
- Scalable Architecture: Deployed on GCP using Cloud Run and Docker containers
- Modern Frontend: Responsive user interface built with Next.js and Tailwind CSS
- Microservices Design: Independent, loosely coupled services for better maintainability and scalability

## Architecture

The platform follows a microservices architecture with the following components:

- Auth Service: Handles user authentication and authorization via Firebase
- Video Service: Manages video uploads, processing, and streaming
- Storage Service: Interfaces with Cloudinary for video storage and optimization
- Monitoring Service: Tracks bandwidth usage and API requests
- API Gateway: Routes requests to appropriate microservices
- Frontend Service: Next.js application serving the user interface

## Tech Stack

### Frontend
- Next.js
- Tailwind CSS
- Firebase Client SDK

### Backend
- Node.js / Express
- Firebase Authentication
- Cloudinary API

### Cloud Infrastructure
- Google Cloud Platform (GCP)
- Cloud Run
- Docker

### Monitoring & Analytics
- Custom logging solutions
- Bandwidth tracking
- API usage monitoring
