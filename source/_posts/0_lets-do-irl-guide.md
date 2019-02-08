---
title: Let's do Inverse RL Guide
date: 2019-01-22
tags: ["프로젝트", "GAIL하자!"]
categories: 프로젝트
author: 이동민, 이승현
subtitle: Let's do Inverse RL Guide
---

---

# 0. Inverse RL의 세계로

반갑습니다! 저희는 Inverse RL을 흐름을 살펴보기 위해 모인 IRL 프로젝트 팀입니다.

강화학습에서 reward라는 요소는 굉장히 중요합니다. 왜냐하면 agent라는 아이가 유일하게 학습할 수 있는 요소이기 때문입니다. 일반적으로 강화학습에서는 사람이 reward를 일일히 정해주지만, 실제로 그 reward에 따라 "desirable"  action이 나오지 않을 수도 있습니다. 여기서 생각해볼 수 있는 것이 바로 "expert"의 행동을 통해 reward를 찾는 것입니다.

저희는 Andrew Ng의 논문인 Linear IRL과 Pieter Abbeel의 논문인 APP를 필두로 하여 MMP, MaxEnt, 그리고 보통 IRL을 통해 얻어진 reward로 다시 RL을 풀어서 policy를 얻어야하지만, 이 과정을 한번에 풀어버리는 GAIL, 최근 들어 GAIL을 뛰어넘는 VAIL까지 살펴보고자 합니다.

<center> <img src="../../../../img/irl/lets-do-irl-guide_2.png" width="900"> </center>

논문의 순서는 다음과 같습니다.

1. [Linear_IRL](http://ai.stanford.edu/~ang/papers/icml00-irl.pdf)
2. [APP](http://people.eecs.berkeley.edu/~russell/classes/cs294/s11/readings/Abbeel+Ng:2004.pdf)
3. [MMP](https://www.ri.cmu.edu/pub_files/pub4/ratliff_nathan_2006_1/ratliff_nathan_2006_1.pdf)
4. [MaxEnt](http://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf)
5. [GAIL](https://papers.nips.cc/paper/6391-generative-adversarial-imitation-learning.pdf)
6. [VAIL](https://arxiv.org/pdf/1810.00821.pdf)

위와 같이 총 6가지 논문들을 리뷰하여 블로그로 정리하였습니다. 각 순서에 맞춰 보시는 것을 권장해드립니다.

<br><br>

# 1. \[Linear IRL\] Algorithms for Inverse Reinforcement Learning

[Linear IRL 여행하기](https://reinforcement-learning-kr.github.io/2019/01/28/1_linear-irl/)

짧은 글 소개, 요약

[Linear IRL 여행하기](https://reinforcement-learning-kr.github.io/2019/01/28/1_linear-irl/)

<br><br>

# 2. \[APP\] Apprenticeship Learning via Inverse Reinforcement Learning

[APP 여행하기](https://reinforcement-learning-kr.github.io/2019/02/01/2_app/)
[APP Code]()

짧은 글 소개, 요약

[APP 여행하기](https://reinforcement-learning-kr.github.io/2019/02/01/2_app/)
[APP Code]()

<br><br>

# 3. \[MMP\] Maximum Margin Planning

[MMP 여행하기](https://reinforcement-learning-kr.github.io/2019/02/07/3_mmp/)

짧은 글 소개, 요약

[MMP 여행하기](https://reinforcement-learning-kr.github.io/2019/02/07/3_mmp/)

<br><br>

# 4. \[MaxEnt\] Maximum Entropy Inverse Reinforcement Learning

[MaxEnt 여행하기](https://reinforcement-learning-kr.github.io/2019/02/10/4_maxent/)
[MaxEnt Code]()

짧은 글 소개, 요약

[MaxEnt 여행하기](https://reinforcement-learning-kr.github.io/2019/02/10/4_maxent/)
[MaxEnt Code]()

<br><br>

# 5. \[GAIL\] Generative Adversarial Imitation Learning

[GAIL 여행하기](https://reinforcement-learning-kr.github.io/2019/02/13/5_gail/)
[GAIL Code]()

짧은 글 소개, 요약

[GAIL 여행하기](https://reinforcement-learning-kr.github.io/2019/02/13/5_gail/)
[GAIL Code]()

<br><br>

# 6. \[VAIL\] Variational Discriminator Bottleneck: Improving Imitation Learning, Inverse RL, and GANs by Constraining Information Flow

[VAIL 여행하기]()
[VAIL Code]()

수정중..

[VAIL 여행하기]()
[VAIL Code]()

<br><br>

# Team

이동민 : [Github](https://github.com/dongminleeai), [Facebook](https://www.facebook.com/dongminleeai)

윤승제 : [Github](https://github.com/sjYoondeltar), [Facebook](https://www.facebook.com/seungje.yoon)

이승현 : [Github](https://github.com/Clyde21c), [Facebook](https://www.facebook.com/Clyde21c)

이건희 : [Github](https://github.com/Geonhee-LEE), [Facebook](https://www.facebook.com/Geonheeee)

김준태 : [Github](https://github.com/OPAYA), [Facebook](https://www.facebook.com/kjt7889)

김예찬 : [Github](https://github.com/suhoy901), [Facebook](https://www.facebook.com/suhoy90)