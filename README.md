# good_golang_posts

這個專案用於整理一些自己覺得寫的不錯的 golang 相關資源，包含網站,文章等等

如果看到不錯的文章也歡迎丟PR，之後文章比較多的時候再來做詳細一點的分類。

本專案很多文章都是從[golangweekly](https://github.com/polaris1119/golangweekly)看到的，在此感謝所有整理資源在網路上分享的人們。

**分類**

- [系列文章](#系列文章)
    - [GitHub](#GitHub)
    - [鐵人賽](#鐵人賽)
- [底層實現](#底層實現)
    - [netpoller](#netpoller)
- [Standard library](#Standard-library)
    - [Context](#Context)
- [延伸應用](#延伸應用)
    - [goroutine pool](#goroutine-pool)
    - [定時任務](#定時任務)
- [設計模式 && 規範](#設計模式與規範)
- [議題](#議題)
- [K8s](#K8s)

## 系列文章

### 套件分類

- [go-awesome](https://github.com/shockerli/go-awesome) => 整理了各個領域常用套件，中文版本

### GitHub 

- [Effective Go](https://github.com/bingohuang/effective-go-zh-en)
- [Go語言愛好者週刊](https://github.com/polaris1119/golangweekly) 
- [over-golang](https://github.com/overnote/over-golang)
- [Golang-100-Days](https://github.com/rubyhan1314/Golang-100-Days)
- [Go-Questions](https://github.com/golang-design/Go-Questions)
- [Go語言設計與實現](https://draveness.me/golang/)

### 鐵人賽

- [Let's Eat GO ! 實務開發雜談by Golang](https://ithelp.ithome.com.tw/users/20080192/ironman/2194)

作者分享了一些實際開發上會遇到的問題，值得一看。

--- 

## 底層實現

### netpoller
- [epoll 與 netpoller](https://mp.weixin.qq.com/s?__biz=MzAxMTA4Njc0OQ==&mid=2651444736&idx=2&sn=262f63e85f9bc8edceca9b41c6ec730a&chksm=80bb08f2b7cc81e4ab1d87e78ffd5fa4e1407b40b493d0e411af1b0c9f7d3cc7180087ccc0c1&scene=132#wechat_redirect)
- [Go netpoller 原生網路模型原始碼講解](https://strikefreedom.top/go-netpoll-io-multiplexing-reactor)

---

## Standard library

### Context
- [圖解Go Context](https://mp.weixin.qq.com/s/e9xMLhDVOAOV3EbE6uGVig)
- [Go語言併發以及Context](https://mp.weixin.qq.com/s/fRb4G74LW-es87jxWkiByw)
- [Context底層實現](https://draveness.me/golang/docs/part3-runtime/ch06-concurrency/golang-context/#611-%E8%AE%BE%E8%AE%A1%E5%8E%9F%E7%90%86)
- [Go語言官方說明 Context 使用時機](https://mp.weixin.qq.com/s/Xv88vljtnDIRuLM0J_NSpA)

### Atomic
- [Go 語言標準庫中atomic.Value 的前世今生
](https://mp.weixin.qq.com/s/9aNfjX2UMQKLLgSW037_uQ)

---

## 延伸應用

### goroutine pool

- [如何裸寫一個goroutine pool](http://legendtkl.com/2016/09/06/go-pool/)
- [fasthttp goroutine pool 解析](http://legendtkl.com/2016/09/09/fasthttp-inside/)

### 定時任務 or 時間相關

- [gron 原始碼解析](https://mp.weixin.qq.com/s/gbF1ZSXe9N_m3SJUXkKvUA)
- [gron GitHub](https://github.com/roylee0704/gron)
- [Go TimingWheel 實現](https://www.luozhiyun.com/archives/444)
- [Go Timer 實現原理](https://www.luozhiyun.com/archives/458)

---

## 設計模式與規範

- [Uber Go語言規範 GitHub](https://github.com/xxjwxc/uber_go_guide_cn)

---

## 議題

- [Golang處理百萬級請求/分鐘](https://juejin.cn/post/6844903977574744072#heading-2)
- [如何寫出優雅的Go程式碼](https://draveness.me/golang-101/)
- [gRPC實操指南](https://mp.weixin.qq.com/s/ZUQQEn4SVLYcIdbW-6YFZQ)
- [go-zero 作者分享](https://xie.infoq.cn/article/aafdbf584a5d4111a2324adf8)
- [由併發模式來學習go channel 使用技巧](https://mp.weixin.qq.com/s/IMnqPFk-3yNEnsX4EpYlpQ)

### 面試經驗分享
- [值得每個Gopher 認真研讀：工作兩年收穫PingCAP、頭條和螞蟻的Offer
](https://mp.weixin.qq.com/s/acePzNpkHISLDkaNc-8vCA)

受益良多的一篇分享文

### Distributed System

- [知乎運用TIDB系統架構](https://mp.weixin.qq.com/s/k27rXayT0C7Sr_vwoIYrUw)

## K8s 

- [k8s學習路徑](https://www.infoq.cn/article/9dtx*1i1z8hsxkdrpmhk)
- [k8s學習之路](https://www.zhihu.com/question/279646705)

- [k8s網路策略](https://github.com/cloudnativeapp/meetup/blob/master/Kubernetes%20Course/%E4%BB%8E%E9%9B%B6%E5%BC%80%E5%A7%8B%E5%85%A5%E9%97%A8%20K8s%20-Kubernetes%20%E7%BD%91%E7%BB%9C%E6%A6%82%E5%BF%B5%E5%8F%8A%E7%AD%96%E7%95%A5%E6%8E%A7%E5%88%B6.pdf)

- [Kubernetes 30天學習筆記](https://ithelp.ithome.com.tw/articles/10192401)
- [其實我真的沒想過在美國上班也被拉來參加30天分享那些年我怎麼理解 kubernetes 的運作 系列
](https://ithelp.ithome.com.tw/users/20120317/ironman/2442)
- [Kubernetes 原始碼分析](https://www.bookstack.cn/books/source-code-reading-notes)

## Nginx

- [Nginx 原始碼解析](https://www.kancloud.cn/digest/understandingnginx/202587)
