# Excel の Microsoft 365 Copilot を使用して市場動向スプレッドシートを分析する
---
マーケティングの専門家は、Microsoft 365 Copilot in Excel を使用してデータを分析し、ビジネスに関する洞察を得ることができます。 Microsoft 365 Copilot in Excel は、マーケティングの専門家が簡単にデータの作成、編集、理解、視覚化を行うのに役立つ強力なツールです。

たとえば、Microsoft 365 Copilot in Excel を使用すると、四半期ごとのビジネス結果の分析、重要な傾向の要約、テーブルへの色分けの適用、モデルとシナリオの作成、フィルターと並べ替え、グラフの追加をマウスのクリックで行うことができます。 Copilot の AI を活用した機能は、反復的なタスクを自動化し、情報に基づいた意思決定を行うのに役立つ貴重な分析情報を提供することで、マーケティングの専門家が時間と労力を節約するのに役立ちます。 Microsoft 365 Copilot in Excel を使用することで、最も重要なことであるビジネスのゴールと目標に集中することができます。

Microsoft 365 Copilot in Excel は、マーケティングの専門家のツールボックス内の貴重なツールです。 これには、以下のような豊富な利点があります。

 -  **簡単なデータの強調表示、フィルター処理、並べ替え**: Microsoft 365 Copilot in Excel は、データを強調表示、フィルター処理、並べ替えることで、マーケティングの専門家がデータをすばやく識別して整理するのに役立ちます。 たとえば、マーケティングの専門家は Copilot を使用して、顧客の統計情報などの大規模なデータ セットから無関係なデータを除外し、マーケティング目標に最も関連するデータに焦点を当てることができます。
 -  **複雑な計算の数式列の提案の生成**: Microsoft 365 Copilot in Excel は、マーケティングの専門家が、マーケティング キャンペーンの投資収益率 (ROI) の計算などの複雑な計算のために数式列の提案を生成するのに役立ちます。 たとえば、マーケティングの専門家は Copilot を使用して、キャンペーンによって生まれた収益をキャンペーンのコストで割ることで、メール マーケティング キャンペーンの ROI を計算できます。
 -  **データの分析、理解、視覚化の支援**: Microsoft 365 Copilot in Excel は、マーケティングの専門家が AI の力を利用して、データを分析、理解、視覚化するのに役立ちます。 たとえば、マーケティングの専門家は、Copilot を使用して売上データの傾向を特定し、これらの知見を使用してマーケティング戦略に関する情報に基づいた意思決定を行うことができます。

Microsoft 365 Copilot in Excel を使用する場合は、ワークシート内にデータを含む Excel の表が必要です。 以下の手順に従うことで、セルの範囲をすばやく Excel の表に変換できます。

1.  データ内のセルまたは範囲を選択します。
2.  **[ホーム]** &gt; **[テーブルとして書式設定]** を選択します。
3.  範囲の最初の行をヘッダー行にしたい場合は、**[テーブルとして書式設定]** ダイアログ ボックスで、**[ヘッダー有りのテーブル]** の横にあるチェックボックスを選択します。
4.  **[OK]** を選択します。

この演習では、Microsoft 365 Copilot in Excel を使用して、Excel テーブルが既に定義されている市場傾向のスプレッドシートを分析します。 この演習では、Copilot の多くの事前構築済み関数とプロンプトを確認します。<br>

### 演習

Contoso, Ltd. の一部門である Contoso Beverage のマーケティング ディレクターであるあなたは、2023 年の Contoso の Chai Tea 製品に関する月ごとのアクティビティを表す市場傾向のスプレッドシートを受け取りました。 あなたは、Microsoft 365 Copilot in Excel の機能を使用してレポートを分析し、2023 年の月ごとの市場傾向の詳細な分析を提供したいと考えています。 この演習では、Microsoft 365 Copilot in Excel が提供するさまざまな定義済みプロンプトと機能を確認します。

以下の手順を実行して、Microsoft 365 Copilot in Excel を使用して市場傾向のスプレッドシートを分析します。

