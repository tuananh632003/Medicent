# MedicineSearch

## Setup Instructions

1. **Create and Activate Python Environment**
   - Ensure you have Python 3.13 installed.
   - Create a virtual environment:
     ```
     python3 -m venv venv
     ```
   - Activate the virtual environment:
     - On macOS/Linux:
       ```
       source venv/bin/activate
       ```
     - On Windows:
       ```
       venv\Scripts\activate
       ```

2. **Install Required Libraries**
   - Install the required libraries using the following command:
     ```
     pip install -r libs.txt
     ```

3. **Initialize Database and Vectorize Data**
   - Run the following command to initialize the database and vectorize data:
     ```
     python vectorizer.py
     ```

4. **Run the Project**
   - Start the FastAPI application with the command:
     ```
     fastapi dev
     ```

## New Features

- **Recommendation Keywords**
  - Endpoint: `/recommendations?query=your+search`
  - Returns a list of suggested keywords extracted from the top matched medicines to help refine your search.
