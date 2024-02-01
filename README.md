# Django Polls Application

## Overview

This Django Polls Application is a web project developed as part of learning Django. It allows users to view polls and vote in them. This project follows the official Django tutorial and includes features such as creating questions and choices through the admin panel, a public site for viewing and voting on polls, and a results view.

## Features

- **Admin Interface**: Secure access for admins to create, update, and delete polls and choices.
- **Polls Listing**: Users can see a list of available polls with their publication dates.
- **Poll Voting**: Users can vote on poll choices and see the current vote count.
- **Results Viewing**: After voting, users can view the results of a poll.

## Installation

To set up the Django Polls Application on your local machine, follow these steps:

1. **Clone the Repository**

    ```
    git clone https://github.com/mtumalan/djangopolls.git
    cd djangopolls
    ```

2. **Set Up a Virtual Environment** (Optional but recommended)

    ```
    python -m venv myvenv
    .\myvenv\Scripts\activate  # On Windows
    source myvenv/bin/activate  # On Unix or MacOS
    ```

3. **Run Migrations**

    ```
    python manage.py migrate
    ```

4. **Create an Admin User**

    ```
    python manage.py createsuperuser
    ```

5. **Run the Development Server**

    ```
    python manage.py runserver
    ```

6. **Access the Application**

    - Admin interface: http://127.0.0.1:8000/admin
    - Public site: http://127.0.0.1:8000/polls

## Usage

- **Admin Usage**: Log in to the admin interface to manage polls and choices.
- **User Voting**: Navigate to the public site, choose a poll, select an option, and submit your vote.
- **View Results**: After voting, view the results of the poll.

## Contributing

Contributions to the Django Polls Application are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to the branch.
5. Create a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Acknowledgments

- This project was inspired by the [Django Official Tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/).
