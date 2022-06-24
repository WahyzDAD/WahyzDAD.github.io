---
layout: single
title:  "그래프 공간 다루기"
---

# 그래프 시인성 개선이 필요했다: 거대 그래프 생성을 대비하면서.

Node의 Number of connections가 클수록 다른 노드를 밀어내는 힘이 있어야

Number of connections가 커서 marker size가 크게 (설정)된 Node 간 겹침이 줄어든다.

그 힘을 weight로서 Node의 Number of connections에 비례하게 설정하였고(이후 제곱에 비례 등등의 시도를 해볼 예정), 시인성이 개선됐다.

개선 전:

![before spacing](https://user-images.githubusercontent.com/96930429/175450197-5b37ffa5-e5a3-4d11-bb74-863b78d7e52b.png)

개선 후:

![after spacing](https://user-images.githubusercontent.com/96930429/175450227-a3ef6c05-11b1-4212-a4a9-3b17cd989364.png)


불편한 점들을 하나하나 차근차근 개선하면 어느샌가는 남들도 편하게 쓸 좋은 도구가 될 것으로 믿는다.
