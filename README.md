# 주제: christmas
christmas js 연습

# 학습내용
- repl 사용해보기 (read-eval-print-loop)
- 자바스크립트 코드등을 즉석에서 바로 실행

### 달력 구조 만들기 
GRID
![image](https://github.com/catspie/christmas/assets/102503668/7f8e425f-6f28-4f6a-94e2-6851e0113126)

### 카드 뒤집기 CSS
```
/* 카드 뒤집기 애니메이션 */
.door .back {
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
	transform: rotateY(180deg);
/* 참고: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotateY */
}

/* 참고: https://scribblinganything.tistory.com/341 */
:checked+.door {
  transform: rotateY(180deg);
}
```

# 배포: netlify
https://65770d29bb45757a0a524e04--lovely-clafoutis-a677d2.netlify.app/
![image](https://github.com/catspie/christmas/assets/102503668/ab230ec4-a678-4769-bb0a-0635f2822b9f)


# 눈내리는거 활용해보기 (블로그에 적용)
https://howtomakecode.tistory.com/
