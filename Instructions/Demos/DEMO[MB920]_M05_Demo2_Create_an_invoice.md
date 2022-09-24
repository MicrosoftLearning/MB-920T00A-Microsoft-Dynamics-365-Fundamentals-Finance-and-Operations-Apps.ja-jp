---
demo:
  title: 'デモ 2:請求書の作成'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>デモ 2 - 請求書の作成

1.  **[プロジェクト管理]** ワークスペースに移動します。  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1.  **[アクティブなプロジェクト]**  テーブルの **[プロジェクト ID]**  列で、 **[00000093 Contoso Consulting]** を選択してください。  

1. 次に、 **[プロジェクト仮発行請求書]**  ページを開いて、Contoso Consulting 向けの処理済みの全請求書を確認します。 

1. アクション ペインの **[請求]**  タブで、 **[プロジェクト仮発行請求書]** を選択します。 

1.  **[プロジェクト仮発行請求書]**  ページのナビゲーション バーで、 **[新規]** 、 **[仮発行請求書]** の順に選択します。  
    これは簡単な時間/実費払い請求書なので、請求ルールから仮発行請求書のオプションを選択する必要はありません。 

    ![[プロジェクト仮発行請求書] ページで新規仮発行請求書が強調表示されているスクリーンショット。](./media/projops_invoice_1_new_invoice_proposal.png)

1.  **[仮発行請求書作成]**  ペインで **[トランザクション選択]** の下のボックスをポイントします。  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![[仮発行請求書作成] ペインの [トランザクション] セクションが強調表示されているスクリーンショット。](./media/projops_invoice_2_select_transactions.png)

1.  **[プロジェクト]**  ドロップダウン メニューから **[00000093 Contoso Consulting]** を選択します。 

1. ここの例では、 **[請求日]** が **[21/2/1]** 、 **[開始日]**  が **[21/2/1]** 、[終了日] が本日に設定されるようにしてください。  
    選択したら、次に検索ボタンでこれらのパラメータに合致するトランザクションを選択します。

1.  **[検索]** を選択します。  
    このデモではプロジェクト運営の範囲内での単一プロジェクトについて請求書を発行するプロセスを学習します。

1.  **[プロジェクト トランザクション]**  タブで **[すべて選択]** を選択します。

1.  **[OK]** を選択します。 

1.  **[仮発行請求書]**  ページで **[金額請求]**  列をポイントします。  
    ここに請求金額、要約、時間数トランザクション、経費が見えます。

    ![請求書明細行金額の列が強調表示された [仮発行請求書] ページのスクリーンショット。](./media/projops_invoice_3_invoice_line_amount_column.png)

1.  **[時間]**  タブをポイントします。 

1.  **[経費]** タブをポイントします。  
    切り替えて経費トランザクションタを確認することもできます。  
次に、合計金額ボタンを確認し、原価と収入の観点で請求書の内容を見ましょう。

1. ナビゲーション バーで、 **[合計]** を選択します。

1.  **[合計]** ページで **[総勘定元帳]** 列、 **[顧客]**  列、 **[行割引列]** をポイントします。  
    合計画面にその影響が総勘定元帳にどう反映されるかを確認したり、与信限度額や割引、消費税、請求書による正味の影響などの顧客情報も確認できます。 

1. 画面右上で、 **[X]**  を選択してページを閉じます。  
    請求書の多数一括発行も可能ですが、デモの目的のためここでは一回のみの材料プロジェクトを取り上げます。 

1.  **[仮発行請求書]**  ページのナビゲーション バーで、 **[印刷プレビュー]** を選択します。 

1. ダイアログ ボックスで **[印刷プレビュー]** を選択します。  
    ここでは見積もり送り状の印刷プレビュー例をご覧いただきます。 

1. **[X]**  を選択してページを閉じます。  
    すべての情報を確認し請求書の印刷プレビューがよければ、仮発行請求書を発行します。

1. ナビゲーション バーで、 **[発行]** を選択します。

1.  **[パラメーター]**  タブを選択します。

1.  **[パラメーター]** の下の **[発行]**  を **[はい]** に設定します。

1.  **[印刷オプション]** の **[請求書印刷]** を **[はい]** に設定します。

1.  **[OK]** を選択します。

1.  **[請求書]**  ページで **[請求書]** 番号をポイントします。  
    これで作成された請求書の番号が割り振られました。  
    請求書を発行したら、次は請求書仕訳帳で情報を再確認して元帳のトランザクションをドリルダウンします。

1.  **[プロジェクト管理]** ワークスペースに移動します。

1.  **[進行中のプロジェクト]**  テーブルでプロジェクト **[00000093** **Contoso consulting]** を選択します。

1. [アクション] ペインの **[請求]**  タブで **[請求書仕訳帳]** を選択します。

1.  **[請求書仕訳帳]**  ページのアクション バーで **[伝票]** を選択します。

1.  **[伝票トランザクション]**  ページで **[勘定科目]** 列をポイントします。  
    そのプロジェクトの明細書の範囲で項目の結果と財務的把握も可能になります。

1.  **[プロジェクト管理]**  ワークスペースに移動します。 

1.  **[進行中のプロジェクト]**  テーブルで **[00000093 Contoso Consulting] プロジェクト**を選択します。

1.  **[Contoso Consulting]**  ページのナビゲーション バーで **[管理]** を選択します。  
    ここにプロジェクトの全明細が表示されます。  
    次に、プロジェクトの明細書でプロジェクトの財務数値を見ていきます。

1.  **[プロジェクト明細書]** を選択します。

1.  **[プロジェクト明細書]**  ページの **[プロジェクト日付]**  セクションをポイントします。  
任意の日付範囲の明細書を作成できます。

1.  **[起点]** 日付ボックスを選択し、「 **2021/2/1**」と入力します。
1. 
1.  **[今日まで]**  ボックスを選択し、本日の日付を入力します。

1. 完了したら、 **[計算]** を選択します。

    ![[プロジェクト明細書] ページの計算オプションが強調表示されているスクリーンショット。](./media/projops_invoice_4_calculate.png)

1.  **[トランザクション]** をポイントします。  
    最初にプロジェクトの請求書発行について説明します。
