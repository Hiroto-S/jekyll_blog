問題点1
-------

ブログのタイトル表示ページでは，綺麗に表示されるが，タイトルをクリックし次のページに移るとうまくテーマが表示されない.

### 解決策

-   mdに変換後headに数行テンプレの行が必要であったため，
    blog2jekyllに\$head2を追加した．

問題点2
-------

github.ioでテーマが表示されない

### 

問題点3
-------

画像が表示されない

### 解決策

-   assets/imgに画像を入れる

![a]({{site.baseurl}}/assets/images/omri.jpg)