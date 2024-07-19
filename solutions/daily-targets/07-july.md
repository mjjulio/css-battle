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