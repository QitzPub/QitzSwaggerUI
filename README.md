# QitzSwaggerUI
これはなんぞ？？<br>
SwaggerUIの読み込むYamlをurl経由で指定できるようにして取り込んだ感じのツールです<br>

## 使い方

SwaggerUIを以下ページに公開していますので、そちらにSwaggerYamlのUrlエンコードした文字列をぶち込んでやります！<br>
https://qitzpub.github.io/QitzSwaggerUI/
<br>
<br>

### SwaggerのYamlのurlを取得してURLエンコード

####SwaggerYamlのGitHubのURLを取得

SwaggerYamlのURLはGitHubに配置したものなら例えば以下方法で取得できます。<br>
![画像](https://i.gyazo.com/be17f0454916f9348509ad211303b8f1.png"がぞーう")<br>
GitHubに配置したSwaggerのyamlを選択しRawのボタンを選択します。<br>
<br>
![画像](https://i.gyazo.com/7bd00ac00f1bcccf2c748d2d664bca59.png"がぞーう")<br>
Swaggerの生のテキストを取得できるURLを取得できます。<br>

####取得したURLをエンコード
以下サイトでエンコードします。<br>
https://tech-unlimited.com/urlencode.html
<br>
![画像](https://i.gyazo.com/cccc43d4fe2306eea5e47fd32132c30c.png"がぞーう")<br>
<br>

### エンコードしたSwaggerURLとQitz公開のSwaggerUIを合体させてアクセス！
<br>
https://qitzpub.github.io/QitzSwaggerUI/
<br>のurlに
yaml_url<br>
のurlパラメーターをつけてSwaggerのURLを追加します<br>
例）<br>
https://qitzpub.github.io/QitzSwaggerUI/?yaml_url=https%3A%2F%2Fraw.githubusercontent.com%2FQitzPub%2Fkarute%2Fmain%2Fdocs%2Fswagger.yaml%3Ftoken%3DAKS7RHG3Y2VGGZQTH7GCVNDBSYBA6
<br>アクセスすると・・・・！？
<br>
対象Swaggerを読み込んだSwaggerUIが表示されました！！！やったーーー！！<br>
<br>

