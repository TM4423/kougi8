1. 受講番号:18 
1. 氏名: 三浦寿也
1. 課題番号: 18 
1. Github_URL: https://github.com/TM4423/kougi8
1. レビュー会参加: あり
1. API_KEY（任意）:
# ★何ができるか
- 内容は、前回と同じですが、さくらへアップロードしました。
  
# ★頑張ったこと・こだわった点
- 今回は3つの取り組みをしました
  1. sakuraアップロード。
  2. awkプログラムを使ってエラーを見つけ出す方法を研究
  3. gitコマンドでissueを入力する方法を研究

sakuraは、以前使っていたものがあり、そのごみが残ってしまったようで、SSL接続がうまくいかず、そこで詰まっています。.htaccess周りかな、と健闘をつけていますが、ルート証明書をうまくインストールできないことと、403エラーが消えないことが課題です。時間切れで、ひとまず提出しました。


これまでエラーを、どんな些細なものでも、macOSとiOSのメモに残すようにしてきました。簡単な打ち間違えが圧倒的に多い、と感じましたので、awkプログラムで、単語の出現回数を数えるソフトを書くことを考えています。今のところ
```
{
  gsub(/:/," :")
  gsub(/,/," , ")
  gsub(/</," <")
  gsub(/>/,"> ")
  gsub(/=/," = ")
  for (i = 1; i<=NF; i++)
    count[$i]++
}
END {
for (w in count)
  print(count[w], w)
}
```
この内容しか書けていません。

gitのissueは、表記方法が面倒で、（ダークテーマのせいか）画面もとてもみにくく、とても使いづらいと思いました。展開も綺麗ではないし、コードと平文の違いもわかりにくく、好きになれません。
ひとまず、
前から気になっていた「シェル・ワンライナー160本ノック」9784297122676 を、偶然、すわちゃんも勧めてくれたので、購入したところ、おすすめ本として記載されていた「エンジニアのためのGit教科書」9784798143668 も購入し、読み始めています。

# ★疑問・質問/次回チャレンジしたいこと
森田先生の補講で、Git関連のコマンドを紹介してもらえましたが、一瞬で過ぎ去ったため聞き取れず、なんとか記憶をたどりながら、コマンドを探しています。issue周りのコマンドだったと思います。

