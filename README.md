Generator Data Chat Application
A conversational AI application that allows users to interact with generator data uploaded in CSV format. This project uses Streamlit for the interface, along with LangChain and FAISS for handling large datasets. The Llama language model serves as the backend for generating context-based answers.

Features
CSV Data Upload: Easily upload a CSV file with generator data.
Conversational Query Interface: Chat with the AI to get insights from your data.
Efficient Data Retrieval: FAISS-powered embeddings for rapid and relevant responses.
Customizable Model: Uses the Llama model with adjustable parameters for tuning responses.
Repository Contents
.devcontainer: Contains configuration files for development in a containerized environment.
generator.py: Main application file implementing the Streamlit interface and conversational chat feature.
generator_data.csv: Sample CSV file to demonstrate the application's functionality.
README.md: Documentation for setting up and using the application.
Installation and Setup
Clone the repository:

bash
Copy code
git clone https://github.com/Sethuram2003/csv_generator_data.git
cd csv_generator_data
Download the Llama Model: The Llama model file llama-2-7b-chat.ggmlv3.q8_0.bin needs to be downloaded separately from this Kaggle link and placed in the root directory.

Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
streamlit run generator.py
Usage
Launch the app and upload a CSV file with generator data.
Enter your queries in the chat box to retrieve specific insights from the data.
Example queries:
"What is the operational status?"
"Show the recent fuel level readings."


Contributing
Feel free to fork the repository and submit pull requests for any improvements or new features.


