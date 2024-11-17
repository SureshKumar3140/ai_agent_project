```markdown
# AI Agent: Interactive Data Query System

This project enables users to upload any CSV file or Google Sheet and ask natural language questions. The system utilizes a powerful Language Learning Model (LLM) to generate dynamic responses based on the uploaded data. 

## Key Features
- **Dynamic Data Query**: Supports CSV and public Google Sheets as input sources.
- **Natural Language Understanding**: Users can ask questions in natural language, and the LLM provides relevant answers based on the uploaded file's context.
- **Seamless Integration**: Combines Google Sheets API and Groq LLM API to process and interpret data.
- **User-Friendly Dashboard**:
  - Upload CSV files or provide a Google Sheets link.
  - Ask queries and receive precise responses.
  - Preview uploaded data directly in the interface.
  - Download the generated response as a CSV file.

## Project Overview
This project serves as a flexible AI agent capable of assisting in various domains like fault analysis, business insights, and more. It adapts dynamically to the data provided by the user.

## Setup and Usage

### Prerequisites
1. Install Python (>= 3.10).
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   - Create a `.env` file with your API keys:
     ```
     GROQ_API_KEY=<your_groq_api_key>
     SERP_API_KEY=<your_serp_api_key>
     ```

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/SureshKumar3140/ai_agent_project.git
   cd ai_agent_project
   ```
2. Run the application:
   ```bash
   streamlit run app.py
   ```
3. Open the app in your browser at `http://localhost:8501`.

## Directory Structure
```
ai_agent_project/
├── app.py                 # Main application script
├── frontend/
│   └── ui.py              # User interface code
├── backend/
│   ├── api_connections.py # API integrations for Groq and Google Sheets
│   ├── data_processing.py # Handles data query processing
│   └── llm_integration.py # Interacts with LLM for responses
├── requirements.txt       # Required Python packages
├── .env                   # API keys (not included in the repo)
└── README.md              # Project documentation
```

## Loom Video Walkthrough
[Watch the walkthrough video](https://drive.google.com/file/d/114lSyMZaBZ2YNvDvY47V3CsxIR7EjEX1/view?usp=sharing)

## Future Enhancements
- Support for private Google Sheets using credentials.
- Advanced query understanding with multi-language support.
- Enhanced visualization of data insights.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
```
