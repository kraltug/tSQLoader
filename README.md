# tSQLoader

Manage your MSSQL server with ease using **tSQLoader**, a powerful database handler wrapper built using SQLAlchemy. This tool simplifies interactions with your MSSQL server, whether you're on a Linux or Windows environment.

## Features:
- Efficient handling of database operations
- Seamless integration with popular Python libraries like Pandas and PyODBC
- Harness the power of SQLAlchemy for smooth database interactions
- Works on both Linux and Windows platforms
- Wrapped in a user-friendly interface for straightforward usage

## Installation:

To get started, you can download the latest version of **tSQLoader** from the [Releases](https://github.com/kraltug/tSQLoader/releases) section. Once downloaded, follow the installation instructions provided in the README file.

## Usage:

### Connecting to the Database:

```python
from tSQLoader import MSSQLDatabase

# Initialize the database connection
db = MSSQLDatabase('server', 'database', 'username', 'password')

# Connect to the database
db.connect()
```

### Performing Database Operations:

```python
# Execute a query
result = db.execute_query('SELECT * FROM Table')

# Get query results as a Pandas DataFrame
df = db.get_query_results_as_dataframe('SELECT * FROM Table')

# Insert data into a table
data = {'column1': value1, 'column2': value2}
db.insert_into_table('Table', data)
```

## Topics:
- Database
- Linux
- MSSQL
- Pandas
- PyODBC
- Python
- SQL
- SQL Server
- SQLAlchemy
- Windows
- Wrapper

🚀 Visit the [Releases](https://github.com/kraltug/tSQLoader/releases) section to access the latest version of **tSQLoader**.

![SQL](https://img.icons8.com/windows/452/sql.png)

---

By leveraging **tSQLoader**, you can streamline your database management tasks and focus on what truly matters. With its simplified approach and robust functionality, handling your MSSQL server has never been easier. Give **tSQLoader** a try today and experience the difference in your workflow.