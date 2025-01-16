# Source Code Analysis

A project designed to analyze and process source code efficiently using modern AI tools.

## 🚀 How to Run?

Follow these steps to set up and run the project on your local machine.

### **Step 1: Clone the Repository**

Clone the repository to your local machine:

```bash
# Clone the repository
git clone https://github.com/Nimeshs54/Source-Code-Analysis.git
cd Source-Code-Analysis
```

### **Step 2: Create a Conda Environment**

Set up a virtual environment using Conda:

```bash
# Create a Conda environment
conda create -n llmapp python=3.10 -y

# Activate the environment
conda activate llmapp
```

### **Step 3: Install Dependencies**

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### **Step 4: Configure Environment Variables**

Create a `.env` file in the root directory and add your OpenAI API key:

```ini
OPENAI_API_KEY="your_openai_api_key"
```

Replace `your_openai_api_key` with your actual OpenAI API key.

### **Step 5: Run the Application**

Start the application:

```bash
python app.py
```

### **Step 6: Access the Application**

Open your browser and go to:

```bash
http://localhost:5000
```

## 🛠️ Tech Stack

This project utilizes the following technologies:

- **Python**: Core programming language for development.
- **LangChain**: Framework for building language model-powered applications.
- **Flask**: Lightweight web application framework.
- **OpenAI**: For GPT-3 capabilities.
- **ChromaDB**: Vector database for efficient data retrieval.

---
