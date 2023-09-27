﻿
# Boujiee Benji's Black Beans

### Overview

You are a data analyst for **Boujiee Benji's Black Beans**, a boutique black bean wholesaler that sells to regional restaurants. The company prides itself on top-tier quality and excellent customer service, knowing that many restaurants they sell to can find a more affordable alternative if need be. At the start of the year in January, the CTO introduced new software for the sales team to use when logging recurring purchases from restaurants. Unfortunately, the software was rolled out with a bug that ultimately affected Boujiee Benji's financial results for the year. It is your job to calculate the impact this bug had on the business.

### Data

The CTO has given you a limited dataset to work with. The dataset is a list of numbers from the month of January, the first month the new software was in use. This is what you've been told about the data:


- The list represents all orders placed in January. No customers who placed an order in January changed their order for the entire year.
- Each element in the list represents one customer.
- The numeric value of each element represents how many bags of beans that customer ordered.
- One bag of beans costs $40
- The software was supposed to log any numeric value as an **integer**.
- Any numeric value that is not an integer was affected by the bug.
- Any numeric value that is a string resulted in an incorrect order being placed. Customers that experienced an incorrect order were given a 15% discount on all orders placed for the year.

### Assignment

**YOU CAN ONLY USE THE PYTHON STANDARD LIBRARY, AKA BUILT-IN FUNCTIONS, TO ANSWER THE FOLLOWING QUESTIONS**

- Importing pandas, numpy, or any other library is not allowed.
- Refer to the [python standard library documentation](https://docs.python.org/3/library/index.html) if necessary.

**Leadership wants you to answer the following questions:**

1. What percentage of customers were affected by the bug? What percentage of customers experienced incorrect orders caused by the bug?
2. How much money did the company lose through discounts in January because of the bug?
3. Boujiee Benji's had targeted a 14% monthly customer increase and a 20% monthly revenue increase by the end of the year. Instead, viral TikToks resulting from the bug caused customer growth to be only 6% and revenue growth to be 9%. Quantify how the bug affected the company's growth goals.
4. The CEO of Boujiee Benji's video calls you on Teams, without messaging first, and tells you that they think the CTO is hiding something. They suspect the CTO has hidden 20% of the customers affected by the bug from you. The CEO want's you to re-answer question 2, with the assumption that each hidden customer ordered 3 bags of beans in January.
