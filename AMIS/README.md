# AMIS
## 公司簡介
Amis 是一個實作及研究區塊鏈應用的軟體科技公司，目前產品主要有以下幾大方向：

1. 數位資產保管服務 (Digital Assets Custody Service)
2. 帳聯網
3. 以太坊研究，密碼學研究，及相關開源軟體
4. 區塊鏈服務 (Blockchain-as-a-Service, BaaS)

## 數位資產保管服務 (Digital Assets Custody Service)

AMIS 數位資產保管服務是一種錢包服務，它包含兩個主要的元件：

1. 私鑰保管。
2. 節點管理。

我們提供高可用度的 API，並且提供高度安全的私鑰管理服務，以下幾項重點資安特色：

1. 混淆加密：我們發明了獨特的遞迴多層分散式加密，讓所有的私鑰不落地，也不經過任何的網路傳輸。
2. 主動備份：無需額外設定，私鑰皆經過加密備份處理，保證其可用性。
3. 服務端多重驗證：所有的交易都會經過服務端多重驗證。
4. 支援多種政策設定: 包含錢包政策、交易與IP白名單設定。
5. 主動偵測並通報異常交易。

## 帳聯網 / 區塊鏈服務 (Blockchain-as-a-Service, BaaS)

一個基於以太坊(Ethereum，一種區塊鏈平台，是開放原始碼的專案)，利用以太坊作為基礎架構所建立的服務 帳聯網有一些特性：

* 多型態的節點：任何公司、政府單位都可以連接到帳聯網上，我們稱作節點。在這裡大家共享著一本帳簿，任何交易都無法被竄改。政府在這裡擔任監管的角色。
* 快速交易結算(Clear)：現在金融單位之間的對帳都需要透過財金資訊股份有限公司（財金公司隸屬於中央銀行的管轄，負責所有跨金融單位之間的交易）。 透過區塊鏈的去中心化特性，可以讓金融單位不需要透過這個中間人，即可完成結算，而且是在交易發生的當下即可完成結算。對於金融機構來說，這個技術每年可以幫它們節省非常多的開銷。
* 結合支付：支付這個行為，如果用最簡單的方式理解它，其實就是錢的流動加上付款收據（證明你付了多少錢、買了什麼商品)，一般民眾可以透過自己所屬的銀行的節點，參與這個網路。你可以支付或轉帳給帳聯網上的任何人或任何單位，而且僅用非常低的成本(這個成本可以由你的銀行承擔，因為夠低）。而且每一次的交易行為都會有收據，紀錄上共享帳本上，不用擔心雙方不認帳。如果你用過微信支付或是支付寶，帳聯網會形成就類似那種生態，不同的點是民眾不用擔心自己的交易紀錄、金錢狀態被單一的公司(騰訊、阿里巴巴)所掌控，因為沒有人可以控制帳聯網，所有節點都是平等的。
* 智能合約：由於以太坊的特性，我們可以利用智能合約創造很多服務，譬如保險理賠、身份證明、食品履歷。這些服務可以跟帳聯網下的金融架構、支付系統結合，形成一個龐大又多元的生態圈。

## 以太坊研究及相關開源軟體

### Istanbul Byzantine Fault Tolerance ([IBFT](https://github.com/ethereum/EIPs/issues/650)) 共識演算法
共識演算法是比較學術性質的研究，為了讓區塊鏈之間的交易更有效率，我們需要新的演算法。由於這個演算法的特性，例如：區塊交易最終性，高交易處理效能，易於控管等等，讓它非常適合帳聯網。 比較特別的是，這個產品並非營利性質的，會以開放原始碼的方式貢獻到 Github 上的 Ethereum 以及 Quorum 專案。 Ethereum 有一個企業版本，數十間公司組成了企業以太坊聯盟 (Enterprise Ethereum Alliance) 要開發這個專案。 我們研發共識演算法主要是為了幫助企業版以太坊的開發。希望在聯盟中我們公司會是一個重要的研發主力。

### Casper/Plasma/Sharding
AMIS 研究的方向也盡可能的和 [Ethereum Foundation](https://www.ethereum.org/foundation) 同步，目前我們除了 IBFT 之外，也在 [Go-ethereum](https://github.com/ethereum/go-ethereum) 或是一般稱的 Geth，以及 [pyethereum](https://github.com/ethereum/pyethereum) 有許多貢獻。近期也積極參與社群上有關 Casper, Plasma, Sharding 的開發與討論。

### 開源軟體 Open source
我們也致力於以太坊及後端技術相關的開源軟體開發，目前我們大部分的開源都放在[github/getamis](https://github.com/getamis)裡。部分相關介紹也可以在我們的 [Medium@getamis](https://medium.com/getamis) 上面找到。裡面除了介紹 [IBFT](https://medium.com/getamis/istanbul-bft-ibft-c2758b7fe6ff)，[合約及服務](https://medium.com/getamis/sol2proto-d28932673cf9)，甚至 [GRPD 與區塊鏈的討論](https://medium.com/getamis/%E7%95%B6%E5%8D%80%E5%A1%8A%E9%8F%88%E9%81%87%E4%B8%8A-gdpr-f3479ad16763)，及[開源軟體授權](https://medium.com/getamis/%E9%96%8B%E6%94%BE%E6%BA%90%E7%A2%BC%E6%8E%88%E6%AC%8A%E6%A6%82%E8%A7%80-%E4%B8%8A-45309a387c64)。


## 職缺資訊
* [DApp Developer/Blockchain Engineer](dapp-developer.md)
* [Frontend Engineer](frontend-engineer.md)

