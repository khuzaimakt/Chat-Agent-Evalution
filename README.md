**LLM Chat-Agent Evaluation**

An online chat agent made using LangGraph and LangChain is evaluated on multiple metrics. Evaluation pipeline developed to evaluate the LLM's performance using different evaluation measures such as Toxicity, Biasedness, Hallucination, Relevance and Faithfulness. Using prompt engineering the LLM was prompted to generate a referral letters based on patient's data provided. The generated referral letter was than evaluated using a ground truth referral letter. Various libraries including Pheonix-Eval, MLFlow, ContinuousEval and DeepEval were tested and implemented.

Garak Auto-Red Team was also implemented and the given agent was evaluated for toxicity using Garak ATR.

Moreover GuardRails-Ai were implemented for the chatagent to invalidate the inputs specifying for harmful responses.
