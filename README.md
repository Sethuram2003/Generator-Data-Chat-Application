# Generator Data Chat Application 🤖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white)](https://streamlit.io/)

A powerful conversational AI application that enables interactive analysis of generator data through natural language queries. Built with Streamlit for the frontend and leveraging LangChain with FAISS for efficient data processing, this application uses the Llama language model to provide context-aware responses to your questions about generator data.

## 🚀 Features

- **CSV Data Upload**: Seamlessly upload and process generator data in CSV format
- **Interactive Chat Interface**: Natural language queries for data insights
- **High-Performance Search**: FAISS-powered embeddings ensure quick and relevant responses
- **Customizable AI Model**: Configurable Llama model parameters for optimal performance
- **User-Friendly Interface**: Clean, intuitive Streamlit-based UI

## 📁 Repository Structure

```
csv_generator_data/
├── .devcontainer/      # Development container configuration
├── generator.py        # Main application code
├── generator_data.csv  # Sample dataset
├── requirements.txt    # Project dependencies
└── README.md          # Documentation
```

## 🛠️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sethuram2003/csv_generator_data.git
   cd csv_generator_data
   ```

2. **Download the Llama Model**
   - Get the model file `llama-2-7b-chat.ggmlv3.q8_0.bin` from [Kaggle](https://www.kaggle.com)
   - Place it in the project's root directory

3. **Set Up Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Application**
   ```bash
   streamlit run generator.py
   ```

## 💡 Usage

1. **Start the Application**
   - Launch the app using the command above
   - Access it through your web browser (typically at `http://localhost:8501`)

2. **Upload Your Data**
   - Use the upload feature to import your CSV file containing generator data
   - The application will process and index the data automatically

3. **Start Querying**
   - Type your questions in natural language in the chat interface
   - Get instant, context-aware responses about your generator data

### Example Queries

- "What is the current operational status of the generators?"
- "Show me the fuel level readings from the past week"
- "Are there any anomalies in the performance metrics?"
- "Generate a summary of maintenance activities"

## 📊 Sample Data Format

Your CSV file should contain relevant generator data columns. Here's a sample structure:
```csv
timestamp,generator_id,operational_status,fuel_level,power_output
2024-01-01 00:00:00,GEN001,active,85.5,750.2
...
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Thanks to the Streamlit team for their amazing framework
- The LangChain community for their excellent tools
- Contributors and users of this application

## 📞 Support

For support, please:
- Open an issue in the GitHub repository
- Contact the maintainers
- Check the [documentation](docs/)

---

Made with ❤️ by [Sethuram2003](https://github.com/Sethuram2003)
