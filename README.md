

# β± CountDown


[DEMO](https://countdown.jacobko.info/)

![screen](https://user-images.githubusercontent.com/28912774/117662433-822e6e80-b1da-11eb-893c-78ec7d06f624.gif)



## π» 1.νλ‘μ νΈ μκ°  

### π μ¬μ©κΈ°μ  λ° μΈμ΄    

- Vanilla JS
- CSS
- HTML


### β° κ°λ° κΈ°κ°  
2021-05-08 


## π 2.νλ‘μ νΈ λ΄μ©

### μ£Όμ κΈ°λ₯

- new Date() method λ₯Ό ν΅ν νμ¬λ μ§, 2022λ λ μ§ μλ ₯

- λ§€ μ΄λ§λ€ λ¨μ μ¬ν΄μ days, hours, mins, secounds λ₯Ό λμ μΌλ‘ κ΅¬ν
 




## π 3.μ£Όμ μ½λ

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

## 4. λλμ 

- κ°λ¨ν Vanilla JS code μ΄μ§λ§, λͺκ°μ§ μ€μνκ² λ°°μ λ μ μ..

    - `new Date()` μ ν΅ν μν΄ λ μ§μκ° - μ§κΈ λ μ§μκ° : λ¨μμκ°  κ²°κ³Όμ / 1000 μ νμ¬ totalSeconds κ΅¬νκΈ°

    - totalSeconds λ₯Ό κ°κ° λ μ§, μκ°, λΆ, μ΄ λ‘ μνμ μΌλ‘ κ³μ°νκΈ° (μ΄ν΄κ° μλμ stackover flow μ κ²μμ ν΅ν΄ μκ² λμλ€)



## Reference

- [Florin Pop](https://www.youtube.com/watch?v=dtKciwk_si4&t=1788s)

- [μΉ κ°λ° λ©λͺ¨μ₯](https://dororongju.tistory.com/116)

- [stack overflow](https://stackoverflow.com/questions/12007379/what-makes-new-date-1000-a-valid-javascript)