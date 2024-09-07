# Currency Converter

A simple PyQt5 application for currency conversion. This application allows users to convert amounts between GEL (Georgian Lari), USD (US Dollar), and EUR (Euro). It includes a login system and a converter page with a clean and modern interface.

## Features

- **Login System**: Secure login with credentials.
- **Currency Conversion**: Convert between GEL, USD, and EUR with real-time conversion rates.
- **Responsive UI**: Modern and user-friendly interface.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
pyinstaller --onefile --noconsole --icon=path/to/icon.ico main.py
