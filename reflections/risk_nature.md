# Agile
# LO3.9.1.1
## Insight from data
### Determine the nature of risk and describe how to respond to risks.

In this reflection, I will try to write what I learned from articles in the cybersecurity and security domains and how I will implement that knwoledge into my college project. My team embarked on a design thinking project, setting out to create a secure database and an accessible API. Our primary focus is safeguarding the database against potential risks while exploring techniques to manage these risks effectively. As a part of my commitment to this project, I've delved into understanding the crucial distinctions between risk and threat. 

I researched to understand the nuances between threats, vulnerabilities, and risks in the cybersecurity domain. Understanding these concepts is essential. In simple terms, a threat is any element that exploits system weaknesses to cause harm or gain unauthorized access to valuable assets. (Glover, 2023) Vulnerabilities represent these weaknesses, rendering the system susceptible to threats. Risk, in this context, pertains to the likelihood of suffering losses or harm due to a threat.[LO3.9.1.1] The article also delves into various types of threats and guides safeguarding against them, advocating practices such as regular threat assessments, penetration testing, and vulnerability scanning to identify and mitigate risks.

In another article I read, the distinction between risk and threat in the context of security is explored, based on the type of vessel and operation. In simpler terms, risk refers to undesirable events, encompassing elements of uncertainty, potential consequences, and impacts, while a threat involves an expressed intention to cause harm or loss.[LO3.9.1.1] (Salim, 2023) The article describes the process of conducting threat and risk assessments, utilizing various tools and methodologies to aid in decision-making. It introduces a valuable formula, "risk = threat x vulnerability x consequence," which effectively evaluates risk levels in different scenarios.

Based on these articles, I've come to understand risk as the potential for undesirable outcomes or harm resulting from various factors. In the context of maritime security, risk encompasses the probability of adverse events influenced by external threats, vulnerabilities within the system, and the potential consequences of those events.[LO3.9.1.1] This perspective takes into account the uncertainties and complexities associated with maritime operations, highlighting that risks can manifest due to various factors, including intentional threats like piracy or terrorism, unintentional factors like accidents or equipment failures, and even natural occurrences like extreme weather.

Effective risk management involves conducting comprehensive assessments that consider the unique aspects of each situation. By examining the interplay between threats, vulnerabilities, and potential consequences, I can develop strategies and measures to proactively mitigate and manage these risks. Continuous monitoring, adaptation, and compliance with international regulations are vital in ensuring the security and safety of operations.

Returning to our project, we've implemented several precautions to minimize potential risks. A significant step we took was excluding database credentials from the repository. (Security outcome Team, 2023) Additionally, we've hashed user passwords and logins, opting to store database credentials in an env file. We've even established two connecting methods to test for potential database injection attempts. While acknowledging the room for further protective measures, I'm eager to research to explore modern industry practices.

I delved into an enlightening article by Deloitte, which details the risks of data loss and how to prevent it.[LO3.9.1.1] (Rohrig, 2020) I've learned that data backup is a critical measure to prevent data loss or damage caused by accidents or malicious activities. Safeguarding valuable data assets and enhancing data security and availability are paramount. Various methods and storage options can optimize data backup processes.

Furthermore, I explored the transformative capabilities of data analytics and artificial intelligence (AI) as explained by KPMG. (Dordevic, 2021) Integrating risk management into AI processes involves implementing data governance, and security measures, and leveraging AI for risk detection. This integrated approach not only mitigates negative data risks but also unlocks the positive value of data for businesses and organizations.

This reflection has been a significant step towards understanding and responding to risks within the context of my project. Effective risk management is an ongoing process that requires continuous learning, adaptation, and integration of industry best practices to safeguard valuable assets and unleash the potential of data.



Glover, C. (2023) The difference between threat, vulnerability, and risk, and why you..., Trava. Available at: https://travasecurity.com/learn-with-trava/blog/the-difference-between-threat-vulnerability-and-risk-and-why-you-need-to-know (Accessed: 21 October 2023). 

Salim, H. (2023) Understanding the difference between ‘risk’ and ‘threat’, Risk Intelligence. Available at: https://www.riskintelligence.eu/background-and-guides/understanding-the-difference-between-risk-and-threat (Accessed: 21 October 2023). 

Security outcome Team (2023) security outcome, repository for security sandbox application. Available at: https://vileider@bitbucket.org/vileider/security-outcome.git (Accessed: 2023). 

Rohrig , M. (2020) Managing data risks for Value Creation, Deloitte United States. Available at: https://www2.deloitte.com/us/en/pages/advisory/articles/emerging-data-risks.html (Accessed: 21 October 2023). 

Dordevic, A. (2021) What are the algorithmic risks when increasing reliance on data analytics and artificial intelligence?, KPMG. Available at: https://kpmg.com/uk/en/home/insights/2021/11/algorithmic-risks-when-increasing-reliance-on-data-analytics-and-artificial-intelligence.html (Accessed: 21 October 2023). 