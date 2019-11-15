# 00.データ構造から始めるTableauビジュアルアナリティクス

### はじめに

このGitbookは、データ分析の初学者を対象に、**「データ構造」を理解した上で、Tableauを使ってデータを可視化し、データを理解する方法**を説明します。本Gitbookを読み終わったときには、履歴データ、マスタデータを扱い、**「データ構造」**を理解した上で、基本的なデータの可視化ができるようになります。

なぜ**「データ構造」**に焦点を当てるのかというと、Tableauで可視化するもととなる「**データの構造」**を理解していなければ、そもそも正しくデータを可視化することはできません。加え、正しく集計されていないデータを可視化し、データからインサイトを得ることは無意味です。また、TableauはUIが非常に優れているため、ドラック&ドロップでデータを可視化できるため、「**データの構造」**そのものを意識する必要がありません\(個人的な解釈\)。

そのため、Tableauで作ったグラフのもととなる**「データの構造」**が、どのようになってるのかを説明できることが、Tableauでビジュアルアナリティクスを行う上では、必要不可欠です。また、**「データの構造」**を理解することで、Tableau以外のBIツールも、ツールの使い方さえ覚えてしまえば、容易に利用できるようになると思われます。

したがって、このGitbookでは、ただ単純にTableauを使う方法を説明するのではなく、**「データの構造」を理解した上で、Tableauを使ってデータを可視化する方法**に焦点をあて、説明していきます。**「データの構造」**を理解する上で、データベースの概念や設計、SQL自体を学ぶことは重要ですが、データ分析の初学者を対象にしているため、その点はは深く扱いません。

### 参考文献

* 小野,清水,前田,三好,山口 \(2017\)「Tableauデータ分析 ~入門から実践まで~」秀和システム
* 小野,黒木,長野,下山,高木\(2018\)「Tableauデータ分析 ~実践から活用まで~」秀和システム
* 松島 七衣\(2019\)「Tableauによる最強・最速のデータ可視化テクニック ～データ加工からダッシュボード作成まで～」翔泳社
* 岩橋,今西,増田\(2019\)「Tableauで始めるデータサイエンス」秀和システム

### 免責事項

筆者が投稿した内容を読者が実行した結果については、第3者によってコードが改竄されていた場合であっても、筆者は**一切の責任を負いません**。また、理解を促すことも第一に考えることによって、正確な定義や表現に関する正確性を犠牲する場合があります。

