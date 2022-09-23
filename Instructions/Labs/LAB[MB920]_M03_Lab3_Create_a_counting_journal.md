---
lab:
  title: '課題 3:棚卸仕訳帳を作成する'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>モジュール 3:Microsoft Dynamics 365 Supply Chain Management の基礎を学ぶ

## <a name="lab-3---create-a-counting-journal"></a>ラボ 3 - 棚卸仕訳帳を作成する

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. 左側のナビゲーション ペインで、 **[モジュール]**  >  **[在庫管理]**  >  **[仕訳入力]**  >  **[品目カウント]**  >  **[カウント]** の順に選択します。

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. ヘッダーと詳細情報を含む在庫棚卸仕訳帳フォームが表示されます

![ヘッダーと詳細情報が入力された在庫棚卸仕訳帳フォームのスクリーンショット。](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. アクション ペインで **[行の作成] -&gt; [オンライン]** の順に選択します。

6. **[手持在庫棚卸仕訳帳の作成]** ダイアログ ペインで、 **[倉庫]** 、 **[在庫状態]** 、[場所]、 **[ライセンス プレート]** の各フィールドを **[はい]** に設定します。 

![説明に従ってフィールドが設定された [手持在庫棚卸仕訳帳の作成] ダイアログ ペインのスクリーンショット。](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. **[手持在庫棚卸仕訳帳の作成]** ダイアログ フォームの下部にある **[OK]** を選択します。

品目 A0001 の手持数量は **[仕訳帳明細行]** セクションに表示され、サイト、倉庫、場所、ライセンス プレートで分割されます。

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - **[手持在庫]** 数量が **[カウント済]** 数量と同じ場合、 **[数量]** フィールドは空白になります。

    - **[カウント済]** フィールドの値が **[手持在庫]** フィールドを超える場合、 **[数量]** フィールドには正の値が含まれます。

    - **[カウント済]** フィールドの値が **[手持在庫]** フィールドより小さい場合、 **[数量]** フィールドには負の値が含まれます。

10. アクション ペインの **[検証]** ボタンを選択した後、 **[転記]** ボタンを選択します。

11. ページを閉じて、ホーム ページに戻ります。
