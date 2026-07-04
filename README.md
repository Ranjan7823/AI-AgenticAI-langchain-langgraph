AI-AgenticAI-LangGraph-Langchain
BMI- Calculator

python -m venv myenv

powershell Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser (for allow allow env)

S D:\AI\langchain-langgraph> .\myenv\Scripts\Activate.ps1 (myenv) PS D:\AI\langchain-langgraph> .\Scripts\Activate.ps1

VS Terminal PS D:\AI\langchain-langgraph\myenv> pip install langgraph
PS D:\AI\langchain-langgraph\myenv> pip install langchain
PS D:\AI\langchain-langgraph\myenv> pip install langchain_openai PS D:\AI\langchain-langgraph\myenv> pip install dotenv

craete a file 0_test_installation.ipynb - this notebook used for test wheather install package are working or not

from langgraph.graph import StateGraph

-- 1_bmi_workflow image
<img width="1901" height="1015" alt="image" src="https://github.com/user-attachments/assets/06e5dc26-b037-42c9-adfa-9c1fea4c9675" />



Added New node for BMI Labale 
<img width="225" height="455" alt="image" src="https://github.com/user-attachments/assets/f5198b79-8f93-4d71-b8e6-62df4305811c" />
