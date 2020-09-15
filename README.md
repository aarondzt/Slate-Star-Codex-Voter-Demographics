# Slate-Star-Codex-Voter-Demographics
Slate Star Codex (SSC) is a blog by the pseudonymous author Scott Alexander. The blog is a fixture of the "rationalist" community, an internet community that seeks to analyze difficult problems in science, culture, and politics with high standards of reason. For example, almost every SSC post features citations from peer-reviewed papers and some degree of statistical reasoning. Each year, Scott conducts a survey of his readers and publishes the results online*. Herein, I look at the demographics of those who participated in the 2020 survey.

As you will see in the iPython notebook, the readers of SSC are very unrepresentative of America, in interesting ways (I limited my analysis to Americans). The readers are vastly male and white. To my surprise, over a third of readers are married. Most work white collar computer-related office jobs. Most identify as atheist, despite most being raised in religious environments. For the most unrepresentative statistic, the plurality voted for Andrew Yang in the Democratic Primary, with Elizabeth Warren and Bernie Sanders in second and third, and Biden in a distant sixth.

For each plot, I used countplot from seaborn, removed blank responses with a mask, and ordered categories by count.

*https://slatestarcodex.com/2020/01/20/ssc-survey-results-2020/
