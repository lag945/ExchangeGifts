# ExchangeGifts
Exchange gifts and NO bugs :)

# [Online Demo](https://lag945.github.io/ExchangeGifts/index.htm)

# 使用說明
將參加人數n人，每個人不重複至編號1~n，程式會隨機抽出每個配對，如3號抽獎者抽到5號抽獎者的禮物等...
此程式每個人都會抽到，且不會抽到自己的禮物。

# 演算法
將參加者隨機打亂，然後排第一拿排第二的禮物，排第二拿排第三的禮物...排最後拿排第一的禮物

# 不想跑程式的做法
每個人選自己想要的禮物，最後兩個選的人一起上場即可(排列組合有 (1)剩兩個別人的禮物，隨便選 (2) 有一個是自己的，別選自己 )
# TODO
使用cookie或[Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)儲存歷史狀態
