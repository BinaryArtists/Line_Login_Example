# Line_Login_Example
<img src='http://arock.blob.core.windows.net/blogdata201702/14-215656-e2740e6c-82bb-489b-9792-a271086e7e4e.png' />
<div class="panel-body">
背景知識:
  請先參考底下這篇文章，建立您的LINE Login服務channel，取得Client_id, Client_secret
  https://studyhost.blogspot.com/2017/12/clinebot17-line-login-v21.html
  接著即可下載clone此範例使用
  
說明: 
<ol>
<li>使用此範例Source code時，請先更換程式碼中《你的Client_id》<br/> (位於default.aspx) </li>
<li>並且調整你申請好的LineLogin設定的callback url <br/> (測試階段應為http://localhost:17615/Callback.aspx) </li>
<li>同時Callback.aspx.cs中的client_id與client_secret必須改為你申請LINE Login後取得的正確資料</li>
<li>相關說明請參考 : http://studyhost.blogspot.tw/2016/12/linebot7-line-loginoauth-sso.html </li>
</ol>
使用: 
<ol>
<li>請點選《使用Line登入》，將會取得該登入用戶的access_token</li>
<li>接著按下《取得用戶資訊》，可透過access_token取得用戶資訊，即表示你取得正確的Token，完成SSO。</li>
</ol>
</div>
