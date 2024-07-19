# July 2024

## [2024/07/19](https://cssbattle.dev/play/zqsEhghz74OQZxY841Mh)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_Y9GeINv.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #6592CF;
    height: calc(100vh - 100px);
    padding: 50px;
    display: grid;
    grid-template-rows: 1fr 120px 1fr;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
  }
  div {
    background: #243D83;
    &:nth-child(3) {
      grid-area: 1 / 3 / span 1 / span 2;
    }
    &:nth-child(4) {
      grid-area: 2 / 1 / span 1 / span 4;
    }
    &:nth-child(5) {
      grid-area: 3 / 1 / span 1 / span 2;
    }
  }
</style>
```

## [2024/07/18](https://cssbattle.dev/play/j3ykZzA2Y99AsYcPCRKo)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_482znT4.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #024817;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    background: #25834A;
    width: 90px;
    height: 160px;
    
    &:nth-child(2) {
      background: #48BF7D;
      width: 60px;
      height: 200px
    }
  }
</style>

```

<details>
  <summary>Top Solution</summary>
  <pre>
    <style>&{margin:-10 0;background:#25834A;border:solid 5pc#041E;*{margin:-20 90;background:#48BF7D
  </pre>
</details>

## [2024/07/17](https://cssbattle.dev/play/63uT8mAsvJRLBjA2dsct)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_apjnNh9.png?alt=media">

#### Solution:

```html
<main>
  <div class="head">
    <div class="eyes"></div>
    <div class="eyes"></div>
  </div>
</main>
<style>
  * { 
    margin: 0
  }
  main {
    background: #EDAF38;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    &.head {
      background: #FFFFCD;
      width: 140px;
      height: 190px;
      display: inherit;
      align-items: inherit;
      justify-content: inherit;
      gap: 10px;
      clip-path: polygon(0 26%, 18% 0, 36% 26.5%, 64% 26.5%, 82% 0, 100% 26%, 50% 100%);
    }
    &.eyes {
      margin-top: 20px;
      border: solid;
      border-width: 30px 15px;
      border-color: #EDAF38 transparent transparent;
    }
  }
</style>
```

## [2024/07/16](https://cssbattle.dev/play/Xi1SSXp9H6g10bK65ZLA)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_o2MVPVs.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0
  }
  main {
    height: 100vh;
    background: #4F77FF;
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    grid-template-rows: repeat(3, 1fr);
  }
  div {
    --radius-value: 40px;
    &:nth-child(odd) {
      background: #EFF8FE;
    }
    &:nth-child(5) {
      background: #4F77FF;
    }
    &:nth-child(1) {
      border-bottom-right-radius: var(--radius-value);
    }
    &:nth-child(3) {
      border-bottom-left-radius: var(--radius-value);
    }
    &:nth-child(7) {
      border-top-right-radius: var(--radius-value);
    }
    &:nth-child(9) {
      border-top-left-radius: var(--radius-value);
    }
  }
</style>
```

## [2024/07/14](https://cssbattle.dev/play/m1cHlo8crbGrZEPvie07)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_cdoXsLV.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #0A6190;
    height: calc(100vh - 100px);
    padding: 50px 100px;
    
    &::after {
      content: "";
      background: #328FC1;
      height: 75%;
      width: 75%;
      display: block;
      margin: 25px;
    }
  }
  div {
    background: #328FC1;
    float: left;
    height: 100px;
    width: 100px;
    border-radius: 50%;
  }
</style>
```

## [2024/07/13](https://cssbattle.dev/play/tE24mLVrdztTiYmqdq3K)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_dKk0sS9.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #F48B26;
    height: 100vh;
    display: flex;
    justify-content: center;
    gap: 20px;
  }
  div {
    --var-height: 200px;
    background: linear-gradient(#FEFF58 var(--var-height), #F48B26 0);
    height: 100%;
    width: 30px;
    &:nth-child(even) {
      --var-height: 250px;
    }
    &:nth-child(3) {
      --var-height: 100%;
    }
  }
</style>
```


```html
<main>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #243D83;
    height: 100vh;
    display: grid;
    grid-template-areas:
      "one ."
      ". ."
      ". two";
    grid-template-rows: repeat(3, 1fr);
  }
  div {
    width: 200px;
    height: 100px;
    background: conic-gradient(from -21.5deg at 50% 100%, #243D83 12%, #6592CF 0);
    
    &:last-of-type {
      grid-area: two;
      scale:-1
    }
  }
</style>
```

## [2024/07/12](https://cssbattle.dev/play/zdlHeV5jrQqFujTJ6RcR)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_s6NqTP3.png?alt=media">

#### Solution:

```html
<main>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #243D83;
    height: 100vh;
    display: grid;
    grid-template-areas:
      "one ."
      ". ."
      ". two";
    grid-template-rows: repeat(3, 1fr);
  }
  div {
    width: 200px;
    height: 100px;
    background: conic-gradient(from -21.5deg at 50% 100%, #243D83 12%, #6592CF 0);
    
    &:last-of-type {
      grid-area: two;
      scale:-1
    }
  }
</style>
```