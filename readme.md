# WSDHOMEWORK-9: RestAPI for Creating QR Codes

This project involves creating a FastAPI-based REST API for generating, retrieving, and deleting QR codes. The purpose of the assignment was to debug and fix broken code, ensuring the application functions correctly and passes all CI/CD pipeline checks. 

## Key Updates in This Assignment

### 1. **Fixed Code Errors**
   - Multiple errors were identified and resolved in the codebase. These issues were related to incorrect API endpoints, faulty logic, and misconfigurations that prevented the QR code generation from functioning properly.
   - Tests were repeatedly run, and errors were analyzed to ensure the fixes were accurate.

### 2. **Implemented CI/CD Pipeline**
   - Added a `production.yml` GitHub Actions workflow to automate testing and deployment.
   - Environment variables were configured in the repository settings to ensure secure and smooth operation in CI/CD.

### 3. **Added Docker Support**
   - Introduced a `Dockerfile` and `docker-compose.yml` for containerized deployment.
   - Ensured the QR code files could be saved and accessed within the Docker environment by creating a `qr_codes` directory with appropriate permissions.

### 4. **Integrated Security Scanning**
   - Configured Trivy to scan Docker images for vulnerabilities within the CI/CD pipeline.
   - Addressed security issues to comply with best practices.

### 5. **Unit Tests and Pytest Configuration**
   - Developed and fixed unit tests for key functionalities like QR code creation, retrieval, and deletion.
   - Configured `pytest` to automate these tests, ensuring high code reliability.

---

## Criteria

| **Targets**                      | **Achievements**                                                                                      |
|-----------------------------------|---------------------------------------------------------------------------------------------------------|
| **Data Organization**             | Code was structured into clear modules and routes. A `qr_codes` directory was created for storing QR codes. |
| **Presentation Quality**          | All errors were debugged, and a clean, fully functional project was pushed to GitHub.                    |
| **Depth and Accuracy of Analysis**| Thoroughly analyzed error logs and fixed multiple broken code sections to meet project requirements.     |
| **Effectiveness of CI/CD**        | Successfully set up a GitHub Actions pipeline with testing, building, and Trivy security scanning.       |

---
