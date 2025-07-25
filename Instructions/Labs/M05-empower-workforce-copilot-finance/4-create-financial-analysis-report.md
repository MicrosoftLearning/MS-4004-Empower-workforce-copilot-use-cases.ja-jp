# Word の Microsoft 365 Copilot を使用して財務分析レポートを作成する
---
Microsoft 365 Copilot in Word は、財務担当者がドキュメントをより効率的に作成するのに役立ちます。 財務担当者が、コンテンツの作成、トピックの調査、自慢できるドキュメントへの既存のコンテンツの変換を行うのに役立ちます。 また、Copilot を使用してドキュメントの書き換えや編集を行うと、時間と思考を節約することもできます。

たとえば、財務アナリストが会社の業績に関するレポートを作成する必要がある場合、Word で Copilot を使用してレポートの下書きを作成できます。 Copilot に "XYZ 社の財務実績に関するレポートを作成してください" と指示すると、下書きが生成されます。これを元に手直しすることができます。 Copilot Chat に質問して、追加できる可能性のあるコンテンツを調査、考案、または反復することができます。

既存のドキュメントで作業している場合、Copilot はドキュメントの書き換えと編集に役立ち、時間と思考を節約できます。 この演習では、Word 文書にコピーされた Fabrikam Q1 Marketing Campaign スプレッドシートのデータに基づいて新しいレポートを作成するように Copilot in Word に指示します。

### 演習

Fabrikam の財務部長であるあなたは、前の演習で Excel の Copilot を使用して、会社の Q1 マーケティング キャンペーンの効果を分析しました。 この演習では、Word の Copilot を使用して、そのデータの分析を要約したレポートを生成する予定です。 スプレッドシートはコピーされて Word 文書に貼り付けられています。これを最初の手順でダウンロードします。

1. 次のリンクを選択して、[Fabrikam Q1 マーケティング キャンペーンのデータ](https://go.microsoft.com/fwlink/?linkid=2268926)をダウンロードします。
1. ダウンロードが完了したら、ファイルを **Microsoft - OneDrive** フォルダーに移動し、ファイルを開いてから閉じて、最近使用した (MRU) ファイルの一覧に表示されるようにします。
1. Microsoft Edge ブラウザーで **[Microsoft 365]** タブを開いている場合は、ここでそれを選択します。それ以外の場合は、新しいタブを開き、次の URL を入力します: [**https://www.office.com**](https://www.office.com)
1. **Microsoft 365** で **Microsoft Word** を開き、白紙の文書を開きます。
1. 白紙の文書の上部に表示される **[Copilot]** プロンプト フィールドに次のプロンプトを入力します。ただし、次の手順でファイルをプロンプトにリンクするまでは、**[生成]** ボタンを選択しないでください。**私は、Fabrikam の財務部長です。Q1 マーケティング キャンペーンに関するデータを提供する添付ファイルに基づいて、Q1 マーケティング キャンペーン分析レポートを作成してください。レポートには、次のセクションを含めてください: エグゼクティブ サマリ、データ分析、推奨事項**。
1. ここで、ダウンロードした **Fabrikam Q1 marketing campaign data.docx** ファイルをプロンプトに添付する必要があります。 **[Copilot]** プロンプト フィールドで、**[+ コンテンツの追加]** ボタンを選択します。 表示されるドロップダウン メニューで **[ファイル]** タブを選択し、MRU ファイルの一覧で **Fabrikam Q1 marketing campaigns data.docx** ファイルを選択します。 プロンプトにファイルがどのように表示されるかに注目してください。
1. プロンプト フィールドで **[生成]** アイコンを選択します。 このとき、Copilot はファイルから関連情報を抽出し、データを分析したレポートの下書きを作成します。 レポートの最後に表示される Copilot ウィンドウに注目してください。 下書き 1/1 の作業中と表示されます。 下書きモードで作業しているため、Copilot ウィンドウは使用していません。 Copilot ウィンドウは、実際の Word 文書で作業しているときに使用されます。 ただし、この場合は Word で Copilot の下書きを編集しているため、下書きの最後に表示される Copilot ウィンドウを使用する必要があります。 この最初の下書きの結果を確認します。 
1. この演習では、下書きの冒頭にある「**概要**」セクションの書式を Copilot で再設定します。 このテストでは、Copilot により、通常は箇条書き、表、または段落形式で概要が表示されることがわかっています。 データが箇条書きで表示されている場合は、Copilot に表形式に変更してもらいます。 表形式または段落形式の場合は、Copilot に箇条書きに変更してもらいます。 入力すべきプロンプトは次のとおりです。**「概要」セクションの情報を {表または箇条書き} 形式に変換してください。** 
    - 箇条書きに「概要」がある場合は、次のプロンプトを入力し、**{表または箇条書き}** を**表**に置き換えます。 
    - **[概要]** データが表または段落形式である場合は、次のプロンプトを入力し、**{表または箇条書き}** を**箇条書き**に置き換えます。**「概要」セクションの情報を {表または箇条書き} 形式に変換してください。**
1. このテストでは、Copilot によって「概要」は適切に更新されましたが、文書の残りの部分が表示されなかったり、見出しだけが表示されたりすることがありました。 このような状況になった場合は、Copilot ウィンドウの戻る矢印を選択して下書き 1 に戻り、次のプロンプトを入力します。「概要」セクションの情報を {表または箇条書き} 形式に変換してください。 残りのすべてのセクションを完全に表示してください。**
1. このテストでは、Copilot に「**データ分析**」セクションに複数のキャンペーン メトリックを作成してもらいました。 これらのメトリックが既に表形式になっている場合は、次の手順に進んでください。 それ以外の場合は、次のプロンプトを入力して、すべてのメトリックを表に配置し、読みやすくします。**データ分析セクションの各メトリックに関する情報を表形式に変換してください。**
1. **推奨事項**は気に入っていますが、Copilot がデータを重要度の順に表示した方がデータの価値が高まるのではないかと思っています。 次のプロンプトを入力して、Copilot にこの変更を加えてもらいます。**推奨事項セクションで、最も重要な項目から重要度の高い順に表示してください**。
1. この最新の下書きを確認すると、レポートに問題はないので、保存する準備ができました。 文書の下部にある [Copilot] ウィンドウで、**[保存]** ボタンを選択して、Copilot の下書きから Word 文書に変換します。
1. 文書を確認します。 問題がなければ、ドキュメントを破棄するか、後で参照するために OneDrive に保存することができます。
1. Microsoft Edge ブラウザーで、このタブを閉じます。
