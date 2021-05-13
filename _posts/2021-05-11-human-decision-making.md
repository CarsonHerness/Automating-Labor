---
layout: post
title:  "Necessarily Human Decision Making: What Can't Be Automated"
author: carson
categories: [ ethics, AI, human decisions ]
category: contemporary
featured: true
image: "./assets/images/fiber-optic-human.jpg"
---

What are the limits of artificial intelligence and technology? Will machines one day be able to do any task that a human can, or is there a limit to what machines can do? If not, should there be?

Photo by [Compare Fibre](https://unsplash.com/@comparefibre?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/robot?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).

---

In this post, I describe two different positions on automating human automation: one from the perspective of a computer scientist at the end of the twentieth century, and the other from a professor of political science who works at the intersection of social justice and technology. Technical limitations and ethical concerns inform their respective positions.

## Artificial intelligence and human decision making

Jean-Charles Pomerol is a French computer scientist. In 1997, Pomerol published "Artificial intelligence and human decision making" in the _European Journal of Operational Research_. In this article, Pomerol is concerned with the current technical limitations of using artificial intelligence to make human decisions.

Pomerol argues that previous models for decision making were inadequate: "AI has many relationships with diagnosis (expert systems, case-based reasoning, fuzzy set and rough set theories). On the other hand, AI has not paid enough attention to look-ahead reasoning, whose main components are uncertainty and preferences." Pomerol says that in the future, AI will need to be able to mimic or execute human-like reasoning in order to be able to make human decisions. As an aside, Pomerol's prediction proves correct here, with AI techniques like Reinforcement Learning gaining momentum in the coming decades.

To illustrate his argument about the importance of the decision making process itself, Pomerol describes the failures of expert systems: they do not consider preferences of the user of the system, and that they assume complete certainty about the present state.[^1] As a result, he argues that organizational decisions, for example, are poorly suited for expert systems since they cannot understand the complexities and competing interests of different stakeholders.[^2]

Pomerol also says that knowledge is not enough—decision making is more complex than having the data.[^3] Overall, Pomerol argues that decision theory and AI will complement each other so that together, they will allow AI to mimic the human decision-making process.[^4] Note that Pomerol does not question if AI can or should try to mimic or replace human decision-making processes; rather, he postulates that the current approaches that AI used to make human decisions, saying that AI needed to better model human reasoning.

## The Allegheny Algorithm

In this section, I'll share a case where a human decision making process has been replaced/augmented by an artificial intelligence (AI) model, as documented by Virginia Eubanks in her 2019 book _Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor_.

Virginia Eubanks is a professor of political science at the University at Albany, SUNY. Eubanks studies the intersection of technology and social justice. In 2018, Eubanks published her award-winning book _Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor_. In the book, Eubanks outlines how technological advances have disproportionately harmed vulnerable populations and marginalized groups. For example, in the chapter "The Allegheny Algorithm," Eubanks explains what happens when the Allegheny County Office of Children, Youth and Families (CYF) in Pennsylvania uses a predictive model to determine how at risk a child is in their home.[^5] The model, called the Allegheny Family Screening Tool (AFST), outputs a score between 1 and 20, where higher scores indicate a higher risk of harm to a child. The model uses data such as child protective services call statistics and the age of the children in a home.

In the chapter, Eubanks describes two specific children's cases who are evaluated using AFST. The results from AFST are opaque and do not match what a case worker would have concluded using the same evidence. Eubanks says, "The AFST, like all risk models, offers only probabilities, not perfect prediction. Though it might be able to identify patterns and trends, it is routinely wrong about individual cases."[^6] As Eubanks dictates, all models miss some information, whether because they lack all of the information and context about a situation or because they lack the reasoning abilities that a human would employ given the same information and context about a situation. In scenarios like child and youth protective services, the consequences of these differences can significantly (negatively) affect human lives.

The AFST is used as a tool and not a replacement for human decisions, but a certain score from AFST mandates CYF intervention. However, the system also seems to influence the humans at CYF making these decisions. As Eubanks says, the "AFST is supposed to support, not supplant, human decision-making in the call center. And yet, in practice, the algorithm seems to be training the intake workers."[^7] Though AFST is intended to be a tool for CYF workers to use, in practice, AFST has a larger impact.

Eubanks also worries about a scenario where AFST eventually would be used as the sole decision maker: "Under the right conditions—fiscal austerity, a governor looking to downsize public agencies, or a rash of child deaths—the AFST could easily become a machine for automatically removing children from their homes. It wouldn't even require reprogramming the model."[^8] Again, though AFST was not intended to replace a human-decision making process, nothing stops a government or agency from using it as such.

Overall, Eubanks presents evidence that perhaps, this technology to augment a human decision making process should never have been created all—when the stakes are so high, like they are for CYF, an algorithm may never meet the bar.

## Connections between Pomerol and Eubanks

The issue that Pomerol describes with AI at the time—not enough attention on look-ahead reasoning—is exactly the sort of reasoning that would be used in a system like AFST. Pomerol describes a technical deficit while Eubanks presents a situation in which human decision making technology should perhaps not be employed at all.

These two pieces were published in different eras of technology—much has changed in artificial intelligence since Pomerol published his paper in 1997—but it's indicative of a common pattern in technological advances: the computer scientists and the engineers determine what is or is not technically possible, and social scientists and historians analyze the impact of their work afterwards. When historians conduct post-implementation analyses of the impact of technologies, like Eubanks does in _Automating Inequality_, they may determine that perhaps the technology should not have been developed at all.

This is not necessarily to say that Pomerol should have included such analysis about the impact on society in his paper, though some would argue that he should have. Rather, I call attention to a trend of an artificial separation of fields: ethics and social science separate from science and engineering.

## Moving Forward

This trend of field separation between ethics and engineering seems to be loosening somewhat in the modern era, with new organizations for AI ethics forming in recent years; additionally, more ethics curriculum is being developed and introduced at the university level in computer science programs. At Harvey Mudd College, for example, many computer science classes integrate ethics-related curriculum throughout each semester of a course so that by the time a student graduates with a degree in computer science, they have been exposed to a significant amount of ethical concerns that past students had not been.

Others have proposed methods to document how a technical or computational model should be used. For example, in "Model Cards for Model Reporting," Mitchell et al. propose using model cards to outline the intended use and limitations of machine learning models;[^9] these model cards would be included with every paper or codebase that proposes or publishes a machine learning model so that whoever would use the technology in the future would, at the very least, know what a model should or should not be used for. This does not necessarily prevent someone from misusing a model, but the model cards encourage computer scientists to provide more information than had been provided previously, which may prevent some model misuse in the future.

Overall, questions of technical feasibility and human impact of automating human processes—such as the process of determining if a child is in need of a safety intervention from child protective services—have been separate questions due to socially constructed differences in research fields. As AI continues to progress and evolve, it may appear that a model is capable of automating some previously human decision making process when in reality, the human decision making process and the context in which it exists is much more complex and nuanced than a computer scientist or engineer understands.

## Works Cited

Eubanks, Virginia. _Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor_. New York, NY: Picador, St. Martin's Press, 2019.

Mitchell, Margaret, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, and Timnit Gebru. "Model Cards for Model Reporting." _Proceedings of the Conference on Fairness, Accountability, and Transparency_, 2019. [https://doi.org/10.1145/3287560.3287596](https://doi.org/10.1145/3287560.3287596).

Pomerol, Jean-Charles. "Artificial Intelligence and Human Decision Making." _European Journal of Operational Research_ 99, no. 1 (1997): 3–25. [https://doi.org/10.1016/s0377-2217(96)00378-5](https://doi.org/10.1016/s0377-2217(96)00378-5).


<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     Jean-Charles Pomerol, "Artificial Intelligence and Human Decision Making," _European Journal of Operational Research_ 99, no. 1 (1997): pp. 3-25, [https://doi.org/10.1016/s0377-2217(96)00378-5](https://doi.org/10.1016/s0377-2217(96)00378-5), 11.

[^2]:
     Ibid.

[^3]:
     Ibid., 22.

[^4]:
     Ibid.

[^5]:
     Virginia Eubanks, _Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor_ (New York, NY: Picador, St. Martin's Press, 2019), 132.

[^6]:
     Ibid., 146.

[^7]:
     Ibid.

[^8]:
     Ibid., 176.

[^9]:
     Margaret Mitchell et al., "Model Cards for Model Reporting," _Proceedings of the Conference on Fairness, Accountability, and Transparency_, 2019, [https://doi.org/10.1145/3287560.3287596](https://doi.org/10.1145/3287560.3287596).
