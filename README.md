# Generator Data Chat Application

A conversational AI application that enables users to interact with generator data uploaded in CSV format. This project uses **Streamlit** for the interface, along with **LangChain** and **FAISS** for handling large datasets. The **Llama** language model serves as the backend, generating context-based answers to user queries.

---

## Features

- **CSV Data Upload**: Easily upload a CSV file containing generator data.
- **Conversational Query Interface**: Interact with the AI through a chat-based interface to gain insights from your data.
- **Efficient Data Retrieval**: Powered by FAISS embeddings, ensuring rapid and relevant responses to your queries.
- **Customizable Model**: Utilizes the Llama model, with adjustable parameters to fine-tune responses.

---

## Repository Contents

- **.devcontainer**: Configuration files for containerized development.
- **generator.py**: Main application file, implementing the Streamlit interface and conversational chat feature.
- **generator_data.csv**: Sample CSV file to demonstrate the application's functionality.
- **README.md**: Documentation for setting up and using the application.

---

## Installation and Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Sethuram2003/csv_generator_data.git
   cd csv_generator_data```

2. **Download the Llama Model**:

The model file llama-2-7b-chat.ggmlv3.q8_0.bin must be downloaded separately. You can find it on Kaggle and place it in the root directory of this project.

3. **Install dependencies**:

```bash
Copy code
pip install -r requirements.txt```

4. **Run the application**:

```bash
Copy code
streamlit run generator.py```

Usage
Launch the App: Start the app and upload a CSV file containing generator data.
Interact with the Data: Enter your queries in the chat box to retrieve specific insights from the data.
Example Queries
"What is the operational status?"
"Show the recent fuel level readings."
Contributing
Feel free to fork the repository and submit pull requests for any improvements or new features. We welcome contributions that enhance functionality or optimize performance.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
