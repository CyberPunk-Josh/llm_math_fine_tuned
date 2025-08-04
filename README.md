This is a Fine Tuned model that takes a question and answer pair and returns a difficulty level from 1 to 5
For this we tried two approcahes to find the best solution, one using propmr engineering using agpt-4o-mini and anothe rone using a fine tunning approach.
For this we used technologies like:

- Python
- LLM models like gpt-4o-mini

and Python libraries like:
- pandas
- matplotlib
- numpy
- json
- openai

In order to solved questions, I used StackOverflow and the help of chatgpt to solve a bug that I faced with my test class.

For biases metrics I used an integration with web a biases cloud service: [web%biases](https://wandb.ai/).

For the project I decided to keep the test class in the main file just to show the execution of the functions, in a production project the best option is to keep this kind of files in a separate folder called "utils" for a better prokect structure.