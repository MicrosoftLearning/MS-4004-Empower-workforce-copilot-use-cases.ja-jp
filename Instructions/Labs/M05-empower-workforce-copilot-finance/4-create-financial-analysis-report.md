# Word の Copilot を使用して財務分析レポートを作成する
---
Word の Copilot は、財務担当者がドキュメントをより効率的に作成するのに役立ちます。 財務担当者が、コンテンツの作成、トピックの調査、自慢できるドキュメントへの既存のコンテンツの変換を行うのに役立ちます。 また、Copilot を使用してドキュメントの書き換えや編集を行うと、時間と思考を節約することもできます。

たとえば、財務アナリストが会社の業績に関するレポートを作成する必要がある場合、Word で Copilot を使用してレポートの下書きを作成できます。 Copilot に "XYZ 社の財務実績に関するレポートを作成してください" と指示すると、Copilot によって校正できる下書きが生成されます。 Copilot Chat に質問して、追加できる可能性のあるコンテンツを調査、考案、または反復することができます。

既存のドキュメントで作業している場合、Copilot はドキュメントの書き換えと編集に役立ち、時間と思考を節約できます。 この演習では、前の演習で分析および更新した Fabrikam Q1 Marketing Campaign スプレッドシートのデータに基づいて新しいレポートを作成するように Word の Copilot に指示します。 ただし、Excel スプレッドシートを使用する代わりに、すべてのスプレッドシート データを含む Word 文書を使用します。

> [!NOTE]
> Word の Copilot は、スプレッドシートに基づいてレポートを作成できます。 ただし、Word 内から Excel ファイルを直接参照することはできません。 代わりに、Excel ファイルのデータをコピーして Word 文書に貼り付ける必要があります。 データを Word 文書に保存したら、Copilot を使用し、そのデータに基づいてレポートを生成できます。 この演習で、前の演習で使用したスプレッドシートのデータをコピーし、**Fabrikam Q1 Marketing Campaign data** というタイトルの Word 文書に貼り付けました。

> [!TIP]
> Copilot で作業しているときに、何らかのエラー メッセージが返された場合は、プロンプトをもう一度送信してください。 そうすると、多くの場合、問題は修正されます。 同様に、データが適切に表示されない場合 (テーブル データが Word の表ではなく HTML コードで表示されるなど)、プロンプトを入力して、データを修正して適切に表示するように Copilot に依頼します (例: **ピボット テーブルがすべて HTML コードで表示されています。これらのテーブルを Word の表形式に変換してください**)。

### 演習

Fabrikam の財務部長であるあなたは、前の演習で Excel の Copilot を使用して、会社の Q1 マーケティング キャンペーンの効果を分析しました。 この演習では、Word の Copilot を使用して、そのデータの分析を要約したレポートを生成する予定です。 スプレッドシートはコピーされて Word 文書に貼り付けられています。これを最初の手順でダウンロードします。

1.  次のリンクを選択して、[Fabrikam Q1 マーケティング キャンペーンのデータ](https://edxinteractivepage.blob.core.windows.net/ms-4004/Fabrikam%20Q1%20marketing%20campaign%20data.docx)をダウンロードします。
2.  ダウンロードが完了したら、ファイルを OneDrive アカウントに移動し、ファイルを開いてから閉じて、最近使用した (MRU) ファイルの一覧に表示されるようにします。
3.  Microsoft Edge ブラウザーで **[Microsoft 365]** タブを開いている場合は、ここでそれを選択します。それ以外の場合は、新しいタブを開き、次の URL を入力します: **https://www.office.com**
4.  **Microsoft 365** で **Microsoft Word** を開き、白紙の文書を開きます。
5.  白紙の文書の上部に表示される **[Copilot を使って下書き]** ウィンドウに次のプロンプトを入力します。ただし、次の手順でファイルをプロンプトにリンクするまでは、**[生成]** ボタンを選択しないでください。
    
    **私は、Fabrikam の財務部長です。Q1 マーケティング キャンペーンに関するデータを提供する添付ファイルに基づいて、Q1 マーケティング キャンペーン分析レポートを作成してください。レポートには、次のセクションを含めてください: エグゼクティブ サマリ、データ分析、推奨事項**。
6.  ここで、ダウンロードした **Fabrikam Q1 marketing campaign data.docx** ファイルをプロンプトに添付する必要があります。 **[Copilot を使って下書き]** ウィンドウで、**[コンテンツを参照する]** ボタンを選択します。 表示されるドロップダウン メニューで、**Fabrikam Q1 marketing campaigns data.docx** ファイルがファイルの一覧に表示されている場合は、それを選択します。 表示されていない場合は、**[クラウドからファイルを参照]** を選択し、**[最近使用したファイル]** の一覧からファイルを選択し、**[添付]** ボタンを選択します。 ファイルが **[最近使用したファイル]** の一覧に表示されない場合は、**[ファイルを選択]** ウィンドウのナビゲーション ウィンドウの上部にある **[マイ ファイル]** を選択し、ファイルを保存したフォルダーに移動し、ファイルを選択し、**[添付]** を選択します。 プロンプトにファイルがどのように表示されるかに注目してください。
7.  **生成**を選択します。 このとき、Copilot はファイルから関連情報を抽出し、データを分析したレポートの下書きを作成します。
8.  結果を確認します。 **エグゼクティブ サマリ**セクションのデータが箇条書きで表示されている場合は、次のプロンプトを入力し、**\{表または箇条書き\}** を**表**に置き換えます。 **エグゼクティブ サマリ**セクションのデータが箇条書き形式で表示されていない場合は、次のプロンプトを入力し、**\{表または箇条書き\}** を**箇条書き**に置き換えます。
    
    **エグゼクティブ サマリ セクションの情報を \{表または箇条書き\} 形式に変換してください**。
9.  **データ分析**セクションが既に表形式の場合は、次の手順に進みます。 表形式ではない場合は、次のプロンプトを入力して、読みやすくするためにデータを表に配置します。
    
    **データ分析セクションの情報を表形式に変換してください**。
10. **データ分析**セクションのデータの表を調べます。 Copilot が表からデータの列を削除できるかどうかを確認してみましょう。 次のプロンプトを入力し、\{見出し\} を、削除する列の名前に置き換えます。
    
    **データ分析セクションのデータの表で、\{見出し\} 列を削除してください**。
11. **推奨事項**は気に入っていますが、Copilot がデータを重要度の順に表示した方がデータの価値が高まるのではないかと思っています。 次のプロンプトを入力して、Copilot にこの変更を加えてもらいます。
    
    **推奨事項セクションで、最も重要な項目から重要度の高い順に表示してください**。
12. この最新の下書きを確認すると、レポートに問題はないので、保存する準備ができました。 文書の下部にある [Copilot] ウィンドウで、**[保存]** ボタンを選択して、Copilot の下書きから Word 文書に変換します。
13. 文書を確認します。 問題がなければ、ドキュメントを破棄するか、後で参照するために OneDrive に保存することができます。
14. Microsoft Edge ブラウザーで、このタブを閉じます。