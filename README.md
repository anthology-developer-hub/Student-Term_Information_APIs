# Student-TermInformation_APIs

## Description

This project involves Postman API collection to fetch the Term informations.

## Installation

### Postman

To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API List

The `API/Postman/Student - TermInformations_APIs.postman_collection` file contains the following APIs:

- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms`: Returns all Term Information.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms({Id})`: Returns a Term information based on given Id.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms/CampusNexus.GetStudentServiceBatchTermList()`: Here we get all the student service batch term list.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms/CampusNexus.GetTermListForLoggedInUser()`: Here we get all the term list loggedIn users.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms/CampusNexus.GetTermByCampusId(campusId={campusId})`: Returns a Term information based on given campusId.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Terms/CampusNexus.GetStudentCourseTermList(studentId={studentId})`: Returns student course term list information based on given studentId.

## Usage

After importing the `Student - TermInformations_APIs.postman_collection` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the collection variables correctly:

- `username`: student environment username
- `password`: student environment password
