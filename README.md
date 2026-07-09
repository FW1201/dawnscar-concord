# 曙痕議約｜網頁卡牌遊戲原型

這是一個不需安裝依賴的單頁瀏覽器原型。開啟 `index.html` 即可試玩。

## 已完成

- 2 人（玩家對電腦）回合制對局
- 曦質、抽牌、角色部署、疲勞、傷害、交鋒與三領域控制
- 行動、裝備、場域的簡化可操作效果
- 聲望勝利、回合紀錄、響應式卡面 UI 與鍵盤焦點樣式
- 3 張 imagegen 原創插畫，儲存於 GitHub repo 並由 `raw.githubusercontent.com` 提供卡面與背景圖片

## 本機啟動

可直接雙擊 HTML；若需要本機伺服器：

```bash
python3 -m http.server 4173 -d projects/web/dawnscar-concord
```

再瀏覽 `http://localhost:4173`。

## 下一輪工作

將 60 張完整卡牌資料抽至 JSON，再加入完整命運、結盟、四人模式、牌組建構與後端對戰同步。
