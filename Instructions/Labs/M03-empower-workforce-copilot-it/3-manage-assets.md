
# Microsoft 365 Copilot in Excel を使用して IT 資産を管理する
---
IT マネージャーは、組織内のハードウェア、ソフトウェア ライセンス、その他の資産の大きなインベントリを管理する責任があります。 各資産を定期的に追跡、更新、報告して、IT インフラストラクチャの運用と準拠が維持されていることを確認する必要があります。 マネージャーは、リソースの割り当てを改善するための資産データの分析、ギャップの特定、データ主導の決定を行うタスクを担当します。

Microsoft 365 Copilot in Excel は、マネージャーがデータ分析を効率化し、分析情報を生成し、反復的なタスクを自動化し、プロセスの効率を高め、エラーが発生しにくくするのを助ける人気のあるツールです。 この演習でのあなたの役割は、Copilot in Excel を使って資産の管理とレポート作成を支援することを計画している IT マネージャーです。

### 演習

Contoso Ltd. の IT マネージャーであるあなたは、ノート PC、プリンター、サーバー、ルーター、スイッチといった会社のハードウェア資産の管理など、会社の重要な IT インフラストラクチャを監視しています。 これらの資産は従業員の高生産性に不可欠であり、可用性、パフォーマンス、セキュリティを維持することが重要です。 あなたの主なタスクの 1 つは、保証情報、修復履歴、現在の状態など、これらの資産のライフサイクルを追跡して管理することです。

ただし、現在、このプロセスは人手で処理されており、時間がかかり、エラーがよく発生します。 購入日、保証の有効期限、修理履歴、部門の割り当てなどの資産情報の追跡には、さまざまなスプレッドシートを使っています。 最善を尽くしてはいますが、すべてのデータの効果的な監視はますます困難になっています。 重要な保証の有効期限を見落としがちで、予定外の修理コストが発生することになります。手作業で資産の動向を分析していたのでは、迅速に意思決定する余地はほとんどありません。

もっと効率的で正確なアプローチが必要であることを認識したあなたは、Copilot in Excel を使って次の処理を行うことを計画します。

会社の資産の一覧を含むファイルをすばやく分析して、IT 資産とその保証に関連する重要な傾向と問題を明らかにします。

分析情報に富んだグラフとレポートを自動的に生成して資産データを視覚化し、すぐに注意が必要な保証パターンを特定します。

Copilot in Excel を使ってこれらのタスクを行うには、次の手順のようにします。

