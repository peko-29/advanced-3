# advanced-3チーム

春木が担当したコード：advanced-3/recipe/template/index.html
1画面目のフロントエンドを担当

担当した言語：JavaScript jquery HTML CSS
バックエンド言語：Python django
開発期間：約３週間

工夫した点：画面遷移を減らすためにモーダルウインドウを使い、ユーザーがタップするだけの仕様に。
高級感とシンプルなデザインを目指し、CSSで工夫した。
検索バーに、現在選択している材料を表示し、何も選択していない場合は検索ボタンを押せない仕様に。

1.チーム名：mbコーダーズです。チームメンバーは松本、こやま、佐々木、春木です。
宜しくお願いします。

2. 今回私たちは大学生向けに「簡単なレシピのみを閲覧できるレシピアプリ」を作りました。動機は、既存のレシピサイトは料理が好きな人向けの物が多く、つくるのが簡単なレシピを探すことが難しいと感じていたことです。自炊する学生の中には、「料理をするのが特別好きなわけじゃないけど、金銭面か健康を意識してやっている」という人も多いと考えました。そういった学生にとって、毎日同じメニューを食べることも、毎日違うメニューを考えることも大きなストレスになると思います。なので、そのような人に向けて、限られた工程数のレシピのみを検索できるレシピアプリを作ろうと決めました。それでは、機能の紹介に入ります。

3. まずは材料検索画面で食材を選択します。例えば卵を選択すると、上の部分で選択している材料を確認することができ、選択を外すと、上の部分でも外れるようになっています。そして、検索を押す（result.htmlに遷移）と、卵を使ったメニューが表示されます。ここで、このアプリのコアである機能を紹介します。今は乱雑にメニューが表示されていますが、上にあるボタンを押すと、ソートする仕様になっています。例えば、タンパク質を押すとタンパク質を多く含んだ順になり、カロリーを押すとカロリーが低い順になるようになっています。これが私たちのコアな機能になっています。(index.htmlに戻る)そして、この材料検索はand検索になっており、先程の卵に加え、ベーコンを選択した状態で検索を押すと、卵とベーコンを使ったメニューを検索できるような仕様になっています。そして、メニューの名前を押すとメニューの詳細ページに遷移(deital.htmlに遷移)し、作り方や材料・金額などの詳細が見られる使用になっています。そして、検索結果に戻るを押すと、材料検索画面に戻って、材料を選択するという使用になっています。次は今紹介した機能の中で工夫した点について紹介していきます。

4. 工夫した点は3点あります。1点目に、掲載するレシピを工程数が5工程以下のものにあらかじめ絞りました。２点目に、自炊する学生は金銭面や健康に気を使っている場合が多いと想定し、コストやカロリーなどでソートする機能を実装しました。３点目に、手軽に使えるデザインを徹底しました。具体的には、ログイン機能を実装せず、画面遷移も2回と最小限に抑えました。また、ユーザーには入力などの操作はさせず、スクロールとタップのみなどユーザーの負担を最大限に抑えた仕様にしました。

5. 今回のチーム開発で苦労した点は、2つあります。 １つ目は、フロントエンドとバックエンドの連携です。当初vueを使ってフロントエンドを実装するつもりだったのですが、データの渡し方でフロントとバックでうまく連携が取れておらず、仕様を変更するなど実装に苦労しました。また、vueに関しても使ってみたいという理由で選んだものの、実装したいことから逆算してしっかりと技術選定することが必要だったと思います。 ２つ目は、コミュニケーションです。チームメンバー同士での話し合いではもちろんのこと、技術メンター等に相談する際も、自分たち自身、何に困っているのか、どういうことを実装したいのかをうまく言語化することができず、個人開発では経験することのなかった苦労をしました。

今回チーム開発で学んだ反省点を、今後の現場で活かしていこうと思います。
ありがとうございました。 
