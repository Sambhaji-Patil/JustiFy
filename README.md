# Legal Document Assistant

A web-based application designed to simplify legal document analysis. Users can upload legal documents, receive AI-generated summaries, ask legal questions, and generate professional response drafts effortlessly.

## Features

- **📜 Document Analysis**: Upload and analyze legal documents to extract key insights, summaries, and critical metrics.
- **🔍 Document Classification**: Automatically categorize documents into legal types such as court orders, contracts, notices, etc.
- **💬 Interactive Chat**: Engage with an AI-powered assistant to ask questions related to your uploaded document.
- **⚖️ General Legal Chat**: Get answers to general legal queries without uploading a document.
- **📝 Professional Draft Generation**: Generate legally formatted response drafts (letters, notices, and agreements) in Word format.
- **📂 PDF Viewer**: View and navigate uploaded PDFs directly within the application.
- **📄 Summary Export**: Download analyzed document summaries as a PDF for easy reference.

## Technologies Used

### Frontend
- **HTML, CSS, JavaScript** – Responsive UI for an intuitive user experience
- **Bootstrap** – Ensures a mobile-friendly and polished design

### Backend
- **Python, Flask** – Backend API handling requests and responses efficiently

### AI & Document Processing
- **OpenAI GPT Models** – AI-powered document analysis and legal chat assistance
- **PyPDF2** – Extracts and processes text from uploaded PDF files
- **python-docx** – Generates formatted Word documents for legal drafts

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Python (>=3.8)
- pip (Python package manager)

### Steps to Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/legal-doc-assistant.git
   cd legal-doc-assistant
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Start the Flask server:
   ```sh
   python app.py
   ```
4. Open the application in your browser at `http://127.0.0.1:5000`

---

Made with ❤️ by DevBytes