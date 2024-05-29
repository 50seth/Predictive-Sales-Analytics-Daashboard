# Predictive-Sales-Analytics-Dashboard
PLP FINAL PROJECT
---

## Project Overview
The Predictive Sales Analytics Dashboard is a web-based application that allows small business owners to input their historical sales data and receive predictive insights about future sales trends. The dashboard leverages data visualization and machine learning to help businesses make data-driven decisions regarding inventory, marketing, and operations.

## Features
- **Data Input**: Users can input historical sales data through a web form.
- **Data Storage**: Sales data is stored in a MongoDB database.
- **Predictive Analysis**: A neural network model predicts future sales trends based on historical data.
- **Data Visualization**: Sales data and predictions are visualized using Chart.js.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Machine Learning**: brain.js (JavaScript library)
- **Data Visualization**: Chart.js

## Project Structure
```
PredictiveSalesDashboard/
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   └── config/
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── scripts/
│       └── main.js
├── README.md
└── package.json
```

## Setup and Installation

### Prerequisites
- Node.js
- MongoDB
- npm (Node Package Manager)

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PredictiveSalesDashboard.git
   cd PredictiveSalesDashboard/backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB:
   - Ensure MongoDB is installed and running on your machine.
   - Create a new database named `salesdb`.

4. Start the Node.js server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```

2. Open `index.html` in your preferred browser.

## Usage
1. Open the `index.html` file in your web browser.
2. Use the form to input historical sales data.
3. Submit the data and view the predictive sales trends on the dashboard.

## Contributing
We welcome contributions to enhance the functionality and features of this project. Feel free to fork the repository, make changes, and submit a pull request.


## Contact
For any questions or feedback, please contact sethoketch61@gmail.com.

---
