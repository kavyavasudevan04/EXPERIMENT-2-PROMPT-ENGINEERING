# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
1. Identify different optimization techniques: Rule-based, Cost-based, Heuristic-based.
2. Select multiple test workloads.
3. Simple SELECT queries.
4. Multi-join queries.
5. Aggregation-heavy queries.
6. Apply each optimization technique on the workloads.
7. Document and evaluate results based on execution time, clarity of query plan, and resource consumption.
8. Compare outcomes to analyze which optimization works best in each scenario.


## Output
Query execution logs and performance metrics collected.
Visualized performance comparison charts.
Query plan details for each optimizer type.
<img width="983" height="326" alt="image" src="https://github.com/user-attachments/assets/121922c8-b59f-4b98-ad15-ef6f97428f84" />

## Result
From the comparison, it is evident that:
Rule-based optimization → works adequately for simple queries but lacks efficiency in complex cases.
Heuristic-based optimization → improves execution time moderately but sometimes misses optimal plans.
Cost-based optimization → consistently delivers the best performance with accurate query plans, especially for multi-join and aggregation workloads.
Thus, cost-based optimization is the most effective approach for handling complex database queries, ensuring both performance and resource efficiency.

