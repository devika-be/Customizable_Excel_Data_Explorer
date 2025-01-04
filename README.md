# Customizable Excel Data Explorer

A user-friendly Streamlit application for searching and filtering data across multiple Excel files in a specified folder. This app allows you to quickly locate information within specific columns of Excel files, view results interactively, and handle mismatched or inaccessible files gracefully.

---

## 🎯 Features

- **Customizable Searches**: Select a folder, pick a column, and search for specific values.
- **Multiple File Support**: Automatically processes all Excel files (`.xls` and `.xlsx`) in the selected folder.
- **Case-Insensitive Matching**: Search results are case-insensitive and handle partial matches.
- **Custom Styling**: Light blue background, styled title, and warnings for a polished interface.
- **Error Handling**:
  - Skips temporary files (`~$` files).
  - Handles missing or mismatched columns.
  - Warns about inaccessible files (e.g., locked files).

---

## 🛠️ Technologies Used

- **Python**: Core logic and data processing.
- **Pandas**: For Excel file reading and data manipulation.
- **Streamlit**: For building the interactive web interface.
- **HTML & CSS**: For custom styling.

---

## 🚀 How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/streamlit-excel-document-search.git
   cd streamlit-excel-document-search

2. **Install Dependencies**: Make sure you have Python 3.7+ installed. Then, install the required packages:

```bash
pip install -r requirements.txt

3. **Run the Application**:

```bash
python -m streamlit run App.py

4. **Access the App**: Open the link displayed in your terminal (e.g., http://localhost:8501) to interact with the app.

📂 Folder Structure

plaintext

Customizable-Excel-Data-Explorer/
├── App.py                # Main Streamlit application code
├── requirements.txt      # Required Python libraries
├── README.md             # Project documentation
└── .gitignore            # Files and folders to ignore in version control

📋 Usage Instructions
1. **Enter the Folder Path**: Specify the folder containing your Excel files.
2. **Choose a Column**: Select the column you want to search from the dropdown menu.
3. **Enter Search Value**: Provide the value to search for in the chosen column.
4. **Submit**: Click the "Submit" button to perform the search.
5. **View Results**: The matching results are displayed in a table on the screen.

🧪 Example Use Cases
- **Property Management**: Search for specific properties by description.
- **Document Tracking**: Look up documents by their registration date or number.
- **Sales Records**: Filter data based on seller or purchaser details.

⚠️ Known Limitations
- Only processes Excel files (.xls and .xlsx).
- Expects columns to match one of two predefined sets.
- Large files or folders with many files may impact performance.

📜 License
This project is licensed under the MIT License.

🤝 Contributions
Contributions are welcome! If you'd like to improve this project:

1. Fork the repository.
2. Create a feature branch (git checkout -b feature-name).
3. Commit your changes (git commit -m "Add feature").
4. Push to the branch (git push origin feature-name).
5. Open a Pull Request.

📧 Contact
For any questions or feedback, feel free to reach out:

Email: devika.be17@gmail.com
GitHub: devika-be

