# 📊 **Annual Inflation Rate Visualization of African Countries**

This project visualizes the **Annual Inflation Rate** of African countries using an interactive **choropleth map**. The map animates over different years to show how inflation varies across the continent, providing a clear visual representation of the economic situation.

![Screenshot 2025-03-24 214816](https://github.com/user-attachments/assets/2837d35d-7a4e-44be-b36f-2aacf4ef8b5b)

![Screenshot 2025-03-24 214834](https://github.com/user-attachments/assets/66194f1e-603d-4c64-9b34-477c67141339)

![Screenshot 2025-03-24 214856](https://github.com/user-attachments/assets/fcb796df-a701-4fda-8cbb-6cb008a195ae)

---

## 🚀 **Project Overview**

The **Annual Inflation Rate Visualization** project is aimed at displaying the inflation rates of African countries over time in a visually appealing and easy-to-understand format. The project uses **Plotly** for creating interactive graphs and **Python** for data analysis and visualization. The choropleth map allows users to observe how inflation changes year over year across different African countries.

---

## 🎯 **Key Features**

- **Interactive Choropleth Map**: A color-coded map to visualize the inflation rates.
- **Animated over Years**: The map animates across different years, providing insights into inflation trends.
- **Color-Coded for Inflation**: Countries are color-coded based on the inflation rate, with a smooth color gradient.
- **Plotly Dark Theme**: The map uses a visually appealing dark theme for better visibility.

---

## 📊 **Data Description**

The dataset used for this project contains the following columns:
- **year**: The year for which inflation data is available.
- **cc3**: The 3-letter ISO country code.
- **inflation_annual_cpi**: The annual inflation rate based on the Consumer Price Index (CPI).
- **country**: The name of the country.

---

## 🛠️ **Installation**

To run this project locally, you will need to install the necessary libraries. Follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/inflation-rate-visualization.git
2. Navigate to the project folder
bash
Copy
Edit
cd inflation-rate-visualization
3. Create a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
4. Install required dependencies
bash
Copy
Edit
pip install -r requirements.txt
5. Run the project
Once the environment is set up, you can run the project:

bash
Copy
Edit
python your_script_name.py
📈 Usage
The script will generate an animated choropleth map displaying the inflation rate of African countries over the years.

Customization:
Inflation Data: You can modify or add additional data in the dataset for other regions or years.

Color Scheme: The color scheme used for the map is thermal. You can change it to other available options in Plotly.

🔧 Technologies Used
Python: Programming language used for data analysis.

Plotly: Visualization library to create the interactive choropleth map.

Pandas: For data manipulation and handling.

📂 Project Structure
The project directory has the following structure:

bash
Copy
Edit
inflation-rate-visualization/
│
├── data/                    # Folder containing datasets
├── script.py                # Main Python script for creating the map
├── requirements.txt         # List of dependencies
└── README.md                # Project overview and documentation
📝 Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork this repository and create a pull request.

To contribute:

Fork this repository.

Create a new branch (git checkout -b feature-branch).

Make your changes.

Commit your changes (git commit -am 'Add new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🌐 Acknowledgements
The inflation data used in this project was sourced from various public datasets.

Thanks to Plotly for providing an easy way to create interactive visualizations.

Enjoy exploring the inflation trends of African countries! 🎉

vbnet
Copy
Edit

### How to Customize:
1. **Title & Description**: Change the project title and description to match your project’s focus.
2. **Installation**: Make sure to update the installation steps to match your project structure and any external libraries you use. I assumed you have a `requirements.txt` file for dependencies.
3. **Project Structure**: Update the structure to reflect your actual files and folders.
4. **Usage**: Add any specific usage instructions, such as how to run your code or how to interact with the visualizations.
5. **Technologies Used**: List any frameworks, libraries, or tools you've used for the project.

Once you've customized this, you can save it in a `README.md` file and push it to your GitHub r
