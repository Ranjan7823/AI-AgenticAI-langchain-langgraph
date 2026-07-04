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


2nd SImple_LLM_Workflow 
<img width="639" height="522" alt="image" src="https://github.com/user-attachments/assets/b9a9e34a-5f82-4d25-a919-f4e6572d407c" />

3- 3_promt_chaining.ipynb
<img width="814" height="548" alt="image" src="https://github.com/user-attachments/assets/81427b57-779b-425b-aefd-9aa916fb7a21" />


4_Batsman work flow - parallel processing 

<img width="872" height="804" alt="image" src="https://github.com/user-attachments/assets/a176af23-40d9-4523-9ed8-613a0fa61ef6" />
<img width="1524" height="839" alt="image" src="https://github.com/user-attachments/assets/d03c949d-5f8c-4b20-b0a3-3b635763dbd2" />
