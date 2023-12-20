# Django Project: CourseDjango

Welcome to the CourseDjango project! This project is part of a Django course for practicing and learning Django web
development.

## Project Structure

The project is organized as follows:

- **challenges:** Django app containing challenges, views, templates, and static files.
- **monthly_challenges:** Django project settings and configurations.
- **static:** Directory for storing static files (e.g., CSS).
- **templates:** Directory for HTML templates used in the project.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository:

    ```bash
    git clone git@github.com:alexfbasa/CourseDjango.git
    cd CourseDjango
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Linux/macOS:

        ```bash
        source venv/bin/activate
        ```

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

4. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Access the project in your web browser at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes.
4. Test your changes locally.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created as part of a Django course for educational purposes.
- Thanks to the Django community for providing a powerful web framework.
