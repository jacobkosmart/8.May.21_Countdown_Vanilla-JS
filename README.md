

Netlify Status

# ⏱ CountDown


## 💻 1.프로젝트 소개  

### 📝 사용기술 및 언어    

- Vanilla JS
- CSS
- HTML


### ⏰ 개발 기간  
2021-05-08 


## 🗒 2.프로젝트 내용

### 주요 기능

- new Date() method 를 통한 현재날짜, 2022년 날짜 입력

- 매 초마다 남은 올해의 days, hours, mins, secounds 를 동적으로 구현
 




## 📌 3.주요 코드

```js
function countdown() {
  const newYearsDate = new Date(newYears);
  const currentDate = new Date();

  const totalSeconds = (newYearsDate - currentDate) / 1000;

  const days = Math.floor(totalSeconds / 3600 / 24);
  const hours = Math.floor(totalSeconds / 3600) % 24;
  const mins = Math.floor(totalSeconds / 3600) % 60;
  const seconds = Math.floor(totalSeconds) % 60;
}
```

## 4. 느낀점

- 간단한 Vanilla JS code 이지만, 몇가지 중요하게 배웠던 점은..

    - `new Date()` 을 통한 새해 날짜시간 - 지금 날짜시간 : 남은시간  결과에 / 1000 을 하여 totalSeconds 구하기

    - totalSeconds 를 각각 날짜, 시간, 분, 초 로 수학적으로 계산하기 (이해가 안되서 stackover flow 의 검색을 통해 알게 되었다)



## Reference

- [Florin Pop](https://www.youtube.com/watch?v=dtKciwk_si4&t=1788s)

- [웹 개발 메모장](https://dororongju.tistory.com/116)

- [stack overflow](https://stackoverflow.com/questions/12007379/what-makes-new-date-1000-a-valid-javascript)