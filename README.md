# LLM Customer Service Representative Output Evaluation

This repository contains a Jupyter Notebook (`compare-llm-outputs.ipynb`) that evaluates the performance of various Large Language Models (LLMs) acting as customer service representatives responding to an irritated customer. The notebook details the process of generating responses from different LLMs and then using another LLM to analyze and rank these outputs.

## Evaluated LLMs (Customer Service Representatives)

The following LLMs were used to generate customer service responses within the notebook:

- **OpenAI 4o mini**
- **Gemini Flash**
- **Deepseek Chat** (Specify model if known)
- **Groq llama-3.3-70b-versatile** (Specify model if known)
- **Ollama llama3.2** (Potentially running a specific open-source model - please specify if so)

The prompts provided to these LLMs, simulating an email from an irritated customer, are included within the Jupyter Notebook.

## Evaluation Methodology

The Jupyter Notebook also contains the process of using **OpenAI 3o mini** to analyze and rank the generated customer service responses. The ranking is based on several key parameters designed to assess the quality of a customer service interaction. These parameters may include (but are not limited to):

- **Empathy:** How well does the response acknowledge and understand the customer's frustration?
- **Clarity:** Is the response easy to understand and free of jargon?
- **Helpfulness:** Does the response offer a clear solution or next steps for the customer?
- **Professionalism:** Is the tone appropriate and professional, even in the face of customer irritation?
- **Completeness:** Does the response address all aspects of the customer's complaint?
- **Efficiency:** Is the response concise and to the point without unnecessary information?

The specific prompts used for both the customer service representative LLMs and the evaluation LLM, as well as the detailed ranking criteria and results, are documented within the `compare-llm-outputs.ipynb` file.

## Repository Contents

- `compare-llm-outputs.ipynb`: This Jupyter Notebook contains all the code for generating LLM responses, evaluating them, and presenting the results.
- `README.md`: The current file, providing an overview of the project.

## How to Explore This Project

To understand the evaluation process and results:

1.  **Open and Run the Jupyter Notebook (`compare-llm-outputs.ipynb`):** This notebook contains all the steps of the experiment, from defining the customer scenario and prompting the various LLMs to the analysis and ranking performed by OpenAI 3o mini. Running the notebook will allow you to see the generated responses and the evaluation output.
2.  **Review the Code and Explanations:** The notebook is likely structured with markdown cells explaining each step of the process. Pay attention to:
    - The prompt used for the customer service representative LLMs.
    - The responses generated by each LLM.
    - The prompt and parameters used by OpenAI 3o mini for evaluation.
    - The resulting rankings and the reasoning behind them.

## Potential Insights and Discussion Points

By examining the Jupyter Notebook, you can gain insights into:

- How different LLMs approach the task of responding to an irritated customer.
- The criteria used for evaluating the quality of these responses.
- The performance of OpenAI 3o mini as an evaluator.
- The potential strengths and weaknesses of different LLM architectures in customer service scenarios.

## Contributing

(Optional) If you'd like to invite contributions or feedback, you can add a section here outlining how others can get involved. For example:

> Feel free to open issues for any questions or suggestions. If you have ideas for further analysis or alternative evaluation methods, please submit a pull request.

## License

(Optional) Include the license under which this project is shared.

---

This revised README is more focused on your single Jupyter Notebook structure. Remember to replace the bracketed placeholders with your specific model details. Good luck!# compare-llm-outputs
One LLM compares and ranks the output generated by other LLMs
