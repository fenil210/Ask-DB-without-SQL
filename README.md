# NaturalSQL: Transforming Natural Language Queries into SQL

## Introduction

In the world of data science, databases (DB) play a pivotal role in storing, managing, and analyzing vast amounts of data. Structured Query Language (SQL) serves as the standard language for interacting with databases, allowing data scientists to retrieve, manipulate, and analyze data effectively.

However, traditional SQL interfaces require users to have a deep understanding of SQL syntax and database schema, posing a significant barrier to entry for those not familiar with these concepts. Despite SQL's power and versatility, accessing databases in natural language, such as English, is challenging due to the structured nature of SQL input.

## The Challenge

Data scientists often face challenges when attempting to interact with databases using natural language. The rigid structure of SQL queries makes it difficult for users to express complex queries in a natural, conversational manner. This limitation hinders productivity and accessibility for individuals without a background in SQL.

## Introducing NaturalSQL

NaturalSQL is a revolutionary solution that bridges the gap between natural language and SQL, enabling users to effortlessly transform complex natural language queries into actionable SQL commands. Powered by cutting-edge Language Model (LLM) technology, NaturalSQL leverages advanced machine learning mechanisms to interpret and process natural language queries with precision and accuracy.

## Setting up Virtual Environment

```bash
# Create a virtual environment named 'venv'
conda create -n venv

# Activate the virtual environment
conda activate venv

# Install required packages
pip install -r requirements.txt
```

## Technologies Used

NaturalSQL incorporates several key technologies and frameworks to deliver seamless text-to-SQL conversion:

1. **LLM (Gemini Pro 1.0)**: NaturalSQL harnesses the power of Gemini Pro 1.0, an advanced Language Model, to understand and interpret natural language queries effectively.

2. **MySQL for Local DB Connection**: NaturalSQL connects to MySQL databases locally, providing users with a familiar and reliable database environment for query execution.

3. **Langchain**: Langchain facilitates the conversion process by mapping natural language queries to SQL structures, enabling smooth communication between the user and the database.

4. **Streamlit**: The Streamlit framework powers NaturalSQL's intuitive user interface, offering a user-friendly experience for interacting with the system and submitting queries.

5. **Few-shot Learning for LLM**: NaturalSQL utilizes few-shot learning techniques to enhance the capabilities of the LLM model, enabling it to adapt and learn from minimal examples provided by the user.

## Getting Started

To begin using NaturalSQL, follow these simple steps:

1. **Provide Database Details**: In the left corner of the interface, enter the necessary details related to your database, including the database username, password, host, and database name.
   
2. **Connect to Database**: Once the system successfully connects to your database, you can proceed to enter your query in natural language format.
![1 database connect](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/d1d0d519-8f27-4b03-9feb-d5c06158d604)


3. **Submit Query**: Enter your natural language query in the provided input field and submit it for processing.

4. **View Results**: NaturalSQL will execute the query against the database and display the results along with the corresponding SQL query used for retrieval.
![2 query 1 llm](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/9c85dd42-dd4e-46ed-8fc6-1deeedfa8b4a)
![3 query 1 mysql](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/36483474-b981-4a45-ab91-72484fcc4f7f)

By leveraging NaturalSQL's intuitive interface and advanced language processing capabilities, data scientists can streamline their workflow and unlock the full potential of their databases with ease.

### Other example for complex natural langauge query with it's SQL verification.

![4 query 2 llm](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/fcd1e1bd-c04a-4632-aa5c-f508e6e5ccf5)
![5 query 2 vs code](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/d3249e99-f4a2-42c2-9f19-2740b5f5f2ee)
![6 query 2 mysql](https://github.com/fenil210/Ask-DB-without-SQL/assets/121050723/60b3a6b5-ece1-4bb1-a93b-0bbbb269441b)






