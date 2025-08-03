# csv-analyzer-
This project is a smart CSV Analyzer built using FastAPI and local LLMs from Ollama. It allows users to upload any .csv file and ask natural language questions like “What are the key insights?” or “Which item had the highest sales?”. The system reads and summarizes the dataset, extracts key patterns, and uses an Ollama-powered large language model (like LLaMA 3) to generate insightful responses in real time. Everything runs locally, ensuring privacy and speed without relying on external APIs.

The backend is built with FastAPI, which provides a simple yet powerful RESTful interface. Once the server is running, users can access the Swagger UI at http://localhost:8000/docs to upload their CSV file and input a question. The application uses Pandas to parse and analyze the uploaded data, and then sends a structured summary along with the user’s query to the LLM. The model analyzes the data contextually and returns a natural-language response tailored to the dataset.

This CSV analyzer is perfect for anyone who wants fast, intelligent insights from structured data without manually writing code or SQL queries. It can be easily extended to include features like visualization, multiple dataset comparison, anomaly detection, or even a full frontend using Streamlit or Gradio. Future versions could also support downloadable reports, data cleaning tools, and cloud deployment options.

To run the project locally, you'll need Python 3.8 or later and Ollama installed with a suitable model pulled. After installing dependencies and running the FastAPI app, you can access the Swagger UI to start uploading and analyzing CSVs instantly. The project structure is modular, making it easy to plug in more tools or switch to a cloud LLM if needed.

This tool empowers users to interact with their data using natural language, combining the power of machine learning with the simplicity of a REST API — all while keeping your data secure and local.
