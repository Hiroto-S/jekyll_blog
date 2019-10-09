目的
----

-   領域実習の記録memoをJekyll~list内で共有したい~

手法
----

-   grad~research19f~/members/hirotoにあるconv~mdtomemoを~

自分の\~/bin/にcpする

-   記録先はgrad~research19f~/README.orgとする
-   プログラム内のグローバル変数(\$jekyll~postspath~)を自分のpathに変更する
    -   jekyll~listpostsのパス~
-   64行目の"lab/grad~research19f~"を自分のgrad~research19fのあるパスに変更する~

    > \['README.org'\].each do |blog~file~| file = File.join
    > ENV\['HOME'\], 'lab/grad~research19f~/', blog~file~
    > File.readlines(file).each do |line| m1 = line.match *\^\* (.+)
    > \<(.+) .+ * m2 = line.match *\^\* (.+)
    > \<(\[\d|-\]\*).\*(\d{2}:\d{2}\*) * img = line.match
    > *$$\[file:(.*)\/(.*)$$\]*

結果
----

-   conv~mdtomemoをターミナルで実行することで~，jekyll~listのmemoカテゴリーに記事が追加される~．

Discuss
-------

-   画像表示いる???

