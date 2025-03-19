📜 JavaScript to Python Conversion Agent

📌 Overview

This project automates the conversion of JavaScript code to Python using AI-powered agents. It reads JavaScript code from a file, translates it into Python using Groq's Llama 3, and validates the execution of the generated Python script. The workflow is implemented using LangGraph, ensuring structured execution with error handling and retries.

🔍 Key Features

🚀 Automated Code Processing
Reads JavaScript code from an input file.
Uses Groq’s Llama 3 to generate equivalent Python code.

📈 Conversion & Execution
Extracts only the valid Python code from the LLM response.
Executes the generated Python script and validates the output.
Retries up to 5 times before requiring human intervention.

🔍 Error Handling & Debugging
Handles incorrect or partial conversions.
Provides detailed logs for debugging.
Ensures seamless execution through an agent-based workflow.

🛠 Future Enhancements
✅ Support for More Complex JavaScript Syntax (Classes, ES6, Async/Await).
✅ Integration with Multiple AI Models (e.g., OpenAI, Gemini, Cohere).
✅ Enhance Code Optimization & Formatting Techniques.
✅ Develop a Web Interface for Interactive Code Conversion.


📬 Contact
For any questions or suggestions, feel free to reach out via LinkedIn or GitHub.

⭐ If you find this project useful, don't forget to star this repository! ⭐
