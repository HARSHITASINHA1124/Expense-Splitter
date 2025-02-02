# Expense-Splitter

**Expense Splitter** is a simple web app that helps you easily split expenses among a group. You can input the total expense amount and the contributions of each person, and the app will show how much everyone owes or is owed.

## Features
- Add contributors with their names and amounts.
- Calculate the fair share for everyone.
- Shows who owes what to whom.

## Tech Used
- **Frontend**: HTML, CSS (flexbox, responsive design), JavaScript (DOM manipulation).
- **Backend**: Python with Flask.

## Setup

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/expense-splitter.git
   cd expense-splitter
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**:
   ```bash
   python app.py
   ```

4. **Go to** `http://127.0.0.1:5000/` in your browser.

## How It Works
1. Enter the total amount.
2. Add each person's name and contribution.
3. Click "Calculate" to see how much each person owes or should receive.

## API
- `POST /calculate`: Sends the total amount and contributions to the backend and returns how to split the costs.

## Screenshots

## Folder Structure
```
/expense-splitter
├── /static
│   ├── style.css
│   ├── script.js
├── /templates
│   └── index.html
├── app.py
├── requirements.txt
```

## License
MIT License. Feel free to contribute or use the code!

---
