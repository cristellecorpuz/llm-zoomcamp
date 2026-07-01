# Q1 Context Engineering
After comparing the generated answers between Chatgpt and Kestra's AI Copilot, I concluded that Kestra's AI copilot has generated better Kestra flows while chatgpt's has to be debugged before execution.
# Q2 RAG vs. No Rag
Non-rag response is vague, generic, or possibly fabricated since the model has only its training data to rely on.
# Q3 Token usage — short summary
Here is the output after running the 4_simple_agent.yaml with summary_length = short:

Multilingual Agent:
- Input tokens: 282
- Output tokens: 74
- Total tokens: 356

English Brevity Agent:
- Input tokens: 89
- Output tokens: 39
- Total tokens: 128

# Q4 Token usage — long summary
Here is the output after 4_simple_agent.yaml again with summary_length = long:

Multilingual Agent: ;long
- Input tokens: 282
- Output tokens: 214
- Total tokens: 496

English Brevity Agent:
- Input tokens: 229
- Output tokens: 39
- Total tokens: 268

# Q5 Modifying a Flow
After changing the english_brevity to ask exactly 3 sentences and with summary_length = long here is the result:

Multilingual Agent:
- Input tokens: 282
- Output tokens: 199
- Total tokens: 481

English Brevity Agent:
- Input tokens: 214
- Output tokens: 87
- Total tokens: 301

# Q6 Best Practices
After studying the lessons in module 3 and applying what I learned through this homework, I concluded that using traditional task-based workflows for predictability and auditability is most appropriate for producing workflows.

