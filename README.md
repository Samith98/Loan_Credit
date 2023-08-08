# Loan_Credit
## Business Understanding
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.<br><br>
When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:<br>
<ul>
<li>If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.</li>
<li>If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.</li>
</ul>
The data contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:<br>
<ol>
  <li>
  <strong>The client with payment difficulties:</strong> he/she had late payment more than X days on at least one of the first Y instalments of the loan the sample.
  </li>
  <li>
    <strong>All other cases:</strong> All other cases when the payment is paid on time.
  </li>
</ol>
When a client applies for a loan, there are four types of decisions that could be taken by the client/company):<br>
<ol>
  <li><strong>Approved:</strong> The Company has approved loan Application</li>
  <li><strong>Cancelled:</strong> The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client, he received worse pricing which he did not want.</li>
  <li><strong>Refused:</strong> The company had rejected the loan (because the client does not meet their requirements etc.).</li>
  <li><strong>Unused offer:</strong>  Loan has been cancelled by the client but at different stages of the process.</li>
</ol>

## Data 
<ol>
  <li><strong>application_data.csv:</strong> contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.</li>
  <li><strong>previous_application.csv:</strong> contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.</li>
  <li><strong>columns_description.csv:</strong> is data dictionary which describes the meaning of the variables.</li>
</ol>

## Summary
<img src="./images/incorrect_data.jpg">
