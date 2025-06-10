# LLM agents for forecasting public perceptions of central banks
**GitHub Repository: `LLM-AGENTS-FOR-CB-COMMUNICATION`**

During the hackathon, participants will be challenged to create **LLM-agents** of real people using anonymised data from in-depth interviews, as well as their sociodemographic characteristics, and to identify the **connections between inflation expectations and informants' narratives**. These LLM-agents will help in **forecasting public responses to central bank communication**.  

# Problem statement 
The general public is one of the most challenging audiences for a central bank. At the same time, it plays a key role in economic decision-making and determines the dynamics of macroeconomic indicators. The higher the trust in the central bank, the lower the inflation expectations and the better the decisions of economic agents. Central banks manage the decisions of agents through communication, which is inevitably associated with increased risks. 

The use of LLM agents for pre-testing communications provides new opportunities for regulators' policy. With such tests, it is now possible to determine in advance how a certain communication will influence the economic decisions of a household. Joint LLM-agents can be used as focus groups to test central bank communication.

## 🎯 Objective
- **Create an AI avatar** of each agent so they respond as closely as possible to the question about their inflation expectations and trust in the central bank. 
- This requires identifying the main factors influencing this and developing a valid framework for answering these questions, in which new informants will enter the test. In doing so, agents will have to give reasons for their level of trust/distrust, rather than simply saying ‘yes’ or ‘no’. In addition, the raw data from in-depth interviews will have to be cleaned of unnecessary information, keeping in mind the garbage in - garbage out principle.
- At the end of the work, participants hand over the prompts/text files/codes of successful LLM agents to the curator.

---
## ❗ Data Disclamer 

The data is not published in the repository on GitHub and is sent only directly to the team members who will work on the project without the possibility of public distribution of this data. After the project is finished, copies of the original data should be deleted.

## 📥 Data

| Characteristics        | Number of informants | Share of sample |
|------------------------|:--------------------:|:---------------:|
|**City**                                                         |
|  Moscow                |           5          |       9.6%      |
|  Saint Petersburg      |           2          |       3.8%      |
|  Ekaterinburg          |           8          |       15.4%     |
|  Krasnoyarsk           |           5          |       9.6%      |
|  Novosibirsk           |           9          |       17.3%     |
|  Perm                  |           5          |       9.6%      |
|  Pskov                 |           3          |       5.8%      |
|  Stavropol             |           5          |       9.6%      |
|  Vladivostok           |           5          |       9.6%      |
|  Barnaul               |           4          |       7.8%      |
|  Elista                |           1          |       1.9%      |
|**Gender**                                                       |
|  Male                  |           29         |       55.8%     |
|  Female                |           23         |       44.2%     |
|**Age**                                                          |
|  under 25 y.o.         |           7          |       13.5%     |
|  26-35 y.o.            |           10         |       19.2%     |
|  36-45 y.o.            |           12         |       23.1%     |
|  46-55 y.o.            |           13         |       25.0%     |
|  56-65 y.o.            |           5          |       9.6%      |
|  over 65 y.o.          |           5          |       9.6%      |
|**Education**                                                    |
|  Secondary             |           3          |       5.8%      |
|  Secondary specialised |           4          |       7.7%      |
|  undergraduate degree  |           1          |       1.9%      |
|  higher+[^1]           |           36         |       69.2%     |
|  higher economic+[^2]  |           8          |       15.4%     |
|**Household size**                                               |
|  1 person              |           19         |       36.5%     |
|  2 or more persons     |           33         |       63.5%     |
| **Total**              |           **52**     |       **100.0%**|

[^1]: Including non-economic academic degrees.
[^2]: Including economic academic degrees.

The data from the anonymised in-depth interviews are split into train (40 informants) and test (12 informants). 

The data are .txt files in Russian where real people talk free-form about their consumer behaviour, perceptions of the situation in the economy and attitudes towards past economic crises and the central bank. The files are stored in [a folder on Google Drive](https://drive.google.com/drive/folders/1ZeObSPwq7RPZFO86SH1kmT72c7_vwgMF?usp=drive_link). Only team members working on the project will have access to the folder.

Data structure:

1.1. Interviews as texts.

1.2.	Basic sociodemographic characteristics of each informant: gender, age, marital status, household size, city of residence, etc.

1.3.	Quantitative assessment of inflation expectations by each informant (for example: 5%, 10%, 12%, etc.).

1.4.	Binary variable of the informant's response to the question about whether or not he trusts the central bank (there is also a verbal answer to this question with argumentation in the interview text).

## ✔️ Evaluation of outcome
On the test, participants are presented with 12 new agents for which only items 1.1 and 1.2 (text interviews and sociodemographic characteristics) are known. 

Thus, the winner team is defined on the basis of two tests:

<ins>Test 1</ins>: We ask agents ‘What do you expect inflation to be in a year from now?’ and estimate whose inflation expextations are closer to those of real informants. 

<ins>Test 2</ins>: We ask agents ‘Are you rather trust the central bank or not?’

The winner is the team that most accurately identifies the inflation expectations and trust of new informants from their narratives on the test task.
