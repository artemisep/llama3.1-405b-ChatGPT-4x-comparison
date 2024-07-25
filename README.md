# llama3.1-405b-ChatGPT-4x-comparison


this project did a quick test and comparison of the ability of llama3.1-405b with ChatGPT-4, ChatGPT-4o to answer domain specific questions. Lepton.ai provided inference endpoint for llama3.1-405b

07/25. update.  different vendor providing llama3.1-405b inference may have different configurations (FP16, FP8, INT4), and which may affect the results

tried the same prompt/question with X vendor, it appeared the performance decreased, need to check what is the model configuration 
--output from llama3.1-405b from X vendor: docs/q1_answer_llama3.1-405b_possibleQuantizedConfig.docx

07/24

prompt/question:
1. "you are an expert in mechanistic interpretability research, how do you use residual stream for research in mechanistic interpretability"

--output from llama3.1-405b provided at the Emergency Llama 3.1 Hackathon at AGI House 07/23: docs/q1_answer_llama3.1-405b.docx

--output from ChatGPT-4: docs/q1_answer_ChatGPT-4

--output from ChatGPT-4o: docs/q1_answer_ChatGPT-4o

Overall, I find llama3.1-405b did a much better job to help me understand how residual stream works with sufficient technical details.  It provide much more coherent and specific information than both ChatGPT-4 and ChatGPT-4o which tend to pile concept, generalized information.

some important information in llama3.1-405b is missing or not explicitly explained in ChatGPT-4x answers.
for example, I think the following segment in llama3.1-405b's answer is important and interesting but it's missing or not explicitly explained in ChatGPT-4x

llama3.1-405b says:
3. **Path attribution**: I use the residual stream to attribute the model's predictions to specific paths or sequences of computations within the network. This involves analyzing how the residual stream changes as the input propagates through the model, allowing me to identify the most influential components.
