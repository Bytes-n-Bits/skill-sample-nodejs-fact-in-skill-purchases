# プレミアムトリビア - スキル内課金を使ったスキルの作成
<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

[![音声ユーザーインターフェイス](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/1-locked._TTH_.png)](./voice-user-interface.md)[![Lambda 関数](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/2-locked._TTH_.png)](./lambda-function.md)[![VUI とコードを接続する](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/3-on._TTH_.png)](./connect-vui-to-code.md)[![テスト](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/4-off._TTH_.png)](./testing.md)[![カスタマイズ](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/5-off._TTH_.png)](./customization.md)[![スキルの公開](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/6-off._TTH_.png)](./publication.md)

## 音声ユーザーインターフェース (VUI) とコードをつなげる

このガイドの [1ページ目](./1-voice-user-interface.md) で、インテントとサンプル発話の設定を行い、音声ユーザーインターフェースを作成しました。 [2ページ目](./2-lambda-function.md) では、Lambda 関数を作成しこのスキルに必要な全てのロジックを実装しました。 このページでこれら２つの部分をつなげます。

1.  [Amazon開発者ポータル](https://developer.amazon.com/edw/home.html#/skills/list) に戻り、一覧からあなたのスキルを選択します。

2.  **ビルド** タブを選択し、左側のナビゲーションパネルにある　**エンドポイント**　を選択します。

3.  サービスのエンドポイントの種類として **AWS LambdaのARN** を選択します。バックエンドのコードは任意のサービスに設置することが可能ですが、単純化とコスト削減のため、ここでは AWS Lambda を利用しています。 ウェブサービスとしてカスタムスキルをホスティングする方法については [こちら](https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/developing-an-alexa-skill-as-a-web-service) を参照してください。 AWS の無料利用枠を利用することで、毎月100万回の Lambda 関数の起動、320万秒のコンピューティング時間が無料で使えます。 無料利用枠については [こちら](https://aws.amazon.com/jp/free/) を参照してください。 さらにアマゾンではただいま、Alexaスキルの開発者向けに　[Alexa AWSプロモーションクレジット](https://developer.amazon.com/ja/alexa-skills-kit/alexa-aws-credits?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-3&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-3_Convert_WW_beginnersdevs&sc_segment=beginnersdevs) をご紹介しています。是非ご活用ください。

4.  前のセクションの最後のステップでコピーした Lambda関数 の **ARN (Amazon Reource Name)** を **デフォルトの地域** のテキストボックスに貼り付けます。

5.  画面上部にある **エンドポイントを保存** をクリックしてください。

6. **"次" ボタンをクリックして、スキル内商品の作成に進みましょう。**

[![次](./next.png)](./create-isp.md)
