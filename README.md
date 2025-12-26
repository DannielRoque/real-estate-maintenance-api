<div id="top"></div>
<!--
*** Real Estate Maintenance API
*** Personal portfolio project
-->



<!-- PROJECT SHIELDS -->
[![Java][java-shield]][java-url]
[![Spring Boot][spring-shield]][spring-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Real Estate Maintenance API</h3>

  <p align="center">
    Backend API built with Spring Boot to manage real estate maintenance requests.
    <br />
    <br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#getting-started">Getting Started</a>
    ·
    <a href="#roadmap">Roadmap</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#domain-overview">Domain Overview</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#api-documentation">API Documentation</a></li>
    <li><a href="#tests">Tests</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project solves a **real-world problem** related to rental properties:  
**handling maintenance requests between tenants and real estate companies**.

Tenants can report issues such as roof leaks or plumbing problems, while the real estate company manages the request lifecycle through a structured workflow.

The project was built as a **portfolio project**, focusing on:
- Backend architecture
- Business rules
- Security
- Realistic domain modeling

<p align="right">(<a href="#top">back to top</a>)</p>



### Domain Overview

#### User Roles
- **TENANT**  
  Can create and track maintenance requests.
- **ADMIN**  
  Can analyze, update status and manage requests.

#### Maintenance Request Status Flow
- OPEN
- IN_ANALYSIS
- IN_PROGRESS
- RESOLVED
- REJECTED (optional)

Each status change is recorded for traceability and auditing.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* Java 17+
* Spring Boot
* Spring Security (JWT)
* Spring Data JPA
* PostgreSQL
* Flyway
* MapStruct
* OpenAPI / Swagger

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Instructions to set up the project locally.

### Prerequisites

* Java 17+
* Maven
* Docker (optional)

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/DanielRoque/real-estate-maintenance-api.git