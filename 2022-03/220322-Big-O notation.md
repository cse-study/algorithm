+++

title = "Big-O notation"
date = "2022-03-22"
[profile]  
	enable = true  
	avatar = "/assets/img/yuho.jpg"  
	name = "Yuho Jeong"  
	github = "yuhodots"
	email = "yuho8437@unist.ac.kr"

+++

2022년 03월 2주차 개인 목표 수행합니다.
<!--more-->

학계와 산업계에서 말하는 big-$O$ notation에는 약간의 차이가 존재한다는 것을 알게 되었음. 이전부터, 수업에서 배우는 big-$O$와 일반적으로 널리 쓰이는 big-$O$의 의미가 다르다는 점이 헷갈렸는데, 해당 챕터를 읽고 이해할 수 있게 되었음

- (시간복잡도의 경우) 학계에서 big-$O$는 시간의 상한, big-$\Omega$(omega)는 등가 혹은 하한, big-$\Theta$(theta)는 $O$와 $\Omega$ 둘 다를 의미함
- 따라서 $O(N)$으로 표현되는 알고리즘을 $O(N^2), O(N^3), O(2^N)$으로도 표현하는 것이, 학계에서는 옳은 표현임
- 하지만 산업계에서(면접에서) 말하는 big-$O$의 의미는 학계에서의 $\Theta$의 의미와 가깝다고 생각하면 된다고 함

추가적으로, 공간복잡도는 시간이 아닌 메모리(혹은 공간)을 big-$O$로 표현한 것임
