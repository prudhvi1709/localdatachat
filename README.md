# Local Datachat

A web application that allows users to upload CSV files, execute queries, and download results.

## Description

This project is built using FastAPI for the backend and HTML with Bootstrap for the frontend. Users can upload datasets, execute SQL queries, and interact with the data through a user-friendly interface.

## Usage

1. Start the FastAPI server and HTTP Server with the following command:
   ```bash
   uv run https://raw.githubusercontent.com/prudhvi1709/localdatachat/refs/heads/main/app.py
   ```
   Then, open your web browser and navigate to (http://localhost:8000) to access the Local Datachat application.
1. Use the interface to upload CSV files, execute queries, and download results.
   You can paste multiple paths separated by commas, and the paths should be without quotes. The application can accept the following file types:
   - CSV
   - .parquet
   - SQLite .db
   - .xlsx
   - External MySQL databases from relational-data.org

## File Structure

```
/localdatachat
│
├── app.py              # The main Python application file
├── .env                # Environment variables file
├── README.md           # The project README file
├── static              # Directory for static files
│   └── index.html      # The main HTML file for the frontend
│   └── js              # Directory for JavaScript files
│       └── script.js   # JavaScript file
├── requirements.txt    # The list of required Python packages
├── LICENSE             # The project license file
```

## Features

- **Upload Files**: Users can upload datasets (CSV, .parquet, SQLite .db, .xlsx, and external MySQL databases) through the web interface.
- **Execute Queries**: Users can execute SQL queries against uploaded datasets.
- **Download Results**: Users can download query results in a convenient format.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
