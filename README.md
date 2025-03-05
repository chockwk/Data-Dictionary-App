# 📖 Data-Dictionary-App 

## Overview

This 👑 Streamlit-based Data Dictionary App provides an interactive interface to explore dataset structures, column details, and associated code tables. Users can:

- Select from multiple datasets.
- View column names, data types, and descriptions.
- Search and filter based on column names and data types.
- Expand code tables for categorical variables.
- Easily switch between datasets using a dropdown menu.
- See reference codes linked to datasets.
- Experience an optimized interface with a wide layout and adjustable dropdowns.


## Features

✅ Dataset Selection
- Users can choose from multiple datasets via a dropdown menu.
- Each dataset comes with a reference code.

✅ Column Details & Filtering
- Displays column names, data types, and descriptions.
- Users can search for specific columns.
- Filter based on data type.

✅ Code Tables
- Expandable sections for columns that have coded values.
- View mappings for categorical variables (e.g., "1" → Present, "0" → Absence).

✅ Enhanced UI
- Full-width layout for better readability.
- CSS adjustments to improve dropdown usability.

## Installation and Usage

1️⃣ Set Up Environment

```sh
pip install streamlit
```

2️⃣ Run the App

```sh
streamlit run data_dictionary.py
```

3️⃣ Accessing the App in SageMaker Studio

- Once the instance is ready after running, open or duplicate SageMaker Studio in your browser.
- Edit the URL by appending /proxy/port_number.
  (Replace port_number with the actual port Streamlit runs on, typically 8501)
- Bookmark the Data Dictionary page for quick access.

4️⃣ Usage

1. Open the Streamlit 
2. Select a dataset from the dropdown on the sidebar. 
3. Explore column details and filter as needed. 
4. Expand code tables to view value mappings.

## Contributing

Feel free to submit issues or pull requests for improvements!
🚀 Enjoy exploring your data dictionaries!

