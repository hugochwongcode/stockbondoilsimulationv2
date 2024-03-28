# Portfolio Simulator version 2
Version 2 leverages OpenAI GPT-2 for insightful analysis. Users can define investment parameters to simulate portfolio growth and receive detailed recommendations, including insights from the Capital Asset Pricing Model (CAPM), to optimize their investment strategies.

## Features
- Simulate portfolio growth based on user-defined parameters.
- Generate detailed descriptions of portfolio performance using OpenAI GPT-2.
- Provide recommendations for optimizing investment strategies, including insights from the CAPM.

## Usage on Google Colab
1. Download the IPYNB file into your local machine
2. Upload it to the Google Colab 
3. Run the simulation by executing the necessary cells.
4. Input values for parameters:
   - Initial Balance: The starting amount of money in the portfolio
   - Stock Allocation: The percentage of the portfolio allocated to stocks
   - Bond Allocation: The percentage of the portfolio allocated to bonds
   - Oil Allocation: The percentage of the portfolio allocated to oil investments
   - Number of Years: The duration of the simulation in years 
   - Number of Steps per Year: The number of steps or intervals per year for simulating portfolio growth 
   - Stock Drift (Mu): The average expected return per step for stocks 
   - Stock Volatility (Sigma): The standard deviation of returns per step for stocks 
   - Bond Drift (Mu): The average expected return per step for bonds 
   - Bond Volatility (Sigma): The standard deviation of returns per step for bonds 
   - Oil Drift (Mu): The average expected return per step for oil investments 
   - Oil Volatility (Sigma): The standard deviation of returns per step for oil investments
5. View the generated portfolio growth visualization and accompanying description.

## Output
The Portfolio Simulator generates visualizations of the portfolio growth over time, including total portfolio balance and balances for each asset class (stocks, bonds, and oil). Additionally, it provides a textual description of the portfolio performance and insights.

## Acknowledgments
This project utilizes the OpenAI GPT-2 model for text generation and incorporates concepts from the Capital Asset Pricing Model (CAPM) for portfolio analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details. The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). It allows users to do almost anything they want with the code, including modifying, distributing, and using it for commercial purposes, as long as they include the original copyright and license notice.

## Contact
For any inquiries or assistance, feel free to reach out: Email: hugochwong123@gmail.com Linkedin: https://www.linkedin.com/in/hugochw/

