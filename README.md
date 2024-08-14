# Bank Card Predictor

This repository contains a web application for predicting bank card attributes using a trained model. The application is built with Django. The model is trained using a Jupyter notebook named `Bank.ipynb`.

## Project Setup

### 1. Create Project Directory

Create a directory for the project. For example:

```bash
mkdir bank_card_predictor
cd bank_card_predictor
```

### 2. Build Environment

Create and activate a virtual environment within the project directory:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Set Up Django Project

Place the `mysite` directory inside the project directory.

### 4. Install Dependencies

Install the required Python packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 5. Migrate Database

Navigate to the `mysite` directory and apply database migrations:

```bash
cd mysite
python manage.py migrate
```

### 6. Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

## Training the Model

The model used for predictions is trained using the Jupyter notebook `Bank.ipynb`, which is located in the main directory of the repository. Follow these steps to train the model:

1. **Open `Bank.ipynb`** in Jupyter Notebook or JupyterLab.
2. **Run the cells** to train the model. Ensure that all necessary libraries and dependencies are installed.
3. **Save the trained model** using `pickle` or another method to a file that will be used by the Django application.
