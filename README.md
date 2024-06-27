# Student API Collection

This repository contains a collection of API endpoints related to student data management.

## Description

The Student API Collection provides various endpoints for retrieving and managing student-related data within a campus management system. It includes endpoints for retrieving people details, person addresses, email addresses, gender pronoun data changes, and phone numbers.

## Getting Started

To use the API endpoints, follow these steps:

1. Clone or download this repository to your local machine.
2. Import the provided Postman collection (`Student_API_Collection.json`) into your Postman application.
3. Configure the necessary environment variables such as `username` and `password` for authentication.
4. Start making requests to the desired endpoints.

## Available Endpoints

- **Retrieve People Details**: `GET /ds/campusnexus/People`
- **Retrieve Person Addresses**: `GET /ds/campusnexus/PersonAddresses`
- **Retrieve Person Email Addresses**: `GET /ds/campusnexus/PersonEmailAddresses`
- **Retrieve Person Gender Pronoun Data Changes**: `GET /ds/campusnexus/PersonGenderPronounDataChanges`
- **Retrieve Person Gender Pronouns**: `GET /ds/campusnexus/PersonGenderPronouns`
- **Retrieve Person Phone Numbers**: `GET /ds/campusnexus/PersonPhoneNumbers`

## Authentication

All endpoints require basic authentication. Provide your username and password in the request headers.

## Contributions

Contributions to this API collection are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.

## License

This API collection is released under the [MIT License](LICENSE).
