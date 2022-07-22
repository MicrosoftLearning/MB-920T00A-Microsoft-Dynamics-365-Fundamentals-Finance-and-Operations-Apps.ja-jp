---
lab:
  title: ラボ 2:Excel 統合
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116294"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>モジュール 1:Dynamics 365 財務と運用アプリの主な機能を調べる

## <a name="lab-2---excel-integration"></a>ラボ 2 - Excel 統合

財務と運用アプリに慣れたところで、少し時間を取って Excel 統合のシナリオを調べてみましょう。

### <a name="task-1-create-template"></a>タスク #1:テンプレートの作成

1. Finance and Operations の [ホーム] ページを開きます。 

2. **[モジュール]**  >  **[共通]**  >  **[共通]**  >  **[Office 統合]**  >  **[Excel ブック** **デザイナー]** に移動します。 ほとんどの移動は [モジュール] を通じて行われるため、通常はこれを指定しないことに注意してください。

3. フィルターで **VendorGroup** を検索します。

4. 使用可能なフィールドの一覧から、**仕入先グループ**、**説明**、**支払条件** の各フィールドを選択し、右矢印を選択して選択したフィールド ボックスに移動します。

5. アクション ペインで、 **[ブックの作成]** ボタンを選択します。

6. 右側の **[保存先]** パネルで、 **[ダウンロード]** ボタンを選択します。

7. **[名前を付けて保存]** を選択してファイルをダウンロードし、**ダウンロード** フォルダーに保存します。

8. **[共通]**  >  **[Office 統合]**  >  **[ドキュメント** **テンプレート]** の順に移動します。

9. **[新規]** を選択します。

10. 右側のパネルの **[テンプレートのアップロード]** セクションで、 **[参照]** ボタンを選択し、前にダウンロードしたファイルを選択します (既定の名前を使用した場合は DynamicsWorkbook です)。

11. **[テンプレート名]** フィールドに「**CustomVendorGroup**」と入力します。

12. **[OK]** を選択し、 **[保存]** を選択します。

### <a name="task-2-open-in-excel"></a>タスク #2:Excel で開く

1. **[調達]**  >  **[設定]**  >  **[仕入先]**  >  **[仕入先グループ]** の順に移動します。

2. **[Microsoft Office で開く]**  >  **[Excel で開く]** を選択して、アップロードした新しいテンプレート CustomVendorGroup を見つけます。

3. **CustomVendorGroup** を選択して、Excel テンプレートをダウンロードします。

4. ダウンロードした Excel テンプレートを保存してから開き、必要な場合は許可して、アクティブ化を閉じて、 **[編集を有効にする]** を選択します。 このアドインを信頼し、サインインします (求められた場合は、同じ資格情報を使用します)。

仕入先グループ テーブルのすべての既存のデータが Excel スプレッドシートに表示されます。

5. 新しいレコードを入力します。

6. **[仕入先グループ]** フィールドに「**100**」、 **[説明]** フィールドに「**Insurance Vendor**」、 **[支払条件]** フィールドに「**Net10**」と入力します。

7. Microsoft Dynamics Office アドイン アプリの **[発行]** ボタンを選択します。

8. **[仕入先グループ]** フォームを開き、新しいレコードが追加されていることを確認します。

