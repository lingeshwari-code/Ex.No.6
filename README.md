# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date: 10.11.2025
# Register no.212223060135
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

#AI Tools Required:

# Explanation:
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

# PY code
```
def query_openai(prompt):
    return "Cloud computing allows businesses to scale easily and reduce costs."

def query_huggingface(prompt):
    return "Cloud computing helps store and use data online instead of one computer."

def compare_outputs(out1, out2):
    print("\n--- AI Tool 1 (OpenAI) ---\n", out1)
    print("\n--- AI Tool 2 (HuggingFace) ---\n", out2)

    if len(out1) > len(out2):
        return "OpenAI provided a more detailed response."
    elif len(out2) > len(out1):
        return "HuggingFace provided a more detailed response."
    else:
        return "Both responses are of similar length."

if __name__ == "__main__":
    user_prompt = "Explain the importance of cloud computing in simple terms."
    openai_output = query_openai(user_prompt)
    hf_output = query_huggingface(user_prompt)
    result = compare_outputs(openai_output, hf_output)
    print("\n--- Actionable Insight ---\n", result)
```

# Output:
<img width="987" height="491" alt="image" src="https://github.com/user-attachments/assets/ec28d2f2-8b3f-44ae-b2e6-55019383216d" />

<img width="1674" height="435" alt="image" src="https://github.com/user-attachments/assets/1b4d4a11-c4af-4374-b56f-a84c0938b784" />

# Result: The corresponding Prompt is executed successfully.
