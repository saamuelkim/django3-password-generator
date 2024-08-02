# Password Generator 
This project is a Random Password Generator web application created using Django 3. 
It allows users to customize the length and composition of the generated passwords, including options for uppercase letters, special characters, and numbers. 

## Features 
- Generate secure random passwords
- Customize password length
- Include or exclude uppercase letters
- Include or exclude special characters
- Include or exclude numbers.

## Requirements 
- Python 3.x
- Django 3.x.
- 
## Installation 1
1. **Clone the repository**
   ``` git clone https://github.com/yourusername/password-generator.git cd password-generator ```
2. **Create a virtual environment**
   ``` python -m venv env ```
3. **Activate the virtual environment**
   - On Windows:
     ``` .\env\Scripts\activate ```
    - On Mac/Linux:
      ```source env/bin/activate ```
4. **Install dependencies**
   ``` pip install -r requirements.txt ```.

## Running the Application
 1. **Apply migrations**
    ``` python manage.py migrate ```
 2. **Run the development server**
    - On Windows: ``` py manage.py runserver ```
    - On Mac/Linux: ``` python manage.py runserver ```
 3. **Access the application**
    Open your web browser and go to `http://127.0.0.1:8000/`.
    
## Usage 
 1. Navigate to the homepage. 
 2. Select your desired password options:
    - Length
    - Inclusion of uppercase letters 
    - Inclusion of special characters
    - Inclusion of numbers
  3. Click "Generate Password" to receive a secure password.

## License

This project is based on ZappyCode. The modifications and additional styling are licensed under the MIT License. See the `LICENSE` file for more details.

This project also uses Bootstrap, which is released under the MIT License. See the `LICENSE` file for more details.

