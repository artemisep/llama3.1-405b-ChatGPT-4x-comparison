# llama3.1-405b-ChatGPT-4x-comparison
This project did a quick test and comparison of the ability of llama3.1-405b with ChatGPT-4, ChatGPT-4o to answer domain specific questions. Lepton.ai provided inference endpoint for llama3.1-405b at the Emergency Llama3.1 Hackathon at AGI House on 07/23.
*please note that different vendor providing llama3.1-405b inference may have different configurations (FP16, FP8, INT4), and which may affect the results

prompt/question:
1. "you are an expert in mechanistic interpretability research, how do you use residual stream for research in mechanistic interpretability"
Overall, I find llama3.1-405b did a much better job to help me understand how residual stream works with sufficient technical details.  It provide much more coherent and specific information than both ChatGPT-4 and ChatGPT-4o which tend to pile concept, generalized information.

some important information in llama3.1-405b is missing or not explicitly explained in ChatGPT-4x answers.
for example, I think the following segment in llama3.1-405b's answer is important and interesting but it's missing or not explicitly explained in ChatGPT-4x

llama3.1-405b says:
3. **Path attribution**: I use the residual stream to attribute the model's predictions to specific paths or sequences of computations within the network. This involves analyzing how the residual stream changes as the input propagates through the model, allowing me to identify the most influential components.

To view detailed answers in browser instead of downloading pdf file here, please go to artemisep.github.io


