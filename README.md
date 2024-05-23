# Bid Tracker Portal

## Overview

The Bid Tracker Tool is a web application designed to help companies manage and track their bids efficiently. Users can insert new bids, update existing bids, and delete bids that are no longer needed.

## Current Features

- **Insert a Bid**: Add new bids to the tracker with details such as bid name, client, deadline, and status.
- **Update a Bid**: Modify the details of existing bids, including changes in status, deadlines, or other pertinent information.
- **Delete a Bid**: Remove bids from the tracker that are no longer relevant or required.

## Desired Features 
[Figma Design](https://www.figma.com/design/ne5qOoakizBscYeX1DSMjJ/BTP---Bid-Tracker-Portal?node-id=103%3A361&t=OpCC3m04sVt8CQwS-1)


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
 <!--
- [Configuration](#configuration)
... -->
- [Contributing](#contributing)
 <!--
- [License](#license)
- [Contact](#contact)
... -->
## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/BidTracker.git
    cd BidTracker
    ```

2. **Install dependencies**:
    ```bash
    bundle install
    ```

3. **Set up the database**:
    - Ensure you have a supported database system installed (e.g., PostgreSQL, MySQL, SQLite).
    - Configure your database connection in the `config/database.yml` file.
    - Run the database migrations:
        ```bash
        rake db:create
        rake db:migrate
        ```

4. **Start the application**:
    ```bash
    rails server
    ```

## Usage

1. **Insert a Bid**:
    - Navigate to the "Add Bid" section.
    - Fill in the required details (bid name, client, deadline, status).
    - Click "Submit" to add the bid to the tracker.

2. **Update a Bid**:
    - Locate the bid you wish to update.
    - Click the "Edit" button next to the bid.
    - Modify the necessary details and save changes.

3. **Delete a Bid**:
    - Locate the bid you want to delete.
    - Click the "Delete" button next to the bid.

<!-- 
## Configuration

- **Database Configuration**: Update the `config/database.yml` file with your database credentials.
- **Environment Variables**: Create a `.env` file in the root directory and add any necessary environment variables (e.g., `DATABASE_URL`, `SECRET_KEY_BASE`).
... -->
## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

<!--
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please reach out to:

- Your Name: [Your Email](mailto:youremail@example.com)
- GitHub: [yourusername](https://github.com/yourusername)
-->
