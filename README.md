# InsuredGPT
Simple interface for patients and any general policyholders to get their questions answered regarding common insurance policies such as Medicare, Medicaid, Medi-Cal, UC Health Benefits, Anthem Blue Cross, and more. 

## Set-Up

Install all required packages 
```
pip install langchain openai chromadb tiktoken unstructured
pip install "unstructured[pdf]"
```

Create new file "constants.py" and add the following code:
```
APIKEY = <your own OpenAI API key>
```

## Typical Usage
Ensuring that you are in the "InsuredGPT" directory, you can execute the following command
```
python gpt.py <your desired prompt>
#python gpt.py "How much deductibles for Medicare in 2024?"
```