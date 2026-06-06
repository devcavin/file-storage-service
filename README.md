# File Storage Service

A simple image file storage service built with Java and Spring Boot. It allows uploading, storing, downloading, and deleting images.

---

## Features

- Upload image files (PNG, JPG, GIF, etc.)
- Download images by filename
- Delete stored images
- Uses MongoDB for persistent storage
- Supports Docker deployment

---

## Tech Stack

| Component  | Technology        |
|------------|-------------------|
| Language   | Java              |
| Framework  | Spring Boot       |
| Database   | MongoDB           |
| Build Tool | Gradle            |
| Deployment | Docker (optional) |

---

## Getting Started

### Prerequisites

- Java 17+
- MongoDB running locally or remotely
- Gradle installed (or use the wrapper)

### Clone the repository

```bash
git clone https://github.com/devcavin/file-storage-service.git
cd file-storage-service