1. 次のリンクを選んで、Contoso の資産管理スプレッドシートをダウンロードします: [Contoso 資産データ](https://go.microsoft.com/fwlink/?linkid=2320505)
1. ダウンロードが完了したら、**エクスプローラー**を開き、**ダウンロード** フォルダーから **Microsoft - OneDrive** フォルダーにファイルをコピーします。
1. この演習では、Excel の MRU ファイルの一覧からドキュメントにアクセスします。 ファイルが MRU 一覧に表示されるようにするには、ドキュメントを開いて閉じます。 
1. Edge ブラウザーを開き (必要な場合)、次の URL を入力して **Microsoft 365** ホーム ページに移動します: **https://www.office.com**  
1. **[Microsoft 365]** ホーム ページの左側のナビゲーション ウィンドウで **[Excel]** アイコンを選択します。 アイコンが表示されない場合は、ナビゲーション ウィンドウで **[アプリ]** を選んで、**[アプリ]** ページから **[Excel]** を選びます。
1. **Excel** の MRU 一覧で、すべてのファイルの一覧まで下にスクロールします。 **[すべて]** タブは既定で表示されます。 **Contoso 資産データ** ファイルを選びます。
1. **Excel** でスプレッドシートを開き、リボンの右側にある **[Copilot]** オプションを選びます (リボンが表示されていない場合は、**[ホーム]** タブをポイントします)。 これにより、**[Copilot]** ペインが開きます。 
1. まず、保証期限が過ぎている資産、または今後 30 日、60 日、90 日以内に期限切れになる資産を Copilot に特定させます。 その際、Copilot に、期限が切れた保証は赤、30 日以内 (0 から 30 日) に期限が切れる保証は黄、60 日以内 (31 から 60 日) に期限が切れる保証は灰色、90 日以内 (61 から 90 日) に期限が切れる保証は緑で強調表示させます。 このタスクを完遂するため、Copilot は、この方法で資産を強調表示する条件付き書式ルールを作成する必要があります。 これらのルールが定義されたら、Copilot にそれを適用するよう指示できます。 <br><br>Copilot にこれらの条件付き書式ルールを作成させるには、Copilot ペインの下部にあるプロンプト フィールドに次のプロンプトを入力します。**"保証の有効期限" 列に適用する次の 4 つの条件付き書式ルールを作成します。その日付が今日の日付より前の場合は、赤で強調表示します。その日付が今後 30 日以内に期限切れになる場合は、黄で強調表示します。 その日付が現在から 31 日から 60 日で期限切れになる場合は、灰色で強調表示します。その日付が現在から 61 日から 90 日で期限切れになる場合は、緑で強調表示します**。
1. Copilot が作成した各条件付き書式ルールを確認します。 60 日のルールには特に注意します。 これらの資産を灰色で強調するよう Copilot に指示しましたが、テストでは、通常、Copilot が塗りつぶしの色として白を割り当てることがわかりました。 そうなった場合は、次のプロンプトを入力します。**作成された 3 番目のルールでは、塗りつぶしの色として白が割り当てられました。代わりに灰色を割り当ててください**。 Copilot がこのプロンプトに応答したら、塗りつぶしの色が灰色 (または薄い灰色) になっていることを確認します。
1. ルールが正しい場合は、条件付きルールの後に表示される **[適用]** ボタンを選びます。 ルールが正しく適用されていることを確認します。
1. 次に、Copilot in Excel がどのようにこのスプレッドシートのデータを分析し、データ要求を表すさまざまなグラフィックスを作成できるか見てみましょう。 まず、次のプロンプトを入力します。**部門別のアクティブなノート PC の数を示す棒グラフを作成します**。
1. 棒グラフを確認します。 次に、Copilot にこの同じデータに基づいて円グラフを作成させてみましょう。 次のプロンプトを入力します。**部門別のアクティブなノート PC の数を示す円グラフを作成します**。
1. Copilot ペインに表示される円グラフに凡例が含まれていないことに注意してください。 ただし、円グラフの下に表示される **[+ 新しいシートに追加]** ボタンを選びます。 今度は、Copilot によって円グラフが **Sheet2** に追加され、円グラフの下に部門別のアクティブなノート PC の一覧と凡例が表示されます。 
1. **Sheet2** で円グラフを選びます。 これにより、このグラフの作成に使われたピボット テーブルの詳細ペインが開きます。 
1. **Sheet1** を選びます。 Copilot にスプレッドシートのデータの分析を要求するには、実際のスプレッドシートでそれを行う必要があります。 Sheet2 にいたままで、Sheet1 のデータに基づくプロンプトを送信すると、Copilot がエラー メッセージを表示することがあります。 そうでない場合は、現在のシートのピボット テーブルの限られたデータでプロンプト要求を完了する方法の説明が示されます。 どちらの場合も、先に進む前に、スプレッドシートのデータを含むシートを選ぶ必要があります。 
1. **Sheet1** で、ステップ 11 から 14 を繰り返します。ただし、今回は次の 2 つのプロンプトを使います (円グラフは Sheet3 に追加されます)。
   - **保証期限が切れているアクティブなノート PC の部門別の数を示す棒グラフを作成します**。 
      > [!NOTE]
      > テストでは、Copilot がこのグラフを作成できない場合があります。 要求がそうなる場合は、プロンプトを次のように変更します。**保証期限の日付が今日の日付より前であるアクティブなノート PC の部門別の数を示す棒グラフを作成します**。 この方法でプロンプトを書き直す必要がある場合、それは単に Copilot が要求を理解するためにもう少し説明が必要であることを示しています。
   - **保証期限が切れているアクティブなノート PC の部門別の数を示す円グラフを作成します**。
1. **Sheet1** を選びます。
1. **Sheet1** で、Copilot in Excel がどのようにスプレッドシートのデータに基づいてレポートを生成できるか見てみましょう。 次のプロンプトを送信します。**保証が今後 90 日以内に切れるアクティブなノート PC の部門別の数を示すレポートを作成します**。
1. Copilot ペインで生成されるレポートが、ペインで利用できる限られたスペースでは理解し難いことに注意してください。 レポート全体を見るには、レポート データの下に表示される **[+ 新しいシートに追加]** ボタンを選びます。 そうすると、Copilot は **Sheet4** にレポートを追加します。 Copilot in Excel が提供する詳細レベルに注意して、レポートを確認します。 
