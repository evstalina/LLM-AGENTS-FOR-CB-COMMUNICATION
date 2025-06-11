# Synthetic focus group for predicting and improving public reaction to central bank communication
**GitHub Repository: `LLM-AGENTS-FOR-CB-COMMUNICATION`**

During the hackathon, participants will be challenged to create **a synthetic focus group of several LLM avatars of real people** with different sentiments towards the central bank, **calibrate them** on publications that in real life have led to reputational risks for the central bank, and finally **rewrite the test material** with the help of the SFG discussion in such a way that **the created SFG improves its sentiment** towards the text and the central bank.  

# Problem statement 
The general public is one of the most challenging audiences for a central bank. At the same time, it plays a key role in economic decision-making and determines the dynamics of macroeconomic indicators. The higher the trust in the central bank, the lower the inflation expectations and the better the decisions of economic agents. Central banks manage the decisions of agents through communication, which is inevitably associated with increased risks. 

The use of LLM agents for pre-testing communications provides new opportunities for regulators' policy. With such tests, it is now possible to determine in advance how a certain communication will influence the economic decisions of a household. Joint LLM-agents can be used as focus groups to test central bank communication and further improvement.

## 🎯 Algorithm of work on the project, objectives and data

1. Review the relevant literature:

   1. Zhang T. et al. Focus Agent: LLM-Powered Virtual Focus Group // Proceedings of the 24th ACM International Conference on   Intelligent Virtual Agents. – 2024. – С. 1-10.
   3. Krueger R. A. Focus groups: A practical guide for applied research. – Sage publications, 2014.
   5. Filipova, A.G., Abrosimova, E.E., Zubova, O.G. (2025). The method of synthetic focus groups in the context of digital transformation of sociological research. Sociodynamics, 5, 1–17. https://doi.org/10.25136/2409-7144.2025.5.74430
2.	Create LLM avatars for each real person given based on their interviews (a sample of 10 interviews). Ensure a closed loop so that the LLM is not trained on real person interview data.

| № | "Name"     | Confidence in the central bank | Inflation expectations, % | Gender | Age | City | Education | Marital status |
|---|------------|:------------------------------:|:-------------------------:|:------:|:---:|:----:|:---------:|:--------------:|                                              
| 1 | Angelina   |               1                |            N/A            |    F   |  38 |Barnaul|College|Married|
| 2 | Alexey     |               1                |             5             |    M   |  22 |Ekaterinburg|College|Single|
| 3 | Antonina   |               0                |            N/A            |    F   |  65 |Ekaterinburg|College|Widow|
| 4 | Konstantin |              N/A               |            N/A            |    M   |  58 |Barnaul|College|Married|
| 5 | Gleb       |               1                |             25            |    M   |  54 |Ekaterinburg|PhD|Married|
| 6 | Larisa     |               0                |            N/A            |    F   |  46 |Novosibirsk|College|Married|
| 7 | Pavel      |               1                |             50            |    M   |  55 |Vladivostok|Economic college|Married|
| 8 | Viktoria   |               0                |             20            |    F   |  22 |Pskov|College|Single|
| 9 | Mikhail    |               0                |            N/A            |    M   |  65 |Ryazan|College|Married|
| 10 | Igor      |               0                |            N/A            |    M   |  64 |Perm|Economic college|Married|

3.	Calibrate LLM agents on publications that in real life led to reputational risks for the central bank, i.e.:
    1. Agents trusting the CB should take a positive or neutral view of communication treatment.
    2. Not trusting – negatively.
    3. Indifferent ( only ‘Konstantin’) - neutrally.
4. Create a synthetic focus group of 10 LLM-agents, propose a technical solution for working with them. Provide a closed loop in it so that the LLM is not trained on interview data from real people.
5. Discuss the text of the Bank of Russia publication with the focus group ([April Commentary on Consumer Price Dynamics](https://www.cbr.ru/Collection/Collection/File/55880/CPD_2025-4.pdf) - only text, no tables) and improve its quality based on the responses received.

At the end of the work, participants hand over the prompts/text files/codes of successful LLM agents as well as the SFG compilation to the curator. 

---
## ❗ Data Disclamer 

The data is not published in the repository on GitHub and is sent only directly to the team members who will work on the project without the possibility of public distribution of this data. After the project is finished, copies of the original data should be deleted.


The data are .txt files in Russian where real people talk free-form about their consumer behaviour, perceptions of the situation in the economy and attitudes towards past economic crises and the central bank. The files are stored in [a folder on Google Drive](https://drive.google.com/drive/folders/16NP0citkOsa4BYz_XCmaWKQMzvtgDDTq?usp=drive_link). Only team members working on the project will have access to the folder.



## ✔️ Evaluation of outcome

Based on the insights from the synthetic focus group, teams must propose a revised version of the central bank communication. The improved text will be evaluated both qualitatively and quantitatively, including through its re-assessment by the same SFG: does the revised version increase overall favorability among the agents, particularly among skeptics?

Bonus points will be awarded for:
- Innovative prompting strategies.
- Multi-agent coordination mechanisms.
- Inclusion of sentiment-shift tracking over the course of the discussion.

All deliverables — including code, prompts, revised text, and logs of group interactions — must be submitted in reproducible format.
