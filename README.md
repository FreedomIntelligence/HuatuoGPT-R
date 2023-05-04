# HuatuoGPT-R: Retrieval-Augmented HuatuoGPT

# 🔍Introduction

HuatuoGPT-R is a retrieval-augmented version of [HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT), designed to provide more effective and safer diagnostic outcomes for patients by referencing a vast collection of real-world physician consultation data. This mitigates the risks posed by potential harmful diagnoses or suggestions arising from language model hallucinations. In this repository, we provide:

1. **HuatuoGPT-R Retrieval Instruction Dataset**: These instructions are built upon [Huatuo-26M](https://github.com/FreedomIntelligence/Huatuo-26M), the largest-scale chinese medical QA dataset. These instructions enable you to fine-tune your model to use the Huatuo-26M database to deliver more reliable and accurate responses.

2. **HuatuoGPT-R Model**: We release our model and retriever weights to make HuatuoGPT-R accessible to everyone.

3. **Evaluation Metrics for Effectiveness and Safety**: A key challenge in employing language models for real-world medical applications lies in guaranteeing safe and effective suggestions or diagnoses, akin to a medical professional. Medical language models can pose safety concerns if they generate diagnoses or prescriptions based on hallucinations or insufficient domain knowledge. Overly focusing on safety could limit the model's ability to offer valuable input in a diagnostic setting. In this repository, we offer more reasonable and comprehensive evaluation methods to better assess the performance of language models in medical consultation scenarios.

   

# 📚Data
### Database
-  Huatuo-26M

### Instruction data
-  Retrieval Instruction Dataset



# 👨‍⚕️Models

-  HuatuoGPT-R
