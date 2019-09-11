# Identifying Redundant Development in Forks 

[Project Webpage] (http://forks-insight.com/INTRUDE-welcome)

Redundant development wastes effort for both maintainers and developers. INTRUDE is a GitHub bot to detect potentially redundant pull requests. It monitors all pull requests in a repository, and if it finds two pull requests that are very similar, it automatically comments on the issue, pointing out the similarity.

Our goal is to identify redundant code changes in forks as early as possible by extracting clues indicating similarities between code changes, and building a machine learning model to predict redundancies.

An academic paper describing more technical details and an evaluation has been published:

L. Ren, S. Zhou, C. Kästner, and A. Wąsowski. Identifying Redundancies in Fork-based Development. In Proceedings of the 27th IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), pages 230--241, 2019. [pdf](https://www.cs.cmu.edu/~shuruiz/paper/saner19-RedundantDev.pdf)


# DuplicatePR Bot Team
We are researchers at Carnegie Mellon University developing a bot to monitor GitHub projects and alert project maintainers to potentially duplicate pull requests. [Shurui Zhou](https://www.cs.cmu.edu/~shuruiz) is a Ph.D. student studying under Professor [Christian Kästner](https://www.cs.cmu.edu/~ckaestne/). Annika Esau is an undergraduate REU student.

INTRUDE comes out of an NSF-funded research project at Carnegie Mellon University, identfying potentially redundant development in open-source software development. INTRUDE is open source and hosted for the community. We would love to hear your ideas and feedback. Explore the source or open an issue.

# Source Code Repository

https://github.com/shuiblue/INTRUDE
