---
lab:
  title: 'ラボ 4:製造オーダーを作成します。'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>ラボ 4 - 製造オーダーの作成

## <a name="objectives"></a>目標

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

あなたの会社への新たな製造オーダーを作成しなければなりません。

## <a name="lab-setup"></a>ラボのセットアップ

   - **推定時間**:5 分

## <a name="instructions"></a>Instructions

1. Finance and Operations の [ホーム] ページの右上で、USMF 社の作業を行っていることを確認します。

1. 必要な場合、会社を選び、メニューから **USMF** を選択します。

1. 左側のナビゲーション ペインで、 **[モジュール]**  >  **[生産管理]**  >  **[製造オーダー]**  >  **[すべての製造オーダー]** を選択します。

1. トップ メニューで、**[新しい製造オーダー]** を選択します。

1. **[ID]** の **[品目番号]** ボックスに「**D0001**」と入力し、識別された品目を選択します。

1. **[生産]** の **[出荷]** ボックスで、今日の日付から 1 か月後の日付を選択します。  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. **数量**ボックスに、**20** と入力します。

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![完成した [製造オーダーの作成] ペインを表示したスクリーンショット](./media/lp1-m4-new-production-order-pane.png)

1. **［作成］** を選択します
