---
lab:
  title: 'ラボ 3.2: 製造オーダーの作成'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# ラーニング パス 3: Microsoft Dynamics 365 Supply Chain Management の基礎を学ぶ
# モジュール 4: 製造工程について説明する

## ラボ 3.2: 製造オーダーの作成

## 目的

製造オーダーは、生産プロセスを Supply Chain Management で開始するのに役立ちます。 このラボでは、製造オーダー フォームのユーザー インターフェイスと機能について学びます。 また、演習の最後までに、製造オーダーの作成と処理の方法についても学習します。

## ラボの手順

1. Dynamics 365 **Supply Chain Management ホーム** ページの右上で、**USMF** 企業と連携していることを確認します。

2. 必要に応じて、会社を選択し、メニューから **USMF** を選択します。

3. 左側のナビゲーション ペインで、 **[モジュール]**  >  **[生産管理]**  >  **[製造オーダー]**  >  **[すべての製造オーダー]** を選択します。

4. トップ メニューで、**[新しい製造オーダー]** を選択し、次のデータを入力します。

    - 品目番号: **D0002**

    - 数量: **10**

    - サイト: **1**

    - 倉庫: **11**

    - 配送: [今日の日付から 1 か月後の日付を選択する]

    - BOM 番号: **D0002BOM**

    - ルート番号: **000004**

5. **[作成]** ボタンを選択します。

品目 D0002 の数量 10 に対して新しい製造オーダーが作成されます。

6. **製造オーダー ([操作] ウィンドウ メニュー) &gt; プロセス &gt; 見積もり**を選択します。

7. **[見積]** ダイアログ ボックスの **[利益設定]** フィールドで **[標準]** を選択し、**[参照フィールド]** を選択して、**[OK]** ボタンを選択します。

製造オーダーの**状態**は、**見積**に変更されます。

8. **[スケジュール] ([操作] ウィンドウ メニュー) &gt; [製造オーダー] &gt; [スケジュール操作]** を選択します。

9. [**工程のスケジューリング**] ダイアログ ボックスで、**[スケジューリング指示]** フィールドの **[今日からフォワード]** を選択し、**[OK]** ボタンを選択します。

10. **[表示] ([操作] ウィンドウ メニュー) &gt; [関連情報] &gt; [容量予約]** を選択します。

11. **[容量予約]** ページで作成された新しいレコードを確認します。

12. **[すべての製造オーダー]** ページに戻ります。 製造オーダーの **[状態]** が **[スケジュール済み]** に変わります。

13. **[製造オーダー] ([操作]ウィンドウ メニュー) &gt; [プロセス] &gt; [リリース]** を選択します。

14. **[リリース]** ダイアログ ボックスで、**[参照フィールド]** を選択し、**[OK]** ボタンを選択します。

15. 製造オーダーの**状態**は**リリース済み**に変更されます。

16. **[製造オーダー] ([操作] ウィンドウ メニュー) &gt; [プロセス] &gt; [開始]** を選択します。

17. **[開始]** ダイアログ ボックスで、**[全般]** タブを選択します。

18. **[全般]** タブで、次を入力します。

    - 日付: **今日の日付**

    - 数量: **10**

    - 運用開始: **YES**

    - 今すぐ工順カードを転記する: **NO**

    - ピッキング リストを今すぐ投稿する: **NO**

19. **[OK]** ボタンを選択します。

製造オーダーの**状態**が**標準**に変わります。

20. **[表示] ([操作] ウィンドウ メニュー) &gt; [仕訳帳] &gt; [ピッキング リスト]** を選択します。

新しいピッキング リストの仕訳帳が 3 行で作成されます。

21. ピッキング リストの仕訳帳を転記します。

必要に応じて、[仕訳帳の転記] ウィンドウで **[OK]** を選択します。

22. **[すべての製造オーダー]** ページに戻り、**[表示] ([操作] ウィンドウ メニュー) &gt; [仕訳帳] &gt; [工順カード]** を選択します。

新しい工順カードの仕訳帳が 3 行で作成されます。

23. 3 行すべてで **[操作の完了]** フィールドを選択し、工順カードの仕訳帳を転記します。

24. **[すべての生産オーダー]** ページに戻り、[**生産オーダ ([操作] ウィンドウ メニュー) &gt; プロセス &gt; レポートを完了したものとして選択します。**。

25. [**完了レポート**] ダイアログ ボックスで、[**適正数量**] フィールドに **10** を入力します。 **End job**フィールドを選択し、**OK** を選択します。

製造オーダーの**状態**は**終了済**に変更されます。 品目番号 **D0002** の在庫は、サイト 1 と倉庫 11 で 10 ずつ増加します。

26. **[コストの管理 (操作ウィンドウ メニュー)&gt; [計算]&gt; [計算の詳細の表示] を選択します**。

**[原価計算の概要]** タブで、製造品目の最終原価計算を確認します。

 
