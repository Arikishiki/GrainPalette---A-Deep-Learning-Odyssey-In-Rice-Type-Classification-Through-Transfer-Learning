# Grainpalette - Rice Grain Classification Web App

Grainpalette is a machine learning-powered web application that classifies rice grain images into different types. The project uses Python, Flask, and a Convolutional Neural Network (CNN) model to automate the classification process.

## Project Overview

Manual classification of rice grains is time-consuming and prone to error. Grainpalette provides an accessible platform for automatic classification, improving accuracy and efficiency for agricultural professionals and researchers.

## Features

- Upload images of rice grains through a web interface
- Automatic prediction of rice grain type
- Display of classification results and confidence scores
- Simple and intuitive user interface

## Project Structure

rice/
├── app.py  
├── rice-classification.ipynb  
├── requirements.txt  
├── templates/  
│   ├── index.html  
│   ├── results.html  
│   └── details.html  

## Requirements

- Python 3.x
- Flask
- TensorFlow / Keras
- NumPy
- Pandas

Install dependencies using:

pip install -r requirements.txt

## How to Run

1. Clone the repository:

git clone https://github.com/your-username/grainpalette.git
cd grainpalette

2. Install dependencies:

pip install -r requirements.txt

3. Run the Flask app:

python app.py

4. Open your browser and visit:

http://localhost:5000

## Usage

- Navigate to the home page
- Upload an image of rice grains
- Click Predict
- View the classification result

## Future Improvements

- Add more rice grain varieties to the dataset
- Improve model accuracy
- Build a mobile version of the app

## Author

Team ID: LTVIP2025TMID33603  
Project Title: Grainpalette

## License

This project is licensed under the MIT License.
