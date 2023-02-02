---
title:  "Double D's Book Shelf"
categories: jekyll update
summary : "독서노트라고 하기엔 너무 거창하지만 책을 읽으면서 마음에 들었던 구절과 짦은 소감이 포함된 페이지"
permalink: contents_update_book_review.html
tags: [news]
---

- ## Double D's Book Shelf - 더블디의 독서노트

  독서노트라고 하기엔 너무 거창하지만 책을 읽으면서 마음에 들었던 구절과 짦은 소감이 포함된 페이지
  곡을 쓰거나 대화를 하다가 가끔 읽었던 책의 특정 구절이 생각나지 않아 정리하기 시작한 페이지
  
  ### 철학   

  - [괴로운 날엔 쇼펜하우어 - 셀린 벨로크 저](https://ddbook.tistory.com/2)
  - [무력할 땐 아리스토텔레스 - 다미앵 클레르제-귀르노](https://ddbook.tistory.com/3)
  - [우울한 날엔 니체 - 발타자르 토마스 저](https://ddbook.tistory.com/4)
  - [비참한 날엔 스피노자 - 발타자르 토마스 저](https://ddbook.tistory.com/5)
  - 절망한 날엔 키에르케고르 - 다미앵 클레르제-귀르노 저 [part1](https://ddbook.tistory.com/6) , [part2](https://ddbook.tistory.com/22)
  
  ### 인문학
  
  - 지적 대화를 위한 넓고 얕은 지식 1 - 채사장 [part1](https://ddbook.tistory.com/7) , [part2](https://ddbook.tistory.com/23)
  - 지적 대화를 위한 넓고 얕은 지식 2 - 채사장 [part1](https://ddbook.tistory.com/8) , [part2](https://ddbook.tistory.com/24)
  
  ### 소설
  
  - [주홍색 연구 · 네 사람의 서명 - 아서 코난 도일](https://ddbook.tistory.com/10)

  ### 프로그래밍

  #### 중복참조 방지

  1. inclusion guard
  foo.h 가 한번도 정의되지 않았을 때에만 참조 한번 이라도 정의되었다면 ifndef구문 내의 함수는 참조하지 않음

  ~~~
  #ifndef FOO_H
  #define FOO_H
  include "foo.h"
  #endif 
  ~~~
  
  2. #pragma once
  #pragma once는 한 번만 include 하라는 옵션으로 아래의 경우 foo.h와 bar.h의 include가 한번만 포함됨을 보장한다.
  
  ~~~
  #pragma once
  #include "foo.h"
  #include "bar.h"
  ~~~

{% include links.html %}
