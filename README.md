# Stock Evaluation System - Backend API

![Node.js](https://img.shields.io/badge/Node.js-18.x-green)
![Express](https://img.shields.io/badge/Express-5.x-blue)
![Postman](https://img.shields.io/badge/Tested_with-Postman-orange)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Setup Instructions](#setup-instructions)
- [Testing](#testing)
- [Files](#files)

## Tech Stack

- **Backend:** Node.js, Express
- **HTTP Client:** axios
- **API Testing:** Postman
-  **Frontend**  ReactJS 

---

## Project Structure

```
/project-root/
├── /controllers/
│   └── stockController.js
├── /routes/
│   └── stockRoutes.js
├── app.js
├── package.json
└── README.md
```

---

## How to Run the Project

### Install Dependencies

```bash
npm install
```

### Start Server

```bash
npm start
```

Server will run on `http://localhost:5000/`

---

### CodeSnaps and Output
| File | Description |
|------|-------------|
| [`postman1.png`](screenshots/P1.png) | Successful API response in Postman |
| [`postman1.png`](screenshots/P2.png) | Postman tests |
| [`postman3.png`](screenshots/P3.png) | Postman tests |
| [`postman4.png`](screenshots/P4.png) | Postman tests |
| [`react-desktop.png`](screenshots/r2.png) | Desktop view of React frontend |
| [`react-desktop.png`](screenshots/r1.png) | Desktop view of React frontend |


### Key Code Files
| File | Purpose |
|------|---------|
| [`app.js`](backend/app.js) | Main Express application setup |
| [`server.js`](backend/server.js) | Server entry point |
| [`routes/`](backend/routes/) | All API route definitions |
| [`controllers/`](backend/controllers/) | Business logic handlers |
| [`utils/math.utils.js`](backend/utils/math.utils.js) | Correlation calculations |

##  Notes

- Uses stock exchange APIs (provided in assessment) for all data.
- No database or user authentication implemented.
- Data structures, average, and correlation calculations handled internally.

---

##  Formulas Used

### Average

```
average = (sum of all prices) / (number of prices)
```

### Pearson’s Correlation Coefficient

```
ρ = cov(X, Y) / (σx * σy)
```

Where:
- cov(X, Y) = covariance between X and Y
- σx, σy = standard deviations

---

## Author

**Ashutosh Ranjan**
22511044
