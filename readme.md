# Identifying Redundant Development in Forks 

[Project Webpage] (http://forks-insight.com/INTRUDE-welcome)

Redundant development wastes effort for both maintainers and developers. INTRUDE is a GitHub bot to detect potentially redundant pull requests. It monitors all pull requests in a repository, and if it finds two pull requests that are very similar, it automatically comments on the issue, pointing out the similarity.

Our goal is to identify redundant code changes in forks as early as possible by extracting clues indicating similarities between code changes, and building a machine learning model to predict redundancies.

An academic paper describing more technical details and an evaluation has been published:

L. Ren, S. Zhou, C. Kästner, and A. Wąsowski. Identifying Redundancies in Fork-based Development. In Proceedings of the 27th IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), pages 230--241, 2019. [pdf](https://www.cs.cmu.edu/~shuruiz/paper/saner19-RedundantDev.pdf)


# DuplicatePR Bot Team
We are researchers at Carnegie Mellon University developing a bot to monitor GitHub projects and alert project maintainers to potentially duplicate pull requests. [Shurui Zhou](https://www.cs.cmu.edu/~shuruiz) is a Ph.D. student studying under Professor [Christian Kästner](https://www.cs.cmu.edu/~ckaestne/). Annika Esau and [Luyao Ren](http://luyaoren.com/) are undergraduate REU students.

INTRUDE comes out of an NSF-funded research project at Carnegie Mellon University, identfying potentially redundant development in open-source software development. INTRUDE is open source and hosted for the community. We would love to hear your ideas and feedback. Explore the source or open an issue.

# Source Code Repository

https://github.com/shuiblue/INTRUDE

# Duplicate PR pairs detected:

| repo |PR1   |PR2   |
|---|---|---|
| matomo-org/matomo|[14137](https://github.com/matomo-org/matomo/pull/14137)|[14975](https://github.com/matomo-org/matomo/pull/14975)|  
|mrdoob/three.js|[10597](https://github.com/mrdoob/three.js/pull/10597)|[13706](https://github.com/mrdoob/three.js/pull/13706)|
|mrdoob/three.js|[6203](https://github.com/mrdoob/three.js/pull/6203)|[6301](https://github.com/mrdoob/three.js/pull/6301)|
|spring-projects/spring-framework|[1695](https://github.com/spring-projects/spring-framework/pull/1695)|[1817](https://github.com/spring-projects/spring-framework/pull/1817)|
|spring-projects/spring-framework|[1492](https://github.com/spring-projects/spring-framework/pull/1492)|[1628](https://github.com/spring-projects/spring-framework/pull/1628)|
|spring-projects/spring-framework|[1218](https://github.com/spring-projects/spring-framework/pull/1218)|[1653](https://github.com/spring-projects/spring-framework/pull/1653)|
|spring-projects/spring-framework|[569](https://github.com/spring-projects/spring-framework/pull/569)|[566](https://github.com/spring-projects/spring-framework/pull/566)|
|spring-projects/spring-framework|[758](https://github.com/spring-projects/spring-framework/pull/758)|[1827](https://github.com/spring-projects/spring-framework/pull/1827)|
|hashicorp/terraform|[18186](https://github.com/hashicorp/terraform/pull/18186)|[18296](https://github.com/hashicorp/terraform/pull/18296)|
|cocos2d/cocos2d-x|[14883](https://github.com/cocos2d/cocos2d-x/pull/14883)|[13687](https://github.com/cocos2d/cocos2d-x/pull/13687)|
|cocos2d/cocos2d-x|[14794](https://github.com/cocos2d/cocos2d-x/pull/14794)|[7565](https://github.com/cocos2d/cocos2d-x/pull/7565)|
|facebook/react|[12760](https://github.com/facebook/react/pull/12760)|[13169](https://github.com/facebook/react/pull/13169)|
