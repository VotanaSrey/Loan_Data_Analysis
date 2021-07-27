# Loan Data Analysis
### Data Description
<p>
In this dataset, there are 128258 samples and 47 dimensions, let's take a look to each dimensions:
    <ul>
        <li>id: a unique LC assigned ID for the loan listing.</li>
        <li>loan_amount: The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.</li>
        <li>funded_amount: The total amount committed to that loan at that point in time.</li>
        <li>funded_amount_investor: The total amount committed by investors for that loan at that point in time.</li>
        <li>term: The number of payments on the loan. Values are in months and can be either 36 or 60.</li>
        <li>interested_rate: Interest Rate on the loan</li>
        <li>installment: The monthly payment owed by the borrower if the loan originates.</li>
        <li>loan_grade: LC(letter of credit) assigned loan grade</li>
        <li>loan_sub_grade: LC assigned loan subgrade</li>
        <li>borrower_job_title: The job title supplied by the Borrower when applying for the loan.*</li>
        <li>borrower_length_experience: Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years. </li>
        <li>home_ownership: The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER</li>
        <li>borrower_annual_income: The self-reported annual income provided by the borrower during registration.</li>
        <li>loan_verification_status: Indicates if income was verified by LC, not verified, or if the income source was verified</li>
        <li>date_loan_funded: The month which the loan was funded</li>
        <li>loan_status: Current status of the loan</li>
        <li>borrower_purpose: A category provided by the borrower for the loan request. </li>
        <li>loan_title: The loan title provided by the borrower</li>
        <li>borrower_zib_code: The first 3 numbers of the zip code provided by the borrower in the loan application.</li>
        <li>address_state: The state provided by the borrower in the loan application</li>
        <li>debt_to_income: Debt-to-Income ratio. A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.</li>
        <li>borrower_delinquency_last_2y: The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years</li>
        <li>date_credit_line_open: The month the borrower's earliest reported credit line was opened</li>
        <li>fico_rage_low: The lower boundary range the borrower’s FICO at loan origination belongs to.</li>
        <li>fico_range_high: The upper boundary range the borrower’s FICO at loan origination belongs to.</li>
        <li>number_inquiry_last_6mo: The number of inquiries in past 6 months (excluding auto and mortgage inquiries)</li>
        <li>borrower_delinquency_last_6mo: The number of months since the borrower's last delinquency.</li>
        <li>borrower_delinquency_public_record: The number of months since the last public record.</li>
        <li>number_credit_line: The number of open credit lines in the borrower's credit file.</li>
        <li>number_deliquency_public_record: Number of derogatory public records</li>
        <li>credit_revolve_balance: Total credit revolving balance</li>
        <li>credit_revolve_utilization: </li>
        <li>total_credit_line: Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.</li>
        <li>initial_list_status: The initial listing status of the loan. Possible values are – W (Whole), F (Fraction)</li>
        <li>outstanding_principal: Remaining outstanding principal for total amount funded</li>
        <li>outstanding_pricipal_investor: Remaining outstanding principal for portion of total amount funded by investors</li>
        <li>total_payment: Payments received to date for total amount funded</li>
        <li>total_payment_investor: Payments received to date for portion of total amount funded by investors</li>
        <li>total_receive_principal: Principal received to date</li>
        <li>total_receive_investor: Interest received to date</li>
        <li>toal_receive_late_fee: Late fees received to date</li>
        <li>recoveries: post charge off gross recovery</li>
        <li>collection_recovery_fee: post charge off collection fee</li>
        <li>last_payment_date: Last month payment was received</li>
        <li>last_payment_amount: Last total payment amount received</li>
        <li>next_payment_date: Next scheduled payment date</li>
        <li>last_credit_pull_date: The most recent month LC pulled credit for this loan</li>
    </ul>
</p>
