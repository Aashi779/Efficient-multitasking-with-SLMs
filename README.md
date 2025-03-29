# **Efficient Multi-Tasking with Small Language Models (SLMs)**  

## **Overview**  
This project explores the efficiency of **Small Language Models (SLMs)** for multi-task learning, offering a lightweight and cost-effective alternative to **Large Language Models (LLMs)**. We fine-tuned **Microsoft’s Phi-3.5-mini-instruct** to handle three key tasks:  

- **Reasoning** (using the ROPES dataset)  
- **Web Search Summarization** (Google-style retrieval)  
- **Mathematical Problem-Solving** (using the GSM8K dataset)  

Our approach optimizes model performance while maintaining **low computational costs**, making AI more accessible for real-time applications.  

## **Methodology**  
### 🚀 **Techniques Used**  
✅ **Multi-task Fine-tuning** → Improves knowledge transfer across different tasks  
✅ **LoRA Adapters** → Efficient parameter updates without full model retraining  
✅ **Chain of Thought (CoT) Prompting** → Enhances logical reasoning and step-by-step solutions  
✅ **Gradient Clipping & Adaptive Learning Rate** → Ensures stable and efficient training  

## **Results**  
📌 **Reasoning Task:** **75% accuracy**, outperforming Llama-3-1.3B by **3x**  
📌 **Web Search Summarization:** Summary generated in **80.9s**, achieving strong **ROUGE scores**  
📌 **Mathematical Problem-Solving:** **91.51% accuracy**, effectively handling complex calculations  

## **Key Takeaways**  
🔹 **SLMs can match or outperform larger models on focused tasks**  
🔹 **Efficient fine-tuning strategies reduce computational overhead**  
🔹 **Potential for real-time AI applications in education, search, and coding assistance**  

## **Future Scope**  
🚧 **Expanding the model’s multilingual capabilities**  
🚧 **Enhancing real-time coding support & debugging assistance**  
🚧 **Optimizing for domain-specific tasks & personalization**  

## **Contributions & Acknowledgments**  
🙌 This project builds on Microsoft’s **Phi-3.5-mini-instruct** and integrates best practices from recent AI research on multi-task learning. Contributions and suggestions are welcome!  
