# Course Manifesto

In 2018, lawyers need quantitative and computational comfort.

## Quantitative Comfort 

The practice of law has always had an uncomfortable relationship with mathematical thinking. Many students find themselves in law school in part out of a discomfort with math, and this discomfort continues even to the highest levels of the legal profession. For example, in oral argument in Gil v. Whitford Chief Justice Roberts famously described the use of quantitative measures of gerrymandering as “sociological gobbledygook” and objected to its use on the basis of not only his personal discomfort but also a sense that the public would question the fairness and legitimacy of a court that used such a mathematical measure: 

> And if you're the intelligent man on the street and the Court issues a decision, and let's say, okay, the Democrats win, and that person will say: "Well, why did the Democrats win?" And the answer is going to be because EG was greater than 7 percent, where EG is the sigma of party X wasted votes minus the sigma of party Y wasted votes over the sigma of party X votes plus party Y votes. And the intelligent man on the street is going to say that's a bunch of baloney. It must be because the Supreme Court preferred the Democrats over the Republicans. 

Yet the modern practice of law requires comfort with mathematical claims and methods in many areas. Most important for legal practice is a familiarity with probability and statistics, which will allow lawyers to understand and begin to answer (or communicate with experts about answering questions like): 

- Is the racial disparity (in employment, housing, jury challenges) substantially more stark than would have been expected by mere chance? 

- If I know the measured accuracy of the test (BreathAlyzer, radar gun, urinalysis, genetic test) taken by the defendant, what is the chance that the defendant has been falsely accused? (The correct answer to this question is less obvious than you think!)

*TODO: add more examples*

Moreover, the expert witnesses that lawyers so often rely upon are often called upon to make claims based on statistical evidence—and a lawyer who is equipped to understand the basic ways this evidence can go wrong will be better able to defend or attack the credibility of that testimony. These kinds of errors can lead to dire consequences: in 2015, the FBI admitted that “at least 90 percent” of the cases over a period of decades in which its hair follicle examiners testified, those examiners overstated the significance of their data. Most troublingly, known errors appeared in 33 of 35 cases in which defendants were sentenced to death.^[FBI Press Release, April 20, 2015, [https://www.fbi.gov/news/pressrel/press-releases/fbi-testimony-on-microscopic-hair-analysis-contained-errors-in-at-least-90-percent-of-cases-in-ongoing-review](https://www.fbi.gov/news/pressrel/press-releases/fbi-testimony-on-microscopic-hair-analysis-contained-errors-in-at-least-90-percent-of-cases-in-ongoing-review)] Perhaps prosecutors or defense lawyers with some familiarity with probability and statistics could have prevented some of these terrible mistakes.

The first goal of this course will be to endow students with sufficient quantitative comfort to be competent consumers of statistical and probabilistic claims. The course will not enable students to carry out original rigorous scientific analysis, but it will enable them to understand and critically examine statistical probabilistic claims often made in legal contexts. It will also enable them to do the most fundamental math for empirical claims, such as calculation of posterior probabilities and understanding of the properties of various statistical distributions, confidence intervals, and other mathematical artifacts.

## Computational Comfort

The legal profession is also rapidly being disrupted by technological advancements. “Predictive coding” systems using machine learning techniques are replacing lawyers in the discovery process, computational legal research is becoming integrated with artificial intelligence, and startups are offering basic legal services such as contracts and wills in computationally facilitated forms that allow customers to avoid consulting with a lawyer. Moreover, the continuing growth of the technological sector of the economy creates a demand for lawyers who understand technical concepts—at least well enough to communicate about them with expert witnesses and jurors.^[See Michaela Ross, “Tech-Savvy Attorneys in Heavy Demand Amid Emerging Tech,” Bloomberg BNA, February 22, 2018, [https://www.bna.com/techsavvy-attorneys-heavy-n57982089186/](https://www.bna.com/techsavvy-attorneys-heavy-n57982089186/)] Finally, increasing evidence appears in the form of “eDiscovery,” which requires special technological skills to handle.

At the same time, there are strong indications that lawyers lack even a minimal level of technical competence. Even that unavoidable tool of legal practice, Microsoft Word, seems to cause lawyers no end of (expensive and time-wasting) problems.^[See D. Casey Flaherty, “Could you pass this in-house counsel’s tech test? If the answer is no, you may be losing business,” ABA Journal, July 27, 2013, [http://www.abajournal.com/legalrebels/article/could_you_pass_this_in-house_counsels_tech_test](http://www.abajournal.com/legalrebels/article/could_you_pass_this_in-house_counsels_tech_test)] I shiver to consider the problems that lawyers have with more complicated and important technical skills, like choosing secure data storage and communication options to protect client information.

This course cannot (and will not attempt to) teach Microsoft Word or encryption and information security. But it can teach basic technological comfort, and even a few superpowers, through offering a deeper understanding of the logic and basic tools of computer programming. Through basic computer programming, lawyers can automate many of the most tedious tasks of their professional lives and save their clients money and themselves time—particularly tasks involving the processing of large volumes of text.

More interestingly, programming skills offer deep synergies with statistical skills. A lawyer who can use a computer to look at data can use statistical computing tools to double-check the claims made by others about the data that shows up in the practice of law, tweak statistical tests to “stress-test” those claims, and visualize data in order to catch mistakes and false assumptions on which those claims depend. And by learning basic programming prior to statistics, a lawyer can make use of statistical data without relying either on expensive and rigid dedicated statistical software like STATA and SPSS, or, worse, struggling through the math by hand.

The second goal of the course will be to endow students with basic programming and statistical computation capacity, using the Python programming language. The course does not aim to produce programmers, but rather to produce lawyers with the skills to work with text and with data in a computational form.