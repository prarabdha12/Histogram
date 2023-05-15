# Histogram (Chart / Word  Count)

This is a React.js application that fetches the contents of a text file, calculates the frequency of occurrence of each word, and plots a histogram of the 20 most occurring words.

## Features

- Fetches the contents of https://www.terriblytinytales.com/test.txt
- Parses the content and calculates the frequency of each word
- Displays a histogram of the 20 most occurring words o X-axis
- Provides an "Export" button to download a CSV file of the histogram data

## Technologies Used

- React.js
- Axios (for making HTTP requests)
- Plotly.js (for plotting the histogram)
- CSS (for styling)

## Installation

### 1. Clone the repository:
```bash
git clone <repository_url> && cd word-frequency-histogram
```
### 2. Navigate to the project directory:
```bash
cd word-frequency-histogram
```
### 3. Install the dependencies:
```bash
npm install
```
# Usage
1. Start the development server:

npm start

2. Open your browser and visit `http://localhost:3000` to access the application.

3. Click the "Submit" button to fetch the word frequency and display the histogram.

![Screenshot 2023-05-15 220936](https://github.com/prarabdha12/word-frequency-app/assets/99959938/e5304fc6-23b6-440f-b742-a3f0af4b5c8a)



4. The top 20 words with the highest occurrence will be plotted in the histogram chart.

![dool](https://github.com/prarabdha12/word-frequency-app/assets/99959938/70687ded-309a-40e1-86b9-638b028cf161)



5. Click the "Export" button to download a CSV file containing the histogram data.

![deadpool](https://github.com/prarabdha12/word-frequency-app/assets/99959938/e36e118b-94db-461f-a3e7-71b3001bfc9a)


# Deployed Version
Access the deployed version of the application here - https://phenomenal-faun-f9ca7d.netlify.app/



