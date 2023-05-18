# # Title: Trust Game with Risk
## Project information
- **Author**: Ni Zheng, Computational Design/Social Policy, 2026, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set No. or Final Project for [COMPSCI/ECON 206 Computational Microeconomics, 2023 Spring (Seven Week - Second)](https://ce.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: [How to Acknowledge?](https://www.scribbr.co.uk/thesis-dissertation/acknowledgements/)
[notes: please include all professors, students, and staff who have contributed to your completetion of the project.]

- **Improvement of PS1 and PS2**
- *For PS1*
- added in-text citations and references
- read Pareto Efficiency reltated articles and improved the solution concept and strategies
- described oTree code part
- polished the writing of the project

- *For PS2*
- provided a normal form and matrix game, and it's evaluation
- corrected the format of Overleaf and reupdated
- **Project Summary**: 
  - **Project Summary**
  - In the trust game, player A and player B have the choices of "Trust" or "Betray", and they get different results of payoff accordingly. Nash Equilibrium can be achieved when both of players adopt strategies that maximize their own expected interest. However, in the real-world practice, players tend to consider more external factors, especially the risk in trading-off. Thus, Nash Equilibrium is not a comprehensive way to analyze the outcome and potential strategies of players. This project will further analyze the behaviors of players with the sense of risk aversion in the trust game.
  - **Background and Motivations**
  - **Literature Review**
  - There have been studies examining the factors that influence individuals' decision-making in trust/investment games, including gender, cultural and age factors (Buchan et al., 1999, 2008; Cox & Deck, 2006, etc.). Also, several studies (Anderhub et al., 2002; Dickhaut et al., 2008, etc.) have focused on how game behavior changes with increasing repetitions. Furthermore, there is substantial research questioning the interpretation of "trust." Cox (2004) suggests that individuals may act with pure altruism, simply intending to benefit others, regardless of whether the other party reciprocates. Ben-Ner and Putterman (2001), on the other hand, argue that the willingness to trust is at least partly linked to a willingness to take risks. Is the investment decision in trust/investment games, which are designed with anonymous one-shot interactions, equivalent to taking a risky gamble (Eckel & Wilson, 2004)? Bohnet and Zeckhauser (2004) found that trust in others is not only influenced by factors such as risk, consideration for others, and efficiency preferences, but also takes into account the costs of betrayal that go beyond monetary losses.
- **Research Questions**
  - **Why is it important to consider the influence of RISK on players’ behaviors or strategies in the trust game?**
RISK reflects the inherent uncertainty and potential consequences that individuals may face when making decisions in real-life situations. It’s significant because it impact individual’s decision-making strategies because people usually have different risk attitudes. They may adjust their behaviors based on their perception of risk in the trust game. 
  - **What’s  the different between the new solution concept and Nash Equilibrium?**
The new solution concept, which considers risk, goes beyond the traditional Nash Equilibrium. While Nash Equilibrium focuses on the stability of strategies when no player has an incentive to unilaterally deviate, the new solution concept incorporates risk and analyzes how risk preferences shape players' behaviors and strategies. It considers strategies that maximize expected utility or expected payoff, taking into account players' risk attitudes. 
  - **How does RISK work in the trust game?**
Individuals with different risk attitudes keep varying levels of willingness to trust or invest. Risk-averse players might be more cautious and hesitant to take risks, leading to lower levels of trust or investment. On the other hand, risk-seeking players may be more inclined to take higher risks and exhibit more trusting or investing behaviors.
Players may assess the potential risks associated with trusting or investing, considering the reliability and past experiences. Players may adjust the level of trust or investment accordingly.
Players may use risk management strategies to mitigate potential losses or maximize potential gains, such as diversifying investments, setting limits on trust or investment amounts, and adjusting behaviors based on the perceived risk-reward trade-off.

- **Application Scenario**
  - **Game Environment**
  - The game involves two players facing an investment and payoff problem, with A making investment decisions and generating profits or losses, and B making decisions regarding the allocation of the payoff.
The two anonymous collaborators are situated within an investment environment, where one person, acting as the sender, possesses a certain amount of funds and must decide how much money to invest. The investment amount generates profits or losses according to certain rules, and it is the responder, the other person in the interaction, who decides how to allocate the resulting gains or losses between the sender and responder. 
Through this process, the sender's final reward is the remaining amount after deducting the investment amount from the initial funds, plus the portion allocated by the responder from the investment outcome. The responder's final reward is the portion of the investment outcome allocated to themselves. This game delineates a scenario where returns are contingent on investment and involves the element of risk.

- **Methodology**
  - Trust Game with Risk will be based on 3 assumptioins
  - The sender's final reward faces uncertainty due to the **responder's uncertain allocation behavior**. In this situation, the investment result is deterministic and can double the sender's investment amount, indicating a profitable investment. However, the responder's allocation behavior is uncertain.
If the responder allocates 3/4 of the profit to the sender, the sender's final reward (F-X+2X*3/4) will be greater than the initial funds (F).
If the responder only allocates 1/4 of the profit, the sender's final reward (F-X+2X*1/4) will be less than the initial funds (F). The more the sender invests, the more the responder will receive.
  *Evaluation:* This situation shows that the sender's final reward faces uncertainty, which is caused by the responder's behavior. The sender's reward can vary depending on how the responder distributes the profits. 

  - The sender's final reward faces uncertainty due to the **uncertain investment results**. The investment can either generate significant profits or losses. In this situation, the responder's allocation behavior is deterministic, where they evenly split the investment outcome with the sender.
If the investment is profitable and results in four times the investment amount, the responder will return half of the profit (4X*1/2) to the sender while keeping the other half (4X*1/2) as their final reward. Similarly, if the investment incurs losses and results in negative two times the investment amount, the responder will make the sender share half of the loss (-2X*1/2) while shouldering the other half of the loss (-2X*1/2). We aim to control the probability of profitable investment at 2/3 and the probability of losses at 1/3, maintaining consistent expected values for the investment outcomes.
  *Evaluation:* It provides an opportunity to explore risk preferences, risk-taking behavior, and risk aversion in the context of trust games.

  - The sender's final reward faces uncertainty arising from the **combination of the two sources of uncertainty in Situations 1 and 2**. In this situation, there are four possibilities for the sender's final reward: (F-X+(-2X)*1/4, F-X+(-2X)*3/4, F-X+(4X)*1/4, F-X+(4X)*3/4). Compared to Situations 1 and 2, where there is only one source of uncertainty resulting in two possibilities, the uncertainty is greater in this situation.
  *Evaluation:* The complex risk situation provides an insight into the interplay between different sources of risk and their effects on decision-making strategies in trust games. It gives a nuanced understanding of how individuals navigate and adapt to intricate risk scenarios.

- **Results**
  - <img width="459" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/csecon206_Jenny_finalproject/assets/125801773/7fc0fa2c-c1c9-45f1-8d44-990e1a55e5fd">
  - The trust game with risk adds a new dimension to the traditional trust game by considering the impact of risk on players' decisions. It provides insights into decision-making under uncertainty and its influence on trust-related interactions.
In real-life applications, this game can help explain investment choices, and risk-taking tendencies. By studying different risk scenarios and equilibrium, we can get a deeper understanding of human behavior in uncertain situations and can develop strategies to enhance trust and manage risks in various contexts.
  - [Intellectual Merits and Practical impacts of your project.]
  

### Code
- oTree Experimental Code 

### Spotlight
- Posters
- ![Trust Game with Risk](https://github.com/Rising-Stars-by-Sunshine/csecon206_Jenny_finalproject/assets/125801773/161b5a07-e84e-40c9-a250-189d293cb7b1)
- Slides&Presentations
  Please check files uploaded.
- Review articles
  The paper "Trust, risk and betrayal" by Iris Bohnet and Richard Zeckhauser explores the decision-making process involved in trusting strangers in one-shot interactions. The authors investigate whether trusting someone is equivalent to taking a risky bet or if it entails an additional risk premium to account for the potential costs of betrayal. They compare a binary-choice Trust game with a structurally identical Risky Dictator game, both offering different outcomes. The researchers elicit individuals' minimum acceptable probabilities (MAPs) of receiving a good outcome in the Trust game, where they would prefer to take the gamble rather than a sure payoff.
  
  The paper acknowledges that the risk preferences measured within the context of the Trust game might be influenced by expectations of trustworthiness and the involvement of another person in determining the outcome. To address these concerns, the authors use a risky-choice task unrelated to trust decisions as a basis for comparison. They also introduce a third treatment, the Risky Dictator game, to replicate the element of payoffs going to two players without the trust component.

- My innovation and inspiration

  For the expansion of Analysis, the previous study focused on analyzing trust behavior based on factors such as gender, culture, age, and repetition of games, my project goes beyond by examining the influence of risk on players' behaviors and strategies. By considering risk aversion, I aim to provide a more comprehensive understanding of decision-making strategy in trust games.

  The traditional Nash Equilibrium is a stable strategy where players have no incentive to unilaterally deviate. In my project, I introduce a new solution concept that incorporates risk. Instead of solely focusing on stability, my concept analyzes how risk preferences shape players' behaviors and strategies.

  In terms of the research questions design, my project explores the importance of considering the influence of risk on players' behaviors or strategies in the trust game, which highlights the novel perspective the study by emphasizing the impact of risk aversion on decision-making. Additionally, I investigate the workings of risk in the trust game, including how individuals with different risk attitudes approach trust and investment scenarios.

  For Methodology, my project introduces a Trust Game with Risk based on three assumptions. By incorporating uncertainty from the responder's allocation behavior, uncertain investment results, and their combination, I create different risk scenarios. This methodology allows for a nuanced exploration of risk preferences, risk-taking behavior, and decision-making strategies in the context of trust games.

### More about the Author
- headshot
![1683779845881](https://github.com/Rising-Stars-by-Sunshine/csecon206_Jenny_finalproject/assets/125801773/01cd4b4d-d9c2-4602-b125-f2f7ce18d39f)

- self-introduction
Hi, I am Ni(Jenny) Zheng from Shanghai. My intended major is Computational Design with track in Social Policy. In the future, I'd like to dig deeper into computational social science (economics/environmental science) and do some quantitative research.

- Final reflections 
  - **Intellectual growth:** Through my in-class projects, I gained valuable insights into the intersection of economics and computer science, which expedited the Nash equilibrium solutions and outcomes for various games. This interdisciplinary approach empowered me to employ more intricate game models.

By incorporating computer science into economics, I realized that Nash equilibrium has limitations in analyzing real-world situations. Shifting the focus away from the traditional rational economic man theory and single-round games, I discovered alternative solutions and add risk to the trust game.

  - **Professional growth:** Throughout my research, I honed my skills in using game theory tools related to SPNE and other economics-related applications, while also exploring theories from computer science and social science. This interdisciplinary approach revealed gaps in existing theories and enabled me to propose novel solutions.

  - **Living a purposeful life:** I have learned a lot about how to propose an idea and do a research based on previous studies. It's a meaningful way for me to learn professional research methods, which is very helpful for my future academic career.
  
### References

- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

Cesarini, David, Christopher T. Dawes, James H. Fowler, Magnus Johannesson, Paul Lichtenstein, and Björn Wallace. 2008. ‘Heritability of Cooperative Behavior in the Trust Game’. Proceedings of the National Academy of Sciences 105 (10): 3721–26. https://doi.org/10.1073/pnas.0710069105.

Ashraf, Nava, Iris Bohnet, and Nikita Piankov. 2003. ‘Is Trust a Bad Investment?’ Working Paper Series, Working Paper Series, , November. https://ideas.repec.org//p/ecl/harjfk/rwp03-047.html.

Stiglitz, Joseph E. 1982. ‘Self-Selection and Pareto Efficient Taxation’. Journal of Public Economics 17 (2): 213–40. https://doi.org/10.1016/0047-2727(82)90020-2.

Bohnet, Iris, and Richard Zeckhauser. 2004. ‘Trust, Risk and Betrayal’. Journal of Economic Behavior & Organization 55 (4): 467–84. https://doi.org/10.1016/j.jebo.2003.11.004.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

