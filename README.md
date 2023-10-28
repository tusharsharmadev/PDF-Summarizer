# PDF-Summarizer

PDF-Summarizer is a web application designed to summarize PDF documents using the LaMini-Flan-T5-248M Model. With an intuitive interface created using Streamlit, this application simplifies the process of extracting key information from PDF files.

## How to Run the Application:

1. **Prerequisites:**
   - Ensure you have Python installed on your system.
   - Install the required libraries using the following command:
     ```
     pip install -r requirements.txt
     ```

2. **Run the Application:**
   - Open `app.py` in your preferred text editor or IDE.
   - Run the following command in your terminal or command prompt:
     ```
     streamlit run app.py
     ```

   This command will launch the application locally, allowing you to access it via your web browser.

## About the Application:

This PDF Summarization application provides a user-friendly interface to summarize PDF documents. Utilizing the powerful LaMini-Flan-T5-248M Model, the application extracts essential information and generates concise summaries. Users have the flexibility to either provide the local path of the PDF file in the `app.py` file or share a repository link containing the PDF documents.

## How to Use:

1. **Upload PDF:**
   - Users can upload the PDF document directly through the web interface.

2. **Generate Summary:**
   - Click on the "Summarize" button to initiate the summarization process.
   - The LaMini-Flan-T5-248M Model will analyze the PDF content and generate a summary of the document.

3. **View Summary:**
   - The summarized content will be displayed on the interface, allowing users to quickly grasp the document's key points.

Feel free to experiment with various PDF documents and explore the application's capabilities. For any questions, issues, or improvements, please don't hesitate to contribute or reach out. Let's simplify the way we extract valuable insights from PDFs! 📄🔍✨
