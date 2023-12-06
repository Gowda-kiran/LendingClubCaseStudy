# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
> The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
  
This project is a based on doing EDA using the lending club dataset to do analysis and predict whether a loan will be defaulted or not.
- What is the background of your project?

The largest online loan marketplace, specializing in personal loans, business loans, and medical procedure financing, offers borrowers the convenience of accessing lower interest rate loans through a streamlined online interface.
The primary concern lies in the identification and handling of 'risky' applicants, as extending loans to individuals with a higher likelihood of default poses a substantial threat to the company's financial stability. The term 'charged-off' is attributed to customers who, unfortunately, fall into the category of defaulters, causing a substantial financial loss to the lending institution.
- What is the business probem that your project is trying to solve?
  
By leveraging the findings from EDA, we aim to implement effective measures that not only reduce credit loss but also foster a more resilient and sustainable lending environment for our online loan marketplace.
- What is the dataset that is being used?
  
The dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011.

## Technologies Used
- Pandas - version 1.3.4
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3


## Conclusions
- Key Predictive Factors for Identifying and Preventing Loan Default and Credit Loss:

1)DTI Ratio:
Leveraging the Debt-to-Income Ratio (DTI) in our risk assessment model is essential, as a high DTI signals potential financial strain, serving as a key predictor for defaults. Setting strategic thresholds and integrating DTI analysis during loan approval enables precise evaluation, minimizing credit loss by gauging applicants' financial stability.

2)Grades:
The grading system is central to assessing borrower creditworthiness; a thorough analysis of historical performance in different grades unveils patterns linked to defaults.

3)Verification Status:
Enhancing the verification process can significantly contribute to reducing defaults. By placing a premium on applications with verified information, we can instill greater confidence in the reliability of borrower data, thereby minimizing the risk of credit loss.

4)Annual income:
Annual income serves as a fundamental indicator of a borrower's financial capacity. Integrating a thorough analysis of annual income into our risk assessment model allows for a more comprehensive understanding of an applicant's ability to meet repayment obligations

5)Pub_rec_bankruptcies:
Examining an applicant's public records, especially bankruptcy history, is paramount in gauging their financial stability and risk of default. Implementing stringent scrutiny and potentially adjusting lending terms for individuals with a history of bankruptcies can be an effective strategy in mitigating credit loss.

- Additional considerations for finding loan defaults can include:
  
1)Borrowers residing mostly in rural areas.

2)Borrowers falling within the annual income range of 50,000 to 100,000.

3)Borrowers with a history of Public Recorded Bankruptcy.

4)Borrowers assigned lower grades (E, F, G), they can be considered as a higher risk profile.

5)Borrowers having high Debt-to-Income ratios.

6)Borrowers having work experience of 10 years or more.



## Acknowledgements
- This assignment is from Upgrad IIIT B AI & ML Program  gives an idea about how real business problems are solved using EDA.
- In this case study, apart from applying the techniques I have learnt in EDA, It has helped me to develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Contact
Created by [@Gowda-kiran] - feel free to contact me!


## License 
- This project is open source .
