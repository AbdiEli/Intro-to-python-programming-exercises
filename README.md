# Intro-to-python-programming-exercise (Credit analysis project)

Applicant=input("Please enter the name of applicant. ") 
ApplicantRequest=input("Please enter loan request amount. ") 
Purpose=input("What is your purpose for requesting the loan? Specify if it is for a term loan, working capital and soo on ")
print("Now, move on to credit information. ")

CreditInformation=input("Does the applicant have any current credit relation with other banks? ")
if CreditInformation == "Yes" :
    print("Our bank will do a background check on your credit relation with other banks. ")
if CreditInformation == "No" :
    print("Our bank will do a background check on your credit relation with other banks. ")
if CreditInformation == "I don't know" :
    print("Our bank will do a background check on your credit relation with other banks. ")

Collateral=input("Please enter full information, including details and specifications, evidence, and estimated value of the collateral for the requested loan amount. ")
Estimation=input("Use the engineer's estimation of the collateral; percentage completed and the remaining work should be summarized. ")
print("Move on to complete the applicant's personal background check. ")

BackgroundInformation=input("Enter the applicant's background by summary, shouldn't be very long. ")

GeneralRemark=input("What is your remark on the applicant's data? Is the information enough to process the case?")
if GeneralRemark == "Yes" :
    print("Enter the applicant's data such as personal salary and if the applicant is a business entity, profit and loss account summary is required. ")
if GeneralRemark == "No" :
    print ("Please go ack and try to find as much data to process the case. ")

FinancialRequirement= input("Enter the financial requirement stated by the engineer's estimation and the financing structure needed to give loan. ")

CurrentRequest=input("Enter the applicant's request and analyze based on financing structure and financial analysis. ")

SourceOfRepayment=input("Is the amount of loan amortized monthly below or one third of the applicant's monthly salary? ")
if SourceOfRepayment == "Yes":
    print("Make the recommendation based on certain disbursement conditions to approve the loan. ")
if SourceOfRepayment == "No" :
    print("Further source of repayment must be insured to approve the loan. Loan is not approved. ") 
