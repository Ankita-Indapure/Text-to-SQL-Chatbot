📖 Project Overview In many companies, team members may need access to data stored in SQL databases but lack the technical skills to write SQL queries. This chatbot allows users to ask questions in natural language, converts those questions into SQL queries, and retrieves results from the database.

This project is applicable in various domains, including healthcare, retail, and finance.

🔧 Features

-Natural Language Processing: Converts user queries into SQL statements.

-Database Interaction: Connects to MySQL databases to fetch results.

-User-Friendly Output: Provides results back to the user in natural language.

-End-to-End Solution: From data preparation to interaction with the chatbot.


🛠️ Installation To get started with the Text to SQL Chatbot, follow these steps:

1.Clone the Repository:

2.Set Up MySQL:

  -Create a MySQL database and tables as specified in the project.
  -Load your data from Excel sheets into the MySQL database.

3.Configure API Keys: Ensure you have the necessary API keys for the LLM you will be using (e.g., Google Gemini).


🗼 Architecture The architecture of the Text to SQL Chatbot consists of the following components:

1.Data Source: Excel sheets containing raw data.

2.Database: MySQL database where the data is stored and queried.

3.LLM Chain: Uses a large language model to convert natural language questions into SQL queries.

4.Output Parser: Processes the SQL query output and formats it for user display.