1.  前の演習で [Contoso Chai Tea market trends 2023](https://go.microsoft.com/fwlink/?linkid=2268822) スプレッドシートをダウンロードした場合は、次の手順に進みます。 それ以外の場合は、リンクを選択してファイルをダウンロードし、それを OneDrive アカウントに移動した後、ファイルを開いてから閉じることで、最近使用した (MRU) ファイル リストにそのファイルを入れます。
2.  Microsoft Edge ブラウザーで Microsoft 365 タブを開いている場合は、ここでそれを選択します。それ以外の場合は、新しいタブを開き、次の URL を入力します: **https://www.office.com**
3.  **[Microsoft 365]** ホーム ページの左側のナビゲーション ウィンドウで **[Excel]** アイコンを選択します。
4.  **Excel** の **[ファイル]** ページで、ファイル リストから **Contoso Chai Tea market trends 2023.xlsx** を選択します。
5.  リボンの右側にある **[Copilot]** オプションを選択します。
6.  表示される **[Copilot]** ペインでは、利用可能ないくつかの定義済みプロンプトから選択を行えます。 **[データ分析情報の表示]** ボタンを選択します。
    
  ![[Copilot] ペインの定義済みプロンプトを示すスクリーンショット。](../media/copilot-excel-prompts-fb96f587.png)
    
7.  生成されたピボット グラフに注目してください。 私たちがこの演習をテストしたときには、Copilot は毎回**日付別のソーシャル メディア エンゲージメント (ビュー)** の線グラフを作成しました。 Copilot はあなたのためにどのような種類のグラフを作成したでしょうか? Copilot が自動的に作成したグラフの下にある **[+ 新しいシートに追加]** ボタンを選択します。
8.  **[シート 2]** を選択します。 Copilot によって作成された新しいデータ シートを確認します。 Microsoft 365 Copilot は、このグラフの基礎となったスプレッドシートのデータのグラフと列の両方を含めました。 グラフの上にカーソルを置き、Copilot が生成したグラフの種類を示すウィンドウが表示されることに注目してください。
9.  [Copilot] ペインでは、定義済みプロンプトのリストが表示されなくなったことに注目してください。 この状況は、Copilot がまだピボットテーブルに対応していないために発生します (この問題を示すメッセージに注目してください)。 **[シート 1]** を選択すると、Excel テーブルに戻ります。 定義済みプロンプトが表示されることに注目してください。
10. プロンプト フィールドの上に表示される定義済みプロンプトで、**[数式列の提案の表示]** ボタンを選択します。
11. Copilot が提供する提案に注目してください。 次の図は、私たちのテスト中に Copilot が提供した提案を示しています。
    
   ![Artisanal Chai の売上に関する Copilot の提案を示すスクリーンショット。](../media/copilot-excel-suggestion-artisanal-63acef26.png)
    
12. 受け取った提案で、**[数式の説明]** ドロップダウン矢印を選択します。 計算について記述する Copilot の説明を確認します。 **[+ 列の挿入]** ボタンを選択して、この列を Excel テーブルに挿入します。
13. Copilot が **[シート 1]** の Excel テーブルの末尾にこのデータ列を追加したことに注目してください。 あなたはこの機能に興味をそそられたので、他にどのような数式の提案が提供されるのかを確認したいと考えます。 **[数式列の提案の表示]** ボタンをもう一度選択します。 提案を確認してください。 **[+ 列の挿入]** ボタンを選択して、この提案列を Excel テーブルに挿入します。
14. プロンプト フィールドの上に表示される定義済みプロンプトで、**[データの強調表示、フィルター処理、並べ替えを行うには?]** ボタンを選択します。
15. 実行できるアクションのリストに注目してください。
16. 今回表示される定義済みプロンプトの改訂されたリストを確認します。 次の図は、私たちがテストで受け取ったプロンプトの例を示しています。
    
   ![並べ替え、太字化、特定の項目の表示など、さまざまな定義済みのデータ プロンプトを示すスクリーンショット。](../media/copilot-excel-data-prompts-a5b3d933.png)
    
17. この演習の目的は、Copilot が実行できるさまざまな種類の定義済みアクションの感触をつかむことです。 そのため、さまざまなプロンプトを選択して、何が起こるかを確認します。 次に例を示します。
     -  **[並べ替え]** プロンプトが表示されたら、今度はそれを選択します。 Copilot が自動でデータを並べ替えたことに注目してください。
     -  **[太字]** プロンプトが表示されたら、今度はそれを選択します。 Copilot が自身が言及した列の項目を太字にし、他の項目は太字にしていないことに注目してください。
     -  **[強調表示]** プロンプトが表示されたら、今度はそれを選択します。 Copilot の応答と、テーブル内のデータがどのように強調表示されているかに注目してください。
18. この時点で、あなたは Copilot が表示する定義済みプロンプトに関心がなくなります。 そのため、あなたは新しいプロンプトのセットを表示したいと考えます。 プロンプト フィールドの上に表示される **[更新]** ボタンを選択します。
    
   ![[プロンプトの更新] ボタンを示すスクリーンショット。](../media/copilot-excel-refresh-prompt-icon-3e82c059.png)
    
    
19. 表示されるプロンプトの新しいセットを確認します。 **[更新]** ボタンを何度か選択して、Copilot が提供するさまざまな種類のプロンプトを確認します。
20. 他のプロンプトを自由に選択して、Copilot が何を行うかを確認してください。 完了したら、Microsoft Edge ブラウザー タブを閉じます。
