# July 2024

## [2024/07/24](https://cssbattle.dev/play/bHBi3b1NZkqOkTSGiK55)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_kV6XT09.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>  
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #EDAF38;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    width: 280px;
    height: 120px;
    background: #FFFFCD;
    position: relative;
    &::before {
      content: "";
      display: block;
      width: 100%;
      height: 40px;
      background: #7F7F24;
      position: absolute;
      border-radius: 50%;
      top: -20px;
      box-shadow: 0 120px#FFFFCD
    }
  }
</style>
```

## [2024/07/23](https://cssbattle.dev/play/FSn5zoHleIhC5QyOrgUT)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_uZhSTfo.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: linear-gradient(#4F77FF 0 125px, #EFF8FE 125px 175px, #4F77FF 175px);
    height: 100vh;
  }
  div {
    width: 150px;
    height: 150px;
    background: #EFF8FE;
    border-radius: 50%;
    position: absolute;
    top: -75px;
    color: #EFF8FE;
    box-shadow: 125px 0, 250px 0, 0 300px, 125px 300px, 250px 300px
  }
</style>
```

<details>
  <summary>Top Solution:</summary>
  <pre><style>*{--g:radial-gradient(1q,#EFF8FE 75px,#0000)634%50vh;background:var(--g)/62.53%,var(--g)#25fc;*{margin:125-9</style></pre>
</details>

## [2024/07/22](https://cssbattle.dev/play/Xn5t4qDbfBvqHiOTRxa8)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_WDIDQzO.png?alt=media">

#### My Solution:

```html
<div></div>
<style>
  * {
    margin: 0;
    background: #B53733;
  }
  div {
    width: 20px;
    height: 150px;
    background: #EA7457;
    color: #EA7457;
    margin: -10px 0 0 30px;
    box-shadow: 40px 40px, 80px 80px, 120px 120px, 160px 160px, 200px 120px, 240px 80px, 280px 40px, 320px 0
  }
</style>

```
<details>
  <summary>Top Solution:</summary>
  <pre><ul><ul><p><style>*{height:70;border-inline:5vw solid#EA7457;margin:0;padding:40 20;p{width:300}}&{background:#B53733;margin:-10 30</style></pre>
</details>


## [2024/07/21](https://cssbattle.dev/play/7T0XdIP4lLXtFht6PK2r)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_fEuqCIG.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>
  <div class="after"></div>
  <div></div>
  <div class="before"></div>
  <div class="before after"></div>
  <div class="after"></div>
  <div></div>
  <div class="before"></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    height: calc(100vh - 100px);
    padding: 50px 100px;
    background: #0A6190;
    display: grid;
    grid-template-columns: 3fr 2fr 3fr;
    grid-template-rows: 3fr 2fr 3fr;
  }
  div {
    position: relative;
    &:nth-child(even),
    &:nth-child(5) {
      background: #328FC1;
    }
    &.after::after,
    &.before::before {
      content: "";
      display: block;
      width: 25px;
      height: 25px;
      background: #0A6190;
      position: absolute;
    }
    &.after::after {
      inset: auto auto 0 0;
    }
    &.before::before {
      inset: 0 0 auto auto;
    }
  }
</style>
```

<details>
  <summary>Top Solution:</summary>
  <pre><style>&{background:#328FC1;outline:solid 2in#0A6190}*{margin:50 25%;border-image:repeating-conic-gradient(var(--a,at 100%0,)#0A6190,25%,#0000 0 50%)100/80q;*{--a:</style></pre>
</details>

## [2024/07/20](https://cssbattle.dev/play/74fe9XcTz4tjx4iscBz9)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_pMOTIYD.png?alt=media">

#### My Solution:

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
    align-items: center;
    justify-content: center;
    gap: 20px;
  }
  div {
    background: #FEFF58;
    width: 40px;
    height: 200px;

    &:first-child, &:last-child {
      &::before {
        content: "";
        display: block;
        width: 275px;
        height: 275px;
        background: #F48B26;
        position: relative;
        border-radius: 50%;
        left: -155px;
        top: -136px;
      }
    }
    &:last-child::before {
      left: -80px
    }
  }
</style>
```

<details>
  <summary>Top Solution:</summary>
  <pre><style>&{background:#F48B26;border:5vw dashed#FEFF58;margin:130 60;scale:1 5;*{margin:-48 60;scale:5 1;border-top:dotted 7ch#F48B26</style></pre>
</details>


## [2024/07/19](https://cssbattle.dev/play/zqsEhghz74OQZxY841Mh)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_Y9GeINv.png?alt=media">

#### My Solution:

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

#### My Solution:

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
  <summary>Top Solution:</summary>
  <pre><style>&{margin:-10 0;background:#25834A;border:solid 5pc#041E;*{margin:-20 90;background:#48BF7D</style></pre>
</details>

## [2024/07/17](https://cssbattle.dev/play/63uT8mAsvJRLBjA2dsct)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_apjnNh9.png?alt=media">

#### My Solution:

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

#### My Solution:

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

## [2024/07/15](https://cssbattle.dev/play/63FIG5VojdN2a8llcruA)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_Huomr0X.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main {
    background: #B53733;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    background: #EA7457;
    height: 160px;
    width: 190px;
    border-radius:80px;
    &::before {
      content: "";
      background: inherit;
      width: 30px;
      height: 150px;
      display: block;
      margin: -20px 0 0 80px;
      border: 25px solid #B53733;
    }
  }
</style>
```

## [2024/07/14](https://cssbattle.dev/play/m1cHlo8crbGrZEPvie07)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_cdoXsLV.png?alt=media">

#### My Solution:

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

#### My Solution:

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

## [2024/07/12](https://cssbattle.dev/play/zdlHeV5jrQqFujTJ6RcR)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_s6NqTP3.png?alt=media">

#### My Solution:

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