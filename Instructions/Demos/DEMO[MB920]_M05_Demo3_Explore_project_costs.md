---
demo:
  title: 'デモ 3:プロジェクト原価についてさらに確認する'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>デモ 3 - プロジェクト原価を確認する

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. 
             **「Dynamics 365 for Finance and Operations」** のナビゲーション ペインで、**「モジュール」 > 「プロジェクト管理と会計」 > 「タイムシート」 > 「マイ タイムシート (モバイル用最適化済み)」** を選択します。  
 まず、モバイル デバイスを使用中でなくても、**[マイ タイムシート (モバイル用に最適化済み)]** オプションを選択すると、モバイルで使いやすい形式で認識されます。

    ![マイ タイムシート (モバイル用最適化済み) が強調表示されているプロジェクト管理と会計メニューのスクリーンショット。](./media/projops_costs_1_select_my_timesheets.png)  

    この最適化は Microsoft のビジネス アプリケーションの主な差別化点であり、web とモバイル用途の間で習得すべき項目がそう違わないようにしています。

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. **[マイ タイムシート]** ページで **[新規]** を選択します。  
    次に、構成済み設定に基づく新規タイムシートを作成しましょう。

1. **[新しいタイムシート]** ペインで **[日付]** ボックスをポイントします。  
    入力した日付によりタイムシートの期間が決まります。

1. **[お気に入りから作成]** をポイントします。  
    お気に入りを保存してあれば、そこから作成して時間を節約できます。

1. 完了したら、 **[OK]** を選択します。

1. **[マイ タイムシートの詳細]** ページで **[新規 +]** アイコンを選択します。

1. **[新しいタイムシートの明細行]** ペインで **[法人]** ボックスをポイントします。  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. **[プロジェクト ID]** メニューを選択します。

1. **[Contoso Consulting]** プロジェクトなど、選択可能なプロジェクトからいずれか 1 つを選択します。

1. 完了したら、 **[OK]** を選択します。  
    時間エントリー用のモバイル最適画面が開き、プロジェクトとカテゴリのために日々の自分の時間をこの場合は **サービス** に予約開始できます。

1. **[時間入力]** ページの **[月]** ボックスに、「**8**」と入力します。  
    これは一日の時間数エントリーを表現したものです。

    ![[時間入力] ページのスクリーンショット。](./media/projops_costs_2_mon_box.png)

1. このデモではContoso Consulting プロジェクトに課金する予定の時間と経費の作成をご説明します。  
    プロジェクト反対の内部および外部コメントも入力して、全当事者が記録されている時間数の性質を把握できるようにします。

1. Web およびモバイル表現用に最適な形式のエントリーをホロ下げ、承認プロセスの管理のためのワークフローの使い方について見ていきましょう。

1. ナビゲーション バーで **[保存]** を選択します。

1. 左のナビゲーション メニューの **[タイムシート]** から **[マイ タイムシート]** を選択します。

1. **[マイ タイムシート]** ページで、以前作成した時間入力を選択します。

1. **[タイムシート]** タブの [カテゴリ] をポイントします。  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. **[明細行の詳細]** で **[内部コメント]** と **[外部コメント]** をポイントします。  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. ナビゲーション バーで **[ワークフロー]** タブを選択します。  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. **[タイムシート ワークフローの確認]** ペインで **[送信]** を選択します。

1. その他のコメントがある場合は、**[タイムシート ワークフローの確認 – 送信]** ペインで追加します。

1. **[Submit](送信)** をクリックします。

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. **[時間トランザクション]** ページでページを確認します。  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

次に、伝票トランザクションへドリルダウンすることもできます。

1. ナビゲーション バーで、**伝票** を選択します。

1. **[伝票トランザクション]** ページで、**[勘定科目]** セクションと **[勘定科目名]** セクションをポイントします。  
    これらのセクションで総勘定元帳さらに使用予定の科目への影響を確認できます。  

次に上の Contoso consulting プロジェクトにつて経費計上を作成します。

1. ナビゲーション ウィンドウで、**[モジュール] > [経費管理] > [自分の経費] > [経費レポート]** を選択します。

1. **[経費管理]** ページの **[レポート]** タブで、**[+ 新しい経費レポート]** を選択します。

1. 右上の会社情報欄で接続先法人が **USSI** であることを確認してください。

1. **[OK]** を選択します。

1. **[経費]** ページで、**[+ 新しい経費]** を選択します。  
新しい経費明細行が表示されます。

1. **[経費カテゴリ]** 列で、**[カテゴリ]** ドロップダウン メニューから **[燃料]** を選択します。  
ここでは燃料の明細を表す新たな経費を入力できます。

1. **[トランザクション金額]** 列に、「**25.00**」と入力します。

1. **[通貨]** 列で、**[JPY]** を選択します。

1. そうでない場合は、法人を **USSI** に変更してください。  
    詳細を記入し終えたら、経費を保存します。

1. **[保存]** を選択します。

1. 左側のナビゲーション メニューの **[ワークスペース]** で、**[経費管理]** を選択します。

1. **[経費管理]** ページで、作成した経費レポートを選択します。

1. **[経費レポート]** ページで、**[プロジクト ID]** ボックスを選択したら、**[00000093 Contoso Consulting]** を選択します。  

次に燃料が Contoso Consulting プロジェクトに借方計上されたことや追加の経費情報も記入できます。

1. **[追加情報]** ボックスをポイントします。

1. 画面下部の右側で **[保存して続行]** を選択します。

1. 画面の右側で **[送信]** を選択します。

1. その他のコメントがある場合は、**[コメント]** ボックスに追加します。

1. **[Submit](送信)** をクリックします。

1. **[経費管理]** ページで、**[承認の状態]** 列をポイントします。  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
