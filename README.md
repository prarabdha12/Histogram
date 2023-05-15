# Word Frequency Histogram

This is a React.js application that fetches the contents of a text file, calculates the frequency of occurrence of each word, and plots a histogram of the 20 most occurring words.

## Features

- Fetches the contents of https://www.terriblytinytales.com/test.txt
- Parses the content and calculates the frequency of each word
- Displays a histogram of the 20 most occurring words
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

![Screenshot 2023-05-15 022134](https://github.com/sudh-202/word-frequency-app/assets/87563365/78a2ecb9-3724-4103-850c-d8435721150b)

4. The top 20 words with the highest occurrence will be plotted in the histogram chart.

![Screenshot 2023-05-15 022151](https://github.com/sudh-202/word-frequency-app/assets/87563365/44e121ff-d399-40d5-a4c3-c53b2a197a2f)


5. Click the "Export" button to download a CSV file containing the histogram data.

![Screenshot 2023-05-15 022405](https://github.com/sudh-202/word-frequency-app/assets/87563365/cb570927-504a-45f5-8cd9-0a57dab63b3c)

# Deployed Version
Access the deployed version of the application here - https://word-frequency-histogram.netlify.app/

# Customization

- To modify the appearance of the application, you can update the CSS styles in the `WordFrequencyHistogram.css` file.

- To change the source of the text file, you can modify the URL in the `fetchWordFrequency function` of the `WordFrequencyHistogram` component.

# Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open a pull request.



