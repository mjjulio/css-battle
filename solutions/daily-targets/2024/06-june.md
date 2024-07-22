# June 2024

## [2024/06/26](https://cssbattle.dev/play/dqUja1HgyVAreGb9jWAd)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_hBT5NLr.png?alt=media">

```html
<main>
  <div></div>
  <div></div>
</main>
<style>
  * {
    margin: 0;
  }
  main, div {
    --color1: #48BF7D 0 30px;
    --color2: #024817 0;
    --options: ;
    background: radial-gradient(circle, var(--color1), var(--color2)) var(--options);
  }
  main {
    height: 100vh;
  }
  div {
    width: 200px;
    height: 200px;
    position: absolute;
    top: 50px;
    left: 100px;
    --color1: #48BF7D 0 20px;
    --color2: transparent 0;
    --options: top left/100px 100px;

    &:last-child {
      --color1: #176C36 0 20px;
      rotate: 45deg;
    }
  }
</style>
```


## [2024/06/25](https://cssbattle.dev/play/qKIRr3xZYc2T6RJLdmSy)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_N1QVAzZ.png?alt=media">

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
    margin-top: -80px;
  }
  div {
    width: calc(100% - 40px);
    height: 100px;
    background: #81008F;
    border: solid #DBBEDF;
    border-width: 0 20px 20px;
    
    &::after {
      content: "";
      display: block;
      height: 20px;
      width: 180px;
      background: #81008F;
      position: relative;
      top: 100px;
      left: 90px
    }

    &:nth-child(even)::after {
      left: 130px;
      width: 100px;
    }
  }
</style>
```


## [2024/06/24](https://cssbattle.dev/play/fQLj0ZRJsJD5jsCq7XLA)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_jQJ1dB1.png?alt=media">

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
    background: #EDAF38;
    height: 100vh;
  }
  div {
    --degree: 90deg;
    background: linear-gradient(var(--degree),
      #FFFFCD 0 30px,
      #EDAF38 30px 60px,
      #FFFFCD 60px 90px,
      #EDAF38 90px);
    width: 160px;
    height: 140px;
    float: left;
    margin-bottom: 20px;
    
    &:nth-child(2) {
      --degree: 180deg;
      width: 240px;
    }
    &:nth-child(3) {
      --degree: 0deg;
      width: 240px;
    }
    &:nth-child(4) {
      --degree: 270deg;
    }
  }
</style>
```


## [2024/06/23](https://cssbattle.dev/play/IXVliJZnb7hcDJk8xloq)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_peK94Xk.png?alt=media">

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
    background: #0A6190;
    height: 100vh;
  }
  div {
    background: #328FC1;
    width: 80px;
    height: 80px;
    position: relative;
    top: 35px;
    left: 10px;
    color: #328FC1;
    box-shadow:
      50px 50px, 100px 100px, 150px 150px, 200px 100px, 250px 50px, 300px 0;
  }
</style>
```

## [2024/06/22](https://cssbattle.dev/play/q4Ut5riDVVIzfgfNFBPm)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_CBJY7mQ.png?alt=media">

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
    background: #243D83;
    height: 100vh;
    display: flex;
    gap: 60px;
  }
  div {
    --border1: 120px;
    --border2: 180px;
    background: linear-gradient(
      #6592CF 0 var(--border1),
      #243D83 var(--border1) var(--border2),
      #6592CF var(--border2));
    height: 100%;
    width: 80px
  }
  div:nth-child(2) {
    --border1: 180px;
    --border2: 240px;
    width: 120px;
  }
</style>
```