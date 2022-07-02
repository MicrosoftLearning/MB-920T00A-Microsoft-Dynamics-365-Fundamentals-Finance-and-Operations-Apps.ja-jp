---
lab:
  title: ラボ 1:財務分析コードの作成
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
ms.openlocfilehash: 9bbc1a92cb719b988ddfa6a08e1e3b2d8c69976e
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/27/2022
ms.locfileid: "137910029"
---
## <a name="lab-1---create-a-financial-dimension"></a>ラボ 1 - 財務分析コードの作成

## <a name="objectives"></a>目標

勘定科目表で勘定セグメントとして使用できる財務分析コードを作成するには、[財務分析コード] ページを使用します。 財務分析コードには、カスタム分析コードとエンティティに基づく分析コードの 2 つのタイプがあります。 カスタム分析コードは法人間で共有され、値はユーザーによって入力および管理されます。 エンティティに裏付けられた分析コードの場合、値はシステム内のどこか (顧客や店舗エンティティなど) で定義されます。 エンティティに基づく分析コードは、法人全体で共有されるものと会社固有のものがあります。

あなたの会社が使用するためのカスタムの財務分析コードを作成していただきます。

## <a name="lab-setup"></a>ラボのセットアップ

   - **推定時間**:5 分

## <a name="instructions"></a>Instructions

1. Finance and Operations の [ホーム] ページの右上で、USMF 社の作業を行っていることを確認します。

1. 必要な場合、会社を選び、メニューから **USMF** を選択します。

1. 左ナビゲーション ウィンドウで、**モジュール** > **総勘定元帳** > **勘定科目表** > **分析コード** > **財務分析コード** の順に選択します。

1. 上部メニューで、**[+ 新規]** を選択します。

1. [財務分析コード] ページで **[値の使用元]** メニューを選択し、**[カスタム分析コード]** を選択します。

1. **[分析コード名]** ボックスに「**Affliate_Revenue**」と入力します。

1. **[レポート列名]** ボックスに、「**Afflt**」と入力します。

1. トップ メニューで **[アクティブ化]** を選択します。

    ![新しいカスタム財務分析コードを表示するスクリーンショット。値の使用元、分析コード名、レポート列名、アクティブ化 メニューが強調表示されている](./media/lp2-m3-new-financial-dimension.png)

1. ダイアログ ボックスの情報を確認し、**[閉じる]** を選択します。

1. 警告通知のバナーを確認します。

    ![警告情報のバナーを表示するスクリーンショット。新しい分析コードをアクティブ化するためにメンテナンス モードが必要であることが示されている。](./media/lp2-m3-activation-warning-banner.png)

    >[!NOTE] メンテナンス モードのオン/オフは、ご使用のサンドボックスおよび実稼働環境の Lifecycle Services (LCS) から直接切り替えることができます。 ライフサイクル サービスの管理の詳細については、[https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure](https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure) を参照してください。
