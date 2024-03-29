---
demo:
  title: 'デモ 3:プロジェクト原価についてさらに確認する'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## デモ 3 - プロジェクト原価を確認する

このデモではContoso Consulting プロジェクトに課金する予定の時間と経費の作成をご説明します。 Web およびモバイル表現用に最適な形式のエントリーをホロ下げ、承認プロセスの管理のためのワークフローの使い方について見ていきましょう。

1. **「Dynamics 365 for Finance and Operations」** のナビゲーション ペインで、**「モジュール」 > 「プロジェクト管理と会計」 > 「タイムシート」 > 「マイ タイムシート (モバイル用最適化済み)」** を選択します。  
    まず、モバイル デバイスを使用中でなくても、**[マイ タイムシート (モバイル用に最適化済み)]** オプションを選択すると、モバイルで使いやすい形式で認識されます。

    ![マイ タイムシート (モバイル用最適化済み) が強調表示されているプロジェクト管理と会計メニューのスクリーンショット。](./media/projops_costs_1_select_my_timesheets.png)  

    この最適化は Microsoft のビジネス アプリケーションの主な差別化点であり、web とモバイル用途の間で習得すべき項目がそう違わないようにしています。

1. 右上の会社情報欄で接続先法人が **USSI** であることを確認してください。 そうでない場合は、法人を **USSI** に変更してください。

1. **[マイ タイムシート]** ページで **[新規]** を選択します。  
    次に、構成済み設定に基づく新規タイムシートを作成しましょう。

1. **[新しいタイムシート]** ペインで **[日付]** ボックスをポイントします。  
    入力した日付によりタイムシートの期間が決まります。

1. **[お気に入りから作成]** をポイントします。  
    お気に入りを保存してあれば、そこから作成して時間を節約できます。

1. 完了したら、 **[OK]** を選択します。

1. **[マイ タイムシートの詳細]** ページで **[新規 +]** アイコンを選択します。

1. **[新しいタイムシートの明細行]** ペインで **[法人]** ボックスをポイントします。  
    新規タイムシート明細行が開き、ここに顧客、プロジェクト、カテゴリ、プロパティ、税パラメーター等の詳細が記載されています。 時間エントリーが組織の他会社のためであれば他の法人を選択することもできます。

1. **[プロジェクト ID]** メニューを選択します。

1. **[Contoso Consulting]** プロジェクトなど、選択可能なプロジェクトからいずれか 1 つを選択します。

1. 完了したら、 **[OK]** を選択します。  
    時間エントリー用のモバイル最適画面が開き、プロジェクトとカテゴリのために日々の自分の時間をこの場合は **サービス** に予約開始できます。

1. **[時間入力]** ページの **[月]** ボックスに、「**8**」と入力します。  
    これは一日の時間数エントリーを表現したものです。

    ![[時間入力] ページのスクリーンショット。](./media/projops_costs_2_mon_box.png)

1. **[内部コメント]** ボックスにコメントを追加します。 次に例を示します。 **「新しいバイクについて話し掛けようと思う**。  
    プロジェクト反対の内部および外部コメントも入力して、全当事者が記録されている時間数の性質を把握できるようにします。

1. **[外部コメント]** ボックスにコメントを加えます。 たとえば、**"チェーンを調節してフリートの前輪を揃える"** のようなものです。

1. ナビゲーション バーで **[保存]** を選択します。

1. 左のナビゲーション メニューの **[タイムシート]** から **[マイ タイムシート]** を選択します。

1. **[マイ タイムシート]** ページで、以前作成した時間入力を選択します。

1. **[タイムシート]** タブの [カテゴリ] をポイントします。  
    次に、コンピュータへ戻り、 Web タイムシート フォームから時間を確認しているとします。 まだカテゴリや時間数等同じ情報が見えます。

1. **[明細行の詳細]** で **[内部コメント]** と **[外部コメント]** をポイントします。  
    以前入力したコメントも見直すことができます。 情報はそこにありますが、レイアウト形式が少々違います。 このフォーマットは誰かが複数のプロジェクトやカテゴリに割り当てられているとき等、特に時間を見直して確認しやすくなるため最終確認によく使います。

1. ナビゲーション バーで **[ワークフロー]** タブを選択します。  
    タイムシートに納得できたら送信できます。 必要な承認は会社の方針別に基づいて実装段階に組織別に決定されます。

1. **[タイムシート ワークフローの確認]** ペインで **[送信]** を選択します。

1. その他のコメントがある場合は、**[タイムシート ワークフローの確認 – 送信]** ペインで追加します。

1. **[Submit](送信)** をクリックします。

1. **[時間トランザクション]** ページを開きます。 **[時間トランザクション]** タブがグレー表示されている場合は、**[マイ タイムシート] ページ** に移動して、以前に作成したタイムシートを選択します。

1. **[時間トランザクション]** ページでページを確認します。  
    承認されたら、結果が投稿され、[時間トランザクション] ページに表示されます。 法人、プロジェクト、カテゴリ、時間数等の関連情報、さらに、この場合には原価価格と販売価格のビューさえ見えます。  

次に、伝票トランザクションへドリルダウンすることもできます。

1. ナビゲーション バーで、**伝票** を選択します。

1. **[伝票トランザクション]** ページで、**[勘定科目]** セクションと **[勘定科目名]** セクションをポイントします。  
    これらのセクションで総勘定元帳さらに使用予定の科目への影響を確認できます。  

次に上の Contoso consulting プロジェクトにつて経費計上を作成します。

1. ナビゲーション ウィンドウで、**[モジュール] > [経費管理] > [自分の経費] > [経費レポート]** を選択します。

1. **[経費管理]** ページの **[レポート]** タブで、**[+ 新しい経費レポート]** を選択します。

1. **[新しい経費レポート]** ペインの **[目的] ボックス**にタイトルを入力します。 たとえば、「**Contoso – Feb2021**」などです。

1. **[OK]** を選択します。

1. **[経費]** ページで、**[+ 新しい経費]** を選択します。  
新しい経費明細行が表示されます。

1. **[経費カテゴリ]** 列で、**[カテゴリ]** ドロップダウン メニューから **[燃料]** を選択します。  
ここでは燃料の明細を表す新たな経費を入力できます。

1. **[トランザクション金額]** 列に、「**25.00**」と入力します。

1. **[通貨]** 列で、**[JPY]** を選択します。

1. **[トランザクション日付]** 列で日付を選択します。 たとえば、**2021/2/1** などとします。  
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
    この時点で、出張方針と経費承認のフローが有効になります。 原価が計上されて Contoso Consulting プロジェクトに適用され、課金可能であれば後日請求書に含めます。

このデモで Contoso Consulting プロジェクトに課金された時間と経費のエントリーを処理しました。 事例を Web とモバイルの両方のフォーマットで見たほか、 USSI が必要としている承認の管理のためのワークフローの使い方も把握しました。
