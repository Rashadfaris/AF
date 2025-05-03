[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/mNaxAqQD)


# React Country Information App

A modern React application that provides information about countries using the REST Countries API. This application allows users to search, filter, and view detailed information about countries around the world.

## Features

- View a list of all countries with their basic information
- Search countries by name
- Filter countries by region and language
- View detailed information about each country
- Responsive design that works on all devices
- User authentication system
- Modern and intuitive user interface

## Technology Stack

- Frontend: React (with functional components)
- CSS: Custom CSS with modern design principles
- API: REST Countries API
- Authentication: Custom backend with JWT
- Testing: Jest and React Testing Library

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Modern web browser

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SE1020-IT2070-OOP-DSA-25/af-2-Rashadfaris.git
cd react-country-info
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. For the backend server:
```bash
cd Backend
npm install
npm start
```

## API Endpoints Used

- GET /all - Get all countries
- GET /name/{name} - Search country by name
- GET /region/{region} - Get countries by region
- GET /alpha/{code} - Get country by code
- GET /lang/{language} - Get countries by language

## Testing

Run the test suite:
```bash
npm test
```




## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- REST Countries API for providing the data
- React team for the amazing framework
- All contributors who have helped with the project 
