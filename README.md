# AWS Lex Bot Powered by Lambda

With the rise of machine learning and NLP, many companies realize that bots can be used to help alleviate their team's load during peak hours by having bots interact with customers. In this bot, the bot was built on AWS Lex, while the Lambda function that handles the requests was built on AWS Lambda. This bot helps customers decide how to best save for retirement based on age

---

## Technologies 

This bot was built through AWS Lex, while the Lambda function to handle the requests for portfolio recommendations was built on AWS Lambda.

---

## Libraries

Import statements already present in program, refer to them below:

```python
from datetime import datetime
from dateutil.relativedelta import relativedelta
```

---

## Database

This program couldn't run without the following test events:

* ageError.json
* correctDialog.json
* incorrectAmountError.json
* negativeAgeError.json

---

## Results

Bot without Lambda function: 

![AWS_Mod15_wo_Sagemaker_AdobeExpress](https://user-images.githubusercontent.com/107497500/192194479-8632f573-ff1e-4b83-8ed9-00bc2df19ac5.gif)

Bot with Lambda function:

![w_Lambda_AdobeExpress](https://user-images.githubusercontent.com/107497500/192194488-a1492004-936c-418f-a4f2-e75fdc9e0f3c.gif)


---
## Contributors

Thank you for Eric Cardena for teaching Rice's FinTech Boot Camp. He was instrumental in teaching and helping us understand this material. Thank you for Rice for preparing this curriculum and the corresponding data sets that are required to be used. 

**Rishi Prasadha**

**LinkedIn**: https://www.linkedin.com/in/rishi-prasadha-912212133/

**Instagram**: @therishiprasadha

**Twitter**: @RishiPrasadha

---

## Licenses 

MIT
