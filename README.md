
# Mail Project

This project is part of the CS50's Introduction to Computer Science course, specifically the Mail project. It is an email client application developed using HTML, CSS, and JavaScript.

## Features

- User authentication: Allow users to register, login, and logout.
- Compose emails: Users can compose and send emails to other users.
- Inbox: Display a list of received emails in the user's inbox.
- View email: Users can view the content of an email in a separate detail view.
- Archive and Unarchive emails: Users can archive or unarchive emails to organize their mailbox.
- Reply to emails: Users can reply to emails, including the original message as a quote.
- Sent mailbox: Store sent emails in a separate mailbox for reference.
- Error handling: Validate user inputs and handle errors appropriately.

## Technologies Used

- HTML
- CSS
- JavaScript
- Flask (Python web framework)
- SQLite (Database)

## How to Run the Project

1. Clone the repository: `git clone [repository-url]`
2. Navigate to the project directory: `cd mail`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up the database: `flask db migrate` and `flask db upgrade`
5. Start the Flask development server: `flask run`
6. Open the web browser and visit `http://localhost:5000` to access the application.

## Project Structure

- `templates`: Contains HTML templates for different pages.
- `static`: Contains CSS stylesheets and JavaScript files.
- `models.py`: Defines the database models.
- `routes.py`: Defines the routes and logic for handling requests.
- `helpers.py`: Contains helper functions used throughout the application.
- `config.py`: Stores configuration variables.
- `mail.db`: SQLite database file.

## Credits

This project is completed as part of the CS50's Introduction to Computer Science course, offered by Harvard University. Special thanks to the CS50 team for providing excellent learning resources and guidance.

## License

This project is licensed under the [MIT License](LICENSE).
