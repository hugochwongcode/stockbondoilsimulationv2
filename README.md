# Portfolio Simulator Version 2 with AI NLP Models
This repository contains code for a financial simulation utilizing three different Natural Language Processing (NLP) models: Community GPT2 XL, MetaLlama 2 13b-chat-hf and AdaptLLM finance-chat. These models are accessible through Hugging Face's model hub.

## Requirements
Before running the code, ensure you have the following dependencies installed:
1. PyTorch
2. Transformers
3. Hugging Face Hub

You'll also need to register for a Hugging Face account and obtain an access token to use the models.

## Natural Language Processing (NLP) model
1. GPT2 XL model https://huggingface.co/openai-community/gpt2-xl
2. MetaLlama 2 13b-chat-hf https://huggingface.co/meta-llama/Llama-2-13b-chat-hf 
3. AdaptLLM finance-chat https://huggingface.co/AdaptLLM/finance-chat

## Usage
To use the financial simulation, follow these steps:
Clone the repository to your local machine.
Open the code in an IDE like Visual Studio Code.
Run the desired script to initiate the financial simulation.

Step 1: Understanding the Simulation
Before you begin, it's essential to understand what this financial simulation offers. This simulation allows you to model the performance of a portfolio consisting of stocks, bonds, and oil over a specified period. You can adjust various parameters such as initial balance, allocation percentages for each asset class, simulation duration, and your risk tolerance level.

Step 2: Running the Simulation
Run the Code: Ensure you have the necessary libraries installed (NumPy, Matplotlib, Seaborn, Hugging Face Transformers). Then, run the provided Python code.

Input Parameters: Once the code is running, you'll be prompted to input several parameters:
Initial Balance: Enter the amount of money you want to start with.
Allocation Percentages: Specify the percentage of your initial balance allocated to stocks, bonds, and oil. Ensure the total allocation percentage sums up to 1 (or 100%).
Simulation Duration: Enter the number of years for which you want to simulate the portfolio.
Steps per Year: Define the number of simulation steps per year.
Risk Tolerance Level: Choose your risk tolerance level: low, medium, or high.
Simulation Execution: After providing the input parameters, the simulation will run. You'll see visualizations of the simulated portfolio's performance over time, including the total portfolio balance and individual asset class balances.

Step 3: Analyzing the Results
Visualizations:
The first visualization shows the total portfolio balance over time.
The second visualization displays the balances of each asset class (stocks, bonds, oil) over time.
Correlation Matrix:
You'll also see a heatmap representing the correlation matrix between different asset classes. This helps you understand how these assets move in relation to each other.
Description:
Finally, the simulation provides a description of the simulated portfolio's performance based on historical returns, volatility, and your risk tolerance level. This description can provide insights into the portfolio's behavior and help you make informed decisions.

## Demo
To demonstrate the usage of the GPT2 XL model, a sample script 'financial_simulation_with_GPT2XL.ipynb' is provided. This notebook showcases how to interact with the GPT2 XL model for financial simulation purposes. However, note that the result may not be satisfactory due to the limitations of the model or the training data.

## Hardware Limitations
Please note that running the scripts for MetaLlama 2 13b and AdaptLLM Finance-Chat models may require substantial computational resources. If your laptop is not powerful enough to run these scripts, consider utilizing cloud-based solutions or running the code on a more robust system. Additionally, I am limited by my laptop's hardware capabilities and may not be able to personally run these resource-intensive scripts.

## Acknowledgments
Special thanks to Will Edwards, instructor at Cantek IT Program, for his invaluable guidance and support in teaching data analytics concepts. Will Edwards is also the founder of Bright Tapestry Data, where innovative work is being pursued. Explore more about Bright Tapestry Data at brighttapestrydata.com/people.

## Contact
For any inquiries or assistance, feel free to reach out:
Email: hugochwong123@gmail.com
LinkedIn: linkedin.com/in/hugochw/

## License
This project is licensed under the MIT License - see the LICENSE file for details. The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). It allows users to do almost anything they want with the code, including modifying, distributing, and using it for commercial purposes, as long as they include the original copyright and license notice.

Disclaimer: This project is for educational and research purposes only. Always consult with a financial advisor before making any financial decisions.
