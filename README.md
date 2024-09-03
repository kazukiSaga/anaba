# サービス名: Anaba  
　  
## ■サービス概要  
* 写真とコメント、スポット名（穴場の名前）と共に、自分の穴場の景色を投稿し、他のユーザーと共有できるサービスです。  　　　
* ユーザーは、都道府県、タグ、スポット名（穴場の名前）で投稿された場所を検索することができます。  　
* 登録された穴場に対して、各ユーザーはタイトル、写真とコメントの投稿、5段階評価（おすすめ度、混雑の少なさの2つの評価）を行えます。  
　  
## ■ このサービスへの思い・作りたい理由  
 コロナ禍により、人混みが避けられない観光地や旅行のハードルが高くなったことを実感しました。  
 また、コロナウイルスの終息後も、円安による外国人観光客の増加で観光地は依然として混雑しています。  
 このような状況で、人混みを避けつつ、まだ有名になっていない穴場スポットを楽しめるサイトがあれば、多くの人が安全で快適に観光を楽しめるのではないかと考えました。  
 自分自身が新しい場所を発見する喜びを多くの人と共有したいという思いから、このサービスを立ち上げたいと考えています。  
　  
## ■ユーザー層について  
* 旅行好きな人：旅行中に観光地を巡って時間が余っている人や、既に訪れた観光地以外の新しい場所を探している人が対象です。この層には、一般的な観光地とは異なる場所を検索機能で見つけられる点が魅力的だと考えました。新たな体験や発見を求めるニーズに応えられると考えています。  
* 写真愛好家：素晴らしい景色や穴場スポットを写真に収め、それを他の人々と共有したいと考える人々が対象です。この層に対しては、人混みのない撮影に適した景色の良い場所を検索機能で探せる点や、撮影した写真をコメントと共に投稿して共有できる機能がニーズに合致すると考えています。  
* 観光地での混雑を避けて景色を楽しみたい人：人混みを避けて、リラックスできる場所を探している人々が対象です。この層には、混雑を避けた景色を楽しめる場所を検索機能で見つけられる点がニーズに合っていると考えました。静かな場所でゆったりと過ごしたいというニーズを満たせると考えています。  　　
　  
## ■サービスの利用イメージ  
* ユーザーは、自分が見つけた穴場スポットを「スポット名（穴場の名前）、住所、説明、タグ」と共に登録できます。  
* 登録された場所はGoogleマップ上にピンで表示され、カーソルを合わせると穴場の名前と評価がポップアップで表示されます。  　　
* ピンをクリックすると、その穴場の詳細ページに移動し、説明や写真、コメントの一覧などの情報を閲覧できます。  　　
* 一覧表示された投稿から詳細ページへアクセスすることもでき、ユーザーはさまざまな視点からスポットの情報を得ることができます。  　　
* これにより、ユーザーは混雑を避けつつ、他のユーザーが提供する詳細な情報や評価を参考にしながら、景色を楽しむことができます。  　　
　  
## ■ユーザーの獲得について  
* XやInstagramのアカウントを作成し、投稿された写真などの情報を発信し、Anabaの普及を行い、ユーザーを獲得します。  
* 旅行、景色、観光等のコミュニティへサイトへAnabaについての情報を投稿し、ユーザーを獲得します。  
* Anabaの情報やURLを載せたチラシを作成し、許可を得た施設や店舗に張り出すことで、Anabaの普及を行いユーザーを獲得します。  
　  
## ■ サービスの差別化ポイント・推しポイント  
このサービスの最大の差別化ポイントは、まだ知られていない穴場のスポットに焦点を当てている点です。  
一般的な観光サイトは有名な観光地を中心に紹介していますが、このサービスではユーザー自身が発見した新しい場所を共有し、その情報を他のユーザーと共有することができます。  
Googleマップとの連携により、視覚的に場所を確認しやすく、直感的に利用できるインターフェースを提供します。  
また、5段階評価システム（おすすめ度、混雑の少なさの2つの評価）を採用しており、他のユーザーの体験をリアルタイムで反映した情報が得られるため、利用者にとって信頼性の高い情報を提供することができます。  
　  
## ■機能候補  
### MVPリリース時:  
* ユーザー登録機能  
* ログイン機能  　
* 写真投稿機能  　　
* コメント投稿機能  　　
* スポットの登録（スポット名、住所、説明、タグ）  
* スポットを登録したユーザーのみ、登録したスポットの編集可能（スポット名、住所、説明、タグ）　
* インクリメントサーチでの検索機能（スポット名）  
* 検索機能（タグ、都道府県）  
* おすすめ度の5段階評価機能（セレクトボックス形式）  
* 混雑の少なさの5段階評価機能（セレクトボックス形式）
# 本リリース時:  
* Googleマップ連携機能（登録されたスポットのピン表示、スポット名と評価のポップアップ表示、詳細ページへのリンク）  
　 
### ■機能の実装方針予定  
* Google Maps　API  
* インクリメントサーチ  
　  
### 画面遷移図  
Figma：https://www.figma.com/design/QnDeRMhH1xPCbQVlR3v1ks/Anaba%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=fpmVHC09WLr3n4Ha-1  
　  
### READMEに記載した機能  
- [✔️] ユーザー登録機能  
- [✔️] ログイン機能  
- [✔️] 写真投稿機能  
- [✔️] コメント投稿機能  
- [✔️] スポットの登録（スポット名、住所、説明、タグ）  
- [✔️] スポットを登録したユーザーのみ、登録したスポットの編集可能（スポット名、住所、説明、タグ）  
- [✔️] インクリメントサーチでの検索機能（スポット名）  
- [✔️] 検索機能（タグ、都道府県）  
- [✔️] おすすめ度の5段階評価機能（セレクトボックス形式）  
- [✔️] 混雑の少なさの5段階評価機能（セレクトボックス形式）  
- [✔️] Googleマップ連携機能（登録されたスポットのピン表示、スポット名と評価のポップアップ表示、詳細ページへのリンク）  
　  
### 未ログインでも閲覧または利用できるページ  
以下の項目は適切に未ログインでも閲覧または利用できる画面遷移になっているか？  
- [✔️] 検索機能（タグ、都道府県）  
- [✔️] インクリメントサーチでの検索機能（スポット名）  
- [✔️] コメント一覧閲覧機能（未ログインでも閲覧可能）  
- [✔️] コメント詳細閲覧機能（未ログインでも閲覧可能）  
- [✔️] スポット一覧閲覧機能（未ログインでも閲覧可能）  
- [✔️] スポット詳細閲覧機能（未ログインでも閲覧可能）  
- [✔️] Googleマップ上にピンで表示されたスポット閲覧機能（未ログインでも閲覧可能）  
　  
### 各画面の作り込み  
画面遷移だけでなく、必要なボタンやフォームが確認できるくらい作り米ているか？  
- [✔️] 作り込みはある程度完了している（Figmaを見て画面の作成ができる状態にある）  
　  
### ER図  
draw.io：https://drive.google.com/file/d/1COQNKC9mRp6apwWSm0Mf6W9a0WITyTIS/view?usp=sharing  