# 🚀 Intelligent Automation Agent Powered by LLM  

Welcome to the **Intelligent Automation Agent**! This advanced tool harnesses the power of natural language processing and cutting-edge LLM technology to streamline and automate a wide range of tasks with precision.  

---

## 🌟 Key Features  
- 🤖 **Smart Task Interpretation**: Utilizes GPT-4o-Mini for precise understanding of tasks.  
- 🔒 **Secure File Management**: Ensures safe handling of sensitive data and files.  
- ⚡ **Multi-Tasking Capabilities**: Efficiently manages and executes multiple tasks simultaneously.  
- 🌐 **API-Driven Operations**: Leverages robust API integrations for seamless task execution.  

---

## 📋 Requirements  
Before getting started, ensure the following are set up:  
- **Docker**: For containerized deployment and management.  
- **AI Proxy Token**: Essential for accessing LLM-powered features.  

---

## ⚙️ Setup & Execution  

### 1. Clone the Project Repository  
```sh
git clone https://github.com/PranavKumar-B/TDS_Project1
```
``` 
cd my-llm 
```

### 2. Install Required Packages  
```
pip install -r requirements.txt  
```

### 3. Configure Environment Variables  
Create a `.env` file in the root directory of the project:  
```
echo "AIPROXY_TOKEN=your_token_here" > .env  
```

### 4. Launch the Application Locally  
```
python run.py  
```

### 5. Deploy with Docker  
Build the Docker image:  
```
docker build -t llm-automation-agent .  
```

Run the Docker container:  
```
docker run --env-file .env -p 8000:8000 llm-automation-agent  
```

---

This setup ensures a smooth and efficient workflow for your automation needs. Let me know if you need further assistance! 🛠️