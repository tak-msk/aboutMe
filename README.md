#DMTC School

##DMTC School第一回
メモし忘れたー

##DMTC School第二回
DBの設計について  
  
-なぜPhotoの型がVarcharなのか？  
ファイル名。  
わざわざMB単位のファイルをDBに貯めるよりもアドレスを格納しちゃえばいい。  
    
http://example.com/.../...  
http => protocol  
https => httpでsecurityを強めたもの  
example.com => hostname  
以降 => path  
  
~account?accounts?  
複数アカウント入るから、accounts  
てかテーブル名はだいたい複数系  
  
~数制限  
varchar, charは文字数制限  
INT系はそこまで深く考えなくていい  
  
~ページ遷移について  
1, ポートフォリオサービスには何が必要か？  
  
LP(Top)  
登録ページ(SignUP)  
Edit  
Portfolio  
Mypage  
Sign out  
Sign in  
Not Found 404  
Edit Complete  
Favorite List  
PM  

2, ページ遷移を実際に書いてみよう  
moqupsの利用  
どういう情報を入れるのかをざっくりとでもいいので、書く  


~PHPのデータベースライブラリ  
・PDO(今回使う)  
・MySQLi  
・MySQL(今は非推奨だから使わないように)  

~データベースとの接続  
・必要なのは  
  ・なんてタイプのサーバで  
  ・どのサーバーの  
  ・なんて名前のデータベースに  
  ・どうやって接続するのか？  
  ・あとユーザー名とパスワード  


