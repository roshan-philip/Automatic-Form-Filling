# Automatic Form Filling Using LLMs

## Table of Contents
- Introduction

- Features

- Requirements

- Installation

- Usage

- Configuration

- Data Preparation

- Running the Algorithm

- Contributing

## Introduction
Automatic Form Filling Using LLMs is a project designed to automate the process of filling out forms in various formats such as PDF, Excel, and Word documents. This tool leverages the power of Large Language Models to understand and populate forms based on provided data, mimicking human-like responses.

## Features
- Supports form filling in PDF, Excel, and Word formats.
- Configurable input areas for uploading data and specifying file paths.
- Confidential API key management using external configuration files.
- Handles extra questions dynamically by allowing user inputs for any missing fields.
- Generates human-like answers using GPT models for filling out forms.

## Requirements
Ensure you have the following libraries installed:

- PyPDF2
- pymupdf
- openai
- pandas
- openpyxl
- numpy
- opencv-python
- Pillow
- python-docx
- 
## Installation
To install the required libraries, run:

#### Copy code
pip install pypdf2 pymupdf openai pandas openpyxl numpy opencv-python Pillow python-docx

## Usage
### Configuration
Create a configuration file named config.py to store your API key and model selection securely.
python
#### Copy code
OPENAI_API_KEY = 'your_openai_api_key_here'
GPT_MODEL = 'gpt-3.5-turbo'  # Specify the GPT model you want to use
### Data Preparation
Prepare the data of the people that need to be filled in the form. Ensure the data is structured and ready for input.

## Running the Algorithm
- Upload Form: Upload the form you want to fill.
- Upload Data: Upload the data file containing the information to populate the form.
- Specify Output Path: Provide the file path where you want the filled form to be saved.
- Extra Questions: If there are any missing fields during the initial run, list those questions in the designated area and run the algorithm again.

## Contributing
Contributions are welcome! Please fork this repository, create a new branch for your feature or bugfix, and submit a pull request for review.
