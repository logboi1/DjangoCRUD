## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/logboi1/DjangoCRUD.git
   cd DjangoCRUD

2. Create a virtual environment
    ```sh
    python -m venv venv

3. Activate the virtual environment:

On Windows:
    ```sh
    venv\Scripts\activate

On macOS/Linux:
    ```sh
    source venv/bin/activate

Install the dependencies:
    ```sh
    pip install -r requirements.txt

Run the application:
    ```sh
    python manage.py runserver


### Additional Notes

- **Dependency Upgrades**: When updating dependencies, remember to regenerate the `requirements.txt` file using `pip freeze > requirements.txt`.
- **Environment Management Tools**: Consider using tools like `pipenv` or `poetry` for more advanced dependency and environment management. These tools provide additional features such as lock files and integrated virtual environment management.

By following these practices, you ensure that your repository remains clean, manageable, and platform-independent, making it easier for collaborators to set up and work on your project.
