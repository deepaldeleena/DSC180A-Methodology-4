
# DSC 180A - Methodology Assignment 4

**Name:** Deepal Deleena

**UCSD Email:** ddeleena@ucsd.edu

**Section:** D37 - Agentic AI for Healthcare Research

**Mentor:** Renu Raman

## Quarter 2 Project Proposal Brainstorm Questions

**1. What is the most interesting topic covered in your domain this quarter?**

- Learning how multiple AI agents can work together to extract metadata and understand the meaning behind different datasets and how those could be connected.
- Seeing how our semantic agent correctly interpreted 27 out of 31 columns, but still struggled to identify relationships between datasets with different column names even though they referred to the same thing.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

- I would like to explore how we can improve our agents' ability to identify matching features across different datasets.
- Test whether semantic similarity and embeddings can help identify relationships that our current agent missed.
  
**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

- Include more data quality checks in our metadata agent since it only flagged 2 out of 7 issues we identified during EDA.
- Add checks for undocumented categorical values, unusual measurements, and placeholder zeros to improve the accuracy of the metadata passed to the semantic agent.

**4. What other techniques would you be interested in using in your project?**

- Explore NLP and text embeddings to identify similarities between features with different names or descriptions.
- Use knowledge graphs to organize connections between datasets, clinical features, and their meanings.
