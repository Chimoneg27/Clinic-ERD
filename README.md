# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# 📖 [Clinic-ERD] <a name="about-project"></a>

**[Clinic-ERD]** is a schema for a clinic database. It is a project for the Microverse Ruby curriculum.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **[Patient data]**
- **[Appointment scheduling]**
- **[Billing]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started

To get a local copy of the Clinic-ERD project up and running, follow these steps:

### Prerequisites

In order to run this project, you need to have PostgreSQL installed on your system. If you haven't already installed PostgreSQL, you can download and install it from the official website: [PostgreSQL Downloads](https://www.postgresql.org/download/)

### Setup

1. Clone this repository to your desired folder using the following command:

   ```sh
   git clone https://github.com/Chimoneg27/Clinic-ERD.git

    ```
2. Navigate to the project folder

   ```sh
   cd Clinic-ERD

   ```

### Install

1. Create a PostgreSQL database for the project. You can do this using the PostgreSQL command line or a graphical tool like pgAdmin.

2. Configure the database connection by modifying the config/database.yml file with your database credentials.

3. Install the required gems by running the following command:

   ```sh
   bundle install

   ```
4. Run the migrations to create the database tables:

   ```sh
    rails db:migrate
    rails db:migrate
    ```

### Usage

To run the project, execute the following command:

Example command:

```sh
  rails server
```
Your Clinic-ERD application should now be accessible by visiting http://localhost:3000 in your web browser.

### Run tests

To run tests, run the following command:

Example command:

```sh
  bin/rails test test/models/article_test.rb
```
-

### Deployment

You can deploy this project to a production server of your choice following the standard deployment procedures for Ruby on Rails applications.

<p align="right">(<a href="#getting-started">back to top<a><p>

## 👥 Authors <a name="authors"></a>

👤 **Garvin Chimone**

- GitHub: [@Chimoneg27](https://github.com/Chimoneg27)
- Twitter: [@GarvinChimone](https://twitter.com/GarvinChimone)
- LinkedIn: [Garvin Chimone](https://www.linkedin.com/in/garvin-chimone-37208924a/)

👤 **Fombi Magnus-Favour**

- GitHub: [Fombi-Favour](https://github.com/Fombi-Favour)
- Twitter: [@FavourFombi](https://twitter.com/FavourFombi)
- LinkedIn: [Fombi Favour](https://www.linkedin.com/in/fombi-favour/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- [ ] **[More query options]**
- [ ] **[More appointment options]**
- [ ] **[More billing options]**
- [ ] **[More patients]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Chimoneg27/Vet-Clinic-V1/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

If you like this project, give it a ⭐️!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank the Microverse team for making this possible.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
