This streamlit application enables the user to query information from pdf files(s) provided by him/her. This application utilises OpenAI API and LangChain.

To run the application in your system, create a virtual environment in the working directory by:
conda create -p venv python=3.10 -y

activate the venv and install the dependencies by:
pip install -r requirements.txt

create a .env file in the working directory and add the OPENAI_API_KEY from your OpenAI account. The following line shall be written in .env file:
OPENAI_API_KEY='----your key----'

run the following command:
streamlit run app.py

The application opens up in your system's default browser.

Upload single or multiple pdf files. Ask your queries regarding the content in those files.