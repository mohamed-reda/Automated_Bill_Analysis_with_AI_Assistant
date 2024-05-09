# Automated Bill Analysis with AI Assistant

Welcome to Automated Bill Analysis with AI Assistant! This repository hosts an application designed to streamline the
process of analyzing and extracting data from bills using artificial intelligence (AI) technology.

## Overview

Automated Bill Analysis with AI Assistant is a tool developed to assist users in managing their bills more efficiently.
By leveraging AI algorithms, the application can extract relevant information from uploaded PDF bills, such as invoice
ID, description, issue date, unit price, amount, bill recipient, sender, and terms.

## Features

- **PDF Bill Upload**: Users can upload PDF bills directly to the application.
- **AI Extraction**: The application utilizes AI algorithms to extract essential data from the uploaded bills.
- **Data Analysis**: Extracted data is presented in a structured format, allowing users to analyze and understand their
  bills better.
- **CSV Export**: Users can download the extracted data as a CSV file for further analysis or record-keeping.

## How to Use

1. **Upload Bills**: Select and upload PDF bills through the application interface.
2. **Extract Data**: Click on the "Extract bill data..." button to initiate the data extraction process.
3. **Review Results**: Once the extraction is complete, review the extracted data, including the average bill amount.
4. **Download CSV**: Download the extracted data in CSV format using the provided download button.

## Getting Started

To get started with Automated Bill Analysis with AI Assistant, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Set up your OpenAI API key in a `.env` file.
4. the application through the provided local URL.

## About

Automated Bill Analysis with AI Assistant is developed OpenAI for AI-powered
data extraction. It aims to simplify bill management and provide users with insights into their financial transactions
effortlessly.

## Feedback and Support

For feedback, bug reports, or feature requests, please open an issue on GitHub or
contact [mohamed.reda.007007@gmail.com](mailto:mohamed.reda.007007@gmail.com). We appreciate your input and will respond
to your inquiries
promptly.

------------


**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.