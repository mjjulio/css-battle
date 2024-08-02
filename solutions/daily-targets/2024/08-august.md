# August 2024

## [2024/08/02](https://cssbattle.dev/play/CQQbSxYOzC3GHPUA8FKS)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fe6YbeBahWNPT7VpE2rE2p85byxa2%2Ftargets%2Ftarget_8a5pJMu.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
&lt;style&gt;
  * {
    margin: 0;
    background: #49C85B;
  }
  main {
    height: 100vh;
    width: 100vw;
    position: relative;
  }
  div {
    background: #1F7D3B;
    height: 180px;
    width: 180px;
    border-radius: 50%;
    position: absolute;
    top: 60px;

    &:nth-child(2) {
      height: 160px;
      width: 160px;
      top: 70px;
      left: 90px;
    }
    &:nth-child(3) {
      height: 140px;
      width: 140px;
      top: 80px;
      left: 170px;
    }
    &:nth-child(4) {
      height: 120px;
      width: 120px;
      top: 90px;
      left: 240px;
    }
    &:nth-child(5) {
      height: 100px;
      width: 100px;
      top: 100px;
      left: 300px;
    }
  }
&lt;/style&gt;
```

<details>
  <summary>Top Summary:</summary>
  <pre></pre>
</details>


## [2024/08/01](https://cssbattle.dev/play/CQQbSxYOzC3GHPUA8FKS)

<img width="400px" height="300px" loading="lazy" src="https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fe6YbeBahWNPT7VpE2rE2p85byxa2%2Ftargets%2Ftarget_HiiHEOA.png?alt=media">

#### My Solution:

```html
<main>
  <div></div>
  <div></div>
</main>
&lt;style&gt;
  * {
    margin: 0;
    background: #301E53;
  }
  main {
    margin: 50px;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-row: repeat(2, 1fr);
  }
  div {
    width: 100px;
    height: 100px;
    background: #301E53;
    color: #766D94;

    &:first-child {
      box-shadow: inset 50px 50px;
    }
    &:last-child {
      grid-area: 2 / 3;
      box-shadow: inset -50px -50px;
    }
  }
&lt;/style&gt;
```

<details>
  <summary>Top Summary:</summary>
  <pre>&lt;style&gt;*{box-shadow:-53q 53q,53q -53q,0 0 0 50px#766D94,inset 6in 0;color:301F52;*{margin:25%</pre>
</details>