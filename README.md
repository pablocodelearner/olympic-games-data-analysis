# Gold, silver and bronze. The Olympic Games through Data.

### Project Overview

Welcome to the **Olympic Medal Analysis** project! This data science project aims to explore the distribution of Olympic medals across various countries and analyze the relationship between a country's economic strength, as measured by Gross Domestic Product (GDP), and its Olympic performance. This analysis is particularly timely, coinciding with the Paris Olympic Games of 2024, providing a fresh perspective on the factors influencing athletic success on the global stage.

### Table of Contents

- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis & Visualizations](#analysis--visualizations)
- [Key Findings](#key-findings)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

### Dataset Information

This project utilizes the following datasets:

1. **Olympic Medals Data**: Sourced from [Wikipedia's All-time Olympic Games medal table](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table).
2. **GDP Data**: Sourced from the World Bank, including GDP values for the years 2022 and 2023.

### Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/olympic-medal-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd olympic-medal-analysis
    ```
3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
    - Alternatively, you can set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

### Usage

1. Ensure all required datasets are placed in the `data/` directory or properly linked if fetched online.
2. Run the Jupyter Notebook or Python script to reproduce the analysis:
    ```bash
    jupyter notebook olympic_analysis.ipynb
    ```
    or:
    ```bash
    python olympic_analysis.py
    ```

3. The analysis will generate various visualizations and statistical outputs, which can be viewed directly in the notebook or saved as files.

### Analysis & Visualizations

- **Data Cleaning and Preparation**: The data is cleaned to remove irrelevant entries and normalized for consistency.
- **Exploratory Data Analysis (EDA)**: Initial insights are gained through histograms and descriptive statistics.
- **Correlation Analysis**: The relationship between GDP and Olympic medals is examined using Pearson correlation and visualized through scatter plots with regression lines.
- **Outlier Analysis**: Countries with extreme data points, like the USA and China, are analyzed separately to understand their impact on global trends.

### Key Findings

- A strong positive correlation between a country’s GDP and the total number of Olympic medals won.
- The removal of outliers slightly affects the correlation, highlighting the significant influence of major economies on global athletic performance.
- Visualizations reveal disparities in Olympic success, with wealthier nations generally outperforming others.

### Contributing

We welcome contributions to enhance the project. Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your message"
    ```
4. Push to your branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request, and we’ll review it as soon as possible.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Contact

If you have any questions or suggestions, feel free to reach out:

- Email: [pablosound@protonmail.com](mailto:pablosound@protonmail.com)
- LinkedIn: [https://www.linkedin.com/in/pablo-ojeda-domenech/](https://www.linkedin.com/in/pablo-ojeda-domenech/)
