# R-ggplot2

#### ggplot2 graph 



## 軸目盛りの長さの制御 (内向きも含む)
参考) https://qiita.com/kattsu2003/items/266e1a0709961f5ba81f
theme内の unitの長さで変更可能
```r
 theme(axis.ticks.length = unit(4, "mm"))
 theme(axis.ticks.length = unit(-2, "mm")) #内向き

```
