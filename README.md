# っぽい

Pull Requestとかのやり方はなんとなくわかったっぽいけどデスクトップからの更新がなんかうまくいかないっぽい。
GitHubアプリ再インスコしてみるっぽい。

なんか自動サイト生成機能みたいのがあったので試してみる。
インストラクションを超テキトーに訳してみるっぽい。GitHub上でなんか編集する時に役に立つかもっぽい？

####段落(Paragraph)
>
To create a paragraph, simply create a block of text that is not separated by one or more blank lines. Blocks of text separated by one or more blank lines will be parsed as paragraphs.
If you want to create a line break, end a line with two or more spaces, then hit Return/Enter.

空行がないテキストは勝手に段落になるのです。段落内に空行を入れたい時は行末にスペースを2個以上入れてから改行するのです。

####引用(blockquotes)

>
Markdown creates blockquotes email-style by prefixing each line with the >.
This looks best if you decide to hard-wrap text and prefix each line with a > character, but 
Markdown supports just putting > before your paragraph.

引用ブロックを作るには \> を使うのです。メールのお返事を書く時みたいに全部の行の頭に \> を入れても良いのですが、段落の最初に1個だけ \> を描くだけで置くだけで段落全体が引用として扱われるのです。

はにゃーー！(通常の段落)

>
はにゃーー！(引用)


####ヘッダー(Headers)

>
Markdown supports two header formats. The wiki editor uses the “atx’-style headers. Simply prefix your header text with the number of \# characters to 
specify heading depth. For example: # Header 1, ## Header 2 and ### Header 3 will be progressively smaller headers.
You may end your headers with any number of hashes.

