# Invoice Extractor 
A web application that allows users to upload invoice images and ask questions about the content of those invoices. Powered by Google’s Gemini generative AI model, this tool is designed for financial advisors and anyone needing assistance with invoice interpretation.

## Features
- **Image Upload**: Users can upload invoice images in JPEG or PNG format.
- **Natural Language Processing**: Ask questions about the invoice, and get AI-generated responses.
- **User-Friendly Interface**: Built with Streamlit for a smooth user experience.

## Installation
1. **Clone the repository**:

  ```bash
  git clone https://github.com/mshaadk/Invoice-Extractor-Gemini.git
  cd Invoice-Extractor-Gemini
  ```

2. **Create a `.env` file in the project root and add your Google API key**:

  ```makefile
  GOOGLE_API_KEY=your_api_key_here
  ```

3. **Install the required packages**:

  ```bash
  pip install -r requirements.txt
  ```

## Running the Application
1. Run the Streamlit app with the following command:

  ```bash
  streamlit run app.py
  ```

2. Open your browser and go to `http://localhost:8501` to access the Invoice Extractor.

## Usage
1. Upload an invoice image using the sidebar.
2. Enter your question in the input field.
3. Click "Submit" to receive a response based on the invoice content.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for more details.
