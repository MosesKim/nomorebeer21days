---
layout: default
---

## 건강을 위한 작은 실험적 프로젝트.

NoMoreBeer21Days 프로젝트는 나의 건강을 위한 작은 프로젝트이다. 적게 먹고 많이 움직이면 살이 빠지고 건강한 몸으로 돌아간다는 것은 그 자체로 반박하기 어려운 진리겠지만...

식습관 중 무언가를 가장 많이 먹게 만드는 맥주라는 녀석과 잠시 멀어지기.

#### 프로젝트 기간

- 21일 (2018/SEP/26/수요일 ~ 2018/OCT/16/화요일)

#### 프로젝트 개요

- 습관적으로 마셨던 맥주를 프로젝트 기간동안 완전히 중단합니다.
- 맥주를 부르는 여러가지 행동을 중단합니다.
- 해당 기간 동안 다음의 내용을 기록하고 남깁니다.
  -  체중 (인바디)
  -  식단
  -  기타 도움이 될만한 것들


#### 프로젝트 기록

<ul>
  {% for post in site.posts %}
    <li>
      {% if site.use_constant_page_name %}
        <a href="{{ site.url }}{{ site.constant_page_name }}{{ post.url }}">{{ post.title }}</a>
      {% else %}
        <a href="{{ post.url }}">{{ post.title }}</a>
      {% endif %}
    </li>
  {% endfor %}
</ul>
