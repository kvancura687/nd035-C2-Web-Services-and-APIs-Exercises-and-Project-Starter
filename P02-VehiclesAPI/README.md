# ND035-P02-VehiclesAPI-Project

Project repository for JavaND Project 2, where students implement a Vehicles API using Java and Spring Boot that can communicate with separate location and pricing services.

## Instructions

Check each component to see its details and instructions. Note that all three applications
should be running at once for full operation. Further instructions are available in the classroom.

- [Vehicles API](vehicles-api/README.md)
- [Pricing Service](pricing-service/README.md)
- [Boogle Maps](boogle-maps/README.md)

## Dependencies

The project requires the use of Maven and Spring Boot, along with Java v11.

## RESOURCES USED
- Used one of the existing tests in CarControllerTest within the project to create the additional required tests
- Main resource was flipping back through the course, watching videos and copying the code used in the videos or provided below the videos, and updating to work in VehiclesAPI
- Pulled snippets of code from the labs throughout the course and updated to fit the VehiclesAPI project as needed
- https://stackoverflow.com/questions/52857820/cxf-codegen-maven-plugin-doesnt-work-openjdk-11 - Used to fix an issue with `cxf-codegen-plugin` in POM, had to update version to 3.3.0.SNAPSHOT
- https://cxf.apache.org/docs/maven-cxf-codegen-plugin-wsdl-to-java.html - Read through it trying to diagnose above issue
- https://github.com/Rapter1990/Build-the-Backend-System-for-a-Car-Website - Used as a visual to compare and see if I missed anything on my end; no code copied from this repository