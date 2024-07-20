# ClickCare - Teleconsultation Application

ClickCare is a web-based healthcare platform designed to improve accessibility to healthcare services. It allows users to schedule appointments and have video consultations with healthcare professionals. The platform also includes functionalities for patients to upload and manage their clinical records and medical history.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User-friendly appointment scheduling
- Seamless video consultations
- Patient functionalities for uploading and managing clinical records
- Storage and management of medical history

## Tech Stack

- **Frontend:** React JS
- **Backend:** Spring Boot
- **Database:** SQL
- **Version Control:** Git

## Installation

### Prerequisites

- Node.js
- npm (Node Package Manager)
- Java Development Kit (JDK)
- Apache Maven
- MySQL or any other SQL database

### Backend Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/vamsidhar32/clickcare.git
    cd clickcare/backend
    ```

2. Configure the database:

    Update the `application.properties` file in the `src/main/resources` directory with your database credentials.

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/clickcare
    spring.datasource.username=vamsi32
    spring.datasource.password=*****
    ```

3. Build and run the backend:

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

### Frontend Setup

1. Navigate to the frontend directory:

    ```bash
    cd ../frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the frontend development server:

    ```bash
    npm start
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to access the ClickCare application.
2. Register or log in as a user.
3. Use the dashboard to schedule appointments, upload medical records, and manage your medical history.
4. Join video consultations through the provided links in your appointments.

## Contributing

We welcome contributions to improve ClickCare. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name (`git checkout -b new-feature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin new-feature`).
5. Create a Pull Request.


