# JWT Authentication with Spring Security

Welcome to the **JWT Authentication with Spring Security** project! This project demonstrates how to secure a Spring Boot application using **JSON Web Tokens (JWT)** and **Spring Security**. It includes essential components like customer authorization.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
  - [Clone the repository](#clone-the-repository)
  - [Configuration](#configuration)
  - [Running the Application](#running-the-application)
- [Endpoints](#endpoints)
- [Security](#security)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Introduction

This project provides a robust and flexible authentication mechanism for Java-based web applications by leveraging **Spring Security** and **JWT**. The authentication system consists of:

- **JWT generation** after successful login.
- **JWT validation** for securing API endpoints.
- **Role-based authorization** using Spring Security.

## Features

- **User Authentication**: Using username and password to generate JWT tokens.
- **Role-based Access Control**: Protect sensitive endpoints with custom roles.
- **Token Refresh**: Support for refreshing JWT tokens when they expire.
- **Secure API Endpoints**: Using JWT tokens for API authentication.

## Technologies Used

- **Java 17** or above
- **Spring Boot 2.x**
- **Spring Security 5.x**
- **Spring Web**
- **Spring Data JPA**
- **MySql Database** (or use your preferred database)
- **JWT (JSON Web Tokens)**
- **Maven/Gradle** for dependency management

## Setup

### Clone the repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/ms593/jwt-spring-security.git
cd jwt-spring-security
