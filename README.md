This code will demonstrate the classification tasks using Azure Open AI LLM. Below provides description of this code.

# Introduction

Welcome! In this MLS, we are going to look into the E-commerce aggregators business. Aggregator platforms face multiple challenges due to their unorganised nature. One such problem is the task of categorising products. Since the sellers on the platform aren't organised, they tend to mislabel some of their products. This leads to confusion in the customers leading to dissatisfaction and ultimately revenue loss. The management had tried to educate the sellers on labelling through hand-outs however, that hasn't been successfull. So they are looking to automate labeling using AI.

**Task 1: Auto-Labelling System**

Initially, our focus is on categories with the highest incidence of mislabeling. Currently, we are facing a 27% mislabeling in the system. One of the reasons this is happening is because there are a lot of common words between the skin care and hair care categories. Both of them have words like oil, powder, wash, etc. It is also confusing as sometimes products for body hair can be categorised as skin care and other times as hair care. Similarly, products for scalp can be basketed into skin care or hair care.Our job is to reduce this as much as possible.

1. Skin Care
2. Hair Care

**Task 2: Customer Intent Analysis**

Management also has received concerns about the usability of the website. They aim to enhance the user experience on our platform by gaining insights into the problems customers are facing. One good source of understanding where customers are having trouble is by looking at the concerns raised by customers with call support. Understanding customer intent in chat support messages will inform the management where improvements are needed in the platform's UI/UX, making navigation and usage more intuitive.

The data science team is entrusted with classifying customer intent into the relevant categories.

Due to resource constraints, we must utilize a small dataset for model training.

The code will demonstrate classification tasks **Task 1: Auto-Labelling System** and **Task 2: Customer Intent Analysis** using zero-prompt, few-shot and COT techniques. 

**Steps involved**
 
1. Assemble and explore data
2. Derive prompts
3. Evaluate prompts

**Data set used** 
Auto_labeling.csv
