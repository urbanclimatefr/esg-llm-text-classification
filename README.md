# EVALUATING THE PERFORMANCE OF STATE-OF-THE-ART ESG DOMAIN-SPECIFIC PRE-TRAINED LARGE LANGUAGE MODELS IN TEXT CLASSIFICATION AGAINST EXISTING MODELS AND TRADITIONAL MACHINE LEARNING TECHNIQUES

This research investigates the classification of Environmental, Social, and Governance (ESG) information within textual disclosures. The aim is to develop and evaluate binary classification models capable of accurately identifying and categorizing E, S and G-related content respectively.

The motivation for this research stems from the growing importance of ESG considerations in investment decisions and corporate accountability. Accurate and efficient classification of ESG information is crucial for stakeholders to understand the impact of companies on sustainability and to make informed decisions.

The research uses a quantitative approach involving data collection, data preprocessing, and the development of ESG-focused Large Language Models (LLMs) and traditional machine learning (Support Vector Machines, XGBoost) classifiers. Performance evaluation guides iterative refinement until satisfactory metrics are achieved.

The research compares traditional machine learning techniques (Support Vector Machines, XGBoost), state-of-the-art language model (FinBERT-ESG) and fine-tuned LLMs like Llama 2, by employing standard Natural Language Processing performance metrics such as accuracy, precision, recall, F1-score. A novel fine-tuning method, Qlora, is applied to LLMs, resulting in significant performance improvements across all ESG domains. The research also develops domain-specific fine-tuned models, such as EnvLlama 2-Qlora, SocLlama 2-Qlora, and GovLlama 2-Qlora, which demonstrate impressive results in ESG text classification.

Key findings show that fine-tuned LLMs, particularly those utilizing Qlora, achieved average F1-score improvements of 7.37% over classical machine learning models; and 12.30% over FinBERT-ESG. However, the high computational demands of LLMs pose a potential barrier for organizations with limited resources. The research highlights the need for exploring more cost-effective alternatives for specific use cases where the exceptional performance of Qlora-fine-tuned models might not be essential.

The deployment of fine-tuned LLMs like those utilizing Qlora presents several issues. Legally, organizations must navigate intellectual property and licensing agreements; socially, the high computational demands can widen the digital divide by favouring well-resourced entities; ethically, the significant energy consumption of these models raises environmental sustainability concerns; and professionally, there's an increased demand for data scientists to acquire skills in optimizing resource-intensive models to stay competitive.
While this research contributes valuable tools and insights to the field of ESG impact classification, it also presents several avenues for future work. Expanding the training data to include diverse ESG-related text sources and exploring data augmentation techniques enhance model robustness and generalizability. 

Further investigation into alternative fine-tuning methods like RAG and prompt engineering could reveal additional performance improvements. Lastly, utilizing newer and more advanced LLMs like Llama 3 holds potential for even greater accuracy and nuance in ESG classification. This research highlights the significant advancements in natural language processing techniques for ESG information classification. By continuously refining methods and exploring new technologies, future research can contribute to a more sustainable and responsible future.

<img width="296" alt="QLora" src="https://github.com/user-attachments/assets/2f27bf30-be0a-4e76-9e53-22b4122d2bdb" />

<img width="299" alt="table" src="https://github.com/user-attachments/assets/81610a3f-7e0a-4f6a-9104-aa72af8c8c4a" />
