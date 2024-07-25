# pearmill-playground-test
This is just a fun repo to keep some sql queries!

# Ways to Run:

## 1. Easiest way:
  a. The solucion can be accessedon Google Colab [here](https://colab.research.google.com/drive/1q5FSdZb0vfWBkkwqrkyVVzkcuR9l8AjB?usp=sharing). (My Suggestion)


## 2. Suppose you want to run locally.

1. **Install Python**: Ensure you have Python installed on your machine, ; download here: python.org2. **Set Up a Virtual Environment**:

    ```sh
    python -m venv venv
    ```

3. **Activate the Virtual Environment**:
    - On Windows:
        ```sh
        .\venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install Required Dependencies**:
    - Install duckdb
        ```
        pip install duckdb
        ```

5. **Clone the Repository**:
    - Ensure you have Git installed on your machine.
    - Clone the required repository:
        ```sh
        git clone https://github.com/murillo-ro-silva/pearmill-playground-test.git
        ```

6. **Run the Script**:
    - Ensure the cloned repository and your script are in the same directory.
    - Run the script:
        ```sh
        python pearmill_sql_questions.py
        ```

Ensure you replace the path to the CSV file (`./pearmill-playground-test/data.csv`) with the correct path if necessary.
