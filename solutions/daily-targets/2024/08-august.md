# August 2024

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
  <pre></pre>
</details>