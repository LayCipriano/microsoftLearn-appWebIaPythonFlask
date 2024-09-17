# Translation tool with Python and Flask

## Prerequisites

- Python 3.x installed
- `pip` installed

## Steps to Run the Application

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/microsoftLearn-appWebIaPythonFlask.git
cd microsoftLearn-appWebIaPythonFlask
```

### 2. Create and Activate the Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file at the root of the project and add the necessary variables. Example:

```
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
```

### 5. Run the Application

```bash
flask run
```

The application will be available at `http://127.0.0.1:5000`.

