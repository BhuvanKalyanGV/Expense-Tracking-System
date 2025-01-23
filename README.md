# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.It stores the data in MySQL database and gives 3 tabs which are adding data, analytics on a range of dates and analytics based on total expenses of each month.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
## Output
![Screenshot 2025-01-23 192229](https://github.com/user-attachments/assets/f60a10c0-2c10-4922-8eda-e9b6127acf4c)
![Screenshot 2025-01-23 192250](https://github.com/user-attachments/assets/20cd4fe6-1cea-4e0b-8d9b-803762a3852e)
![Screenshot 2025-01-23 192304](https://github.com/user-attachments/assets/379da790-cf09-44dc-a8b0-0c7c2083d185)


## Author
Bhuvan Kalyan G V
[LinkedIn: in/bhuvan-kalyan-g-v](https://www.linkedin.com/in/bhuvan-kalyan-g-v/)

## Version History
 0.1: Initial Release
