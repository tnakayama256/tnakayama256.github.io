<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

<h3 align="center">メルマガ "中学生にもわかる Web3"</h3>

  <p align="center">
    中島聡さんのメルマガ"Life is Beautiful"で<br>
    Web3について学んだ。
    <br />
  </p>
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>目次</summary>
  <ol>
    <li>
      <a href="./web3index.md">TLDR</a>
    </li>
    <li>
      <a href="./what-is-web3.md">Web3とは</a>
      <ul>
        <li><a href="#">Web3</a></li>
        <li><a href="#">Web2.5</a></li>
        <li><a href="#">Web2.0</a></li>
      </ul>
    </li>
    <li><a href="bitcoin">Bitcoin</a></li>
    <li><a href="ethereum">Ethereum</a></li>
    <li><a href="defi">DeFi</a></li>
    <li><a href="nft">NFT</a></li>
    <li><a href="dao">DAO</a></li>
    <li><a href="fund">ファンド(a16z)</a></li>
    <li><a href="learn">Web3 学習法</a></li>
    <li><a href="feedback">感想</a></li>
    <li><a href="links">参照</a></li>
  </ol>
</details>

---

## DAO

### DAO

「エージェント問題」の解決策になりうる

> スマートコントラクトを活用することにより、（どんな組織にとっても最も重要な）資金の使い道を、経営者を雇わずに、メンバーの投票によって決める点が従来型の組織と大きく異なります。お金の流れが透明化され、エージェント問題（雇われた経営者が株主の利益よりも自分の利益を優先した行動をしてしまう）が回避できるなど、良い面もありますが、長期的な戦略を実行しにくいなどの欠点もあります。

> 日本では、「非営利型の一般社団法人は、収益事業を行った場合にのみ課税され、会費や寄付金などに対しては課税されない」という税制があるので、それが適用出来れば、DAO を発行した際の NFT の売り上げに対する課税を避けることが可能.

> 経営陣の代わりにスマートコントラクトを使って組織を運営するリーダーシップの不在.. 長期的な戦略を立てたり、（他の人がまだ理解できない）画期的なことをするのが不得意

> 個別のマーケティング案件への投資はメンバーの間の投票で比較的簡単に決められますが、継続性を持ったマーケティング活動だとか、収益を目指したサービス構築への開発投資などは、構造的に非常に難しくなっています

### NounsDAO

最も DAO らしい DAO

1. 複数のコントラクトで構成することにより、アップデートを可能にしている
2. 画像を全てオンチェーンで生成している
3. 画像は SVG で生成している

> 「開発者に対するインセンティブが、スマートコントラクトにより NFT で自動的に支払われることになっている」

> 通常の会社にあるような、雇用関係やストックオプションではなく、スマートコントラクトの、それも後から書き換えることが決して出来ない部分に「Nounders への報酬の提供方法」が記述されており、それが「自動的に実行されてしまう」という点が、Nouns の最大の発明

> 「エグジットしなければいけない」というインセンティブが全く働かない

> 私はここにこそ、Web3 が目指す「非中央集権的な世界」を作る鍵があると思うのです。GAFA を生み出してきた、シリコンバレー型のビジネスモデルとは正反対のビジネスモデルです。

> 非営利法人と Nouns 型のトークンを活用したインセンティブモデルの組み合わせです。サービスを運営する主体は、NPO、NGO などと呼ばれる非営利法人が行います（日本では、「非営利型の一般社団法人」です）。そこが「社会に価値をもたらす」というビジョンの元にプロジェクトを立ち上げ、開発者集団とスマートコントラクトで契約を結び、作ったサービスを社会に提供するのです。

> 大切なことは、開発者のインセンティブを非営利法人の目的と一致させることです。

> Web3 の信者たちは、「DAO こそが株式会社に変わる Web3 時代にふさわしい姿だ」と主張しますが、それはリーダーシップ不在の DAO の運営の難しさを理解していないから言える言葉なのです。DAO の中でも「もっとも DAO らしい DAO」と言われている NounsDAO ですら、結局、その運営に真剣に取り組んでいるのはファウンダーとメンバーの一部であり、彼らのリーダーシップなしが必須なのです。

> スマートコントラクトは、一度ブロックチェーンにデプロイしてしまうと、アップデートが不可能です。しかし、アプリケーションを複数のコントラクトで構成し、他のコントラクトを参照するためのアドレスをデータとして持っておき、アップデート可能にしておけば、一番ルートにあるコントラクト以外はアップデートが可能になります。

> Nouns の場合、４つのコントラクトから構成されており、NounsToken 以外のコントラクトはアップデートが可能。

-   NounsToken: ルートにある NFT トークンを実装しているコントラクト
-   NounsDescriptor: シード（さまざまな属性）を元に SVG 画像を生成するコントラクト
-   NounsSeeder: それぞれの NFT にユニークなシードを生成するコントラクト
-   NounsAuctionHouse: オークションを実装するコントラクト

NounsDescriptor で、外部ツールと協力して、ドット絵をベクトルデータに変換している。

> ウォレットは完全にスマートコントラクトで動き,Nouns を創立した人たち（Nounders と呼ばれています）ですら,勝手に動かすことはできない.そもそも,DAO は法人でもありませんし銀行口座を持たなくても運営できてしまいます.現在,「銀行口座を持たずに会社を運営」することが日本では想定されていません.この想定から変えていかないと日本で DAO を運営するのはまだ難しいでしょう.

<p align="right"><a href="fund">ファンド ></a></p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Twitter - [@TaNakayama14](https://twitter.com/TaNakayama14)

Github: [pages](https://github.com/tnakayama256/tnakayama256.github.io)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

<!-- ## Acknowledgments
-   []() -->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->