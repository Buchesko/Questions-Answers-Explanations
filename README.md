# Questions-Answers-Explanations
Quiz JSON File Creator
This program allows users to create a JSON file containing quiz data. The JSON file can be used to store information about the quiz title, module number, questions, and their corresponding answers and explanations.

Usage
Run the script using Python 3.
Follow the prompts to enter the quiz details.
Enter the title and module number for the quiz.
Enter the questions and their respective answers and explanations.
To finish adding questions, enter 'k' when prompted for a question identifier.
Enter the desired name for the output JSON file (without the extension).
The JSON file will be created in the same directory as the script.
Dependencies
This program requires the following:

Python 3.x
The json module (comes with Python standard library)
Example
Here's an example of how the program can be used:

$ python quiz_creator.py
Tytuł: My Quiz
Numer modułu: 1
Podaj identyfikator pytania (lub 'k' aby zakończyć): q1
Pytanie: What is the capital of France?
Poprawna odpowiedź: Paris
Niepoprawna odpowiedź 1: London
Niepoprawna odpowiedź 2: Berlin
Niepoprawna odpowiedź 3: Rome
Wyjaśnienie: Paris is the capital of France.
Podaj identyfikator pytania (lub 'k' aby zakończyć): q2
Pytanie: Who painted the Mona Lisa?
Poprawna odpowiedź: Leonardo da Vinci
Niepoprawna odpowiedź 1: Pablo Picasso
Niepoprawna odpowiedź 2: Vincent van Gogh
Niepoprawna odpowiedź 3: Michelangelo
Wyjaśnienie: Leonardo da Vinci painted the Mona Lisa.
Podaj identyfikator pytania (lub 'k' aby zakończyć): k
Podaj nazwę pliku JSON (bez rozszerzenia): quiz_data
Plik 'quiz_data.json' został utworzony.
In this example, the user creates a quiz with two questions and saves the data to a file named 'quiz_data.json'.

License
This program is licensed under the MIT License.
