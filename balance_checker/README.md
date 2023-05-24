# Ethereum Balance Checker

This Django application allows you to check the balance and recent transactions of an Ethereum address.

## Getting Started

### Prerequisites

- Python (3.6 or above)
- Django (3.0 or above)
- requests library

### Installation

1. Clone the project repository:

   ```shell
   git clone <repository_url>

2. Install the project dependencies:
    
    ```shell
    cd ethereum_balance_checker
    pip install -r requirements.txt

3. Run the Django development server:
    ```shell
    python manage.py runserver

4. Access the application:

Open your web browser and visit http://localhost:8000.

## Usage
1. Enter an Ethereum address in the input field and click the "Fetch" button.
2. The application will retrieve the balance and the most recent transactions for the provided Ethereum address.
3. The balance and the recent transactions will be displayed on the page.

## Files

* ethereum_balance_checker/views.py: Contains the Django views for rendering the index page and fetching Ethereum data using the etherscan.io API.
* ethereum_balance_checker/templates/index.html: The HTML template file for the index page, which displays the form and the fetched Ethereum data.

## Contributing
Contributions are welcome! If you find any issues or want to contribute to the project, feel free to create a pull request.

    