## 概要
第6回課題を取り組むにあたりSpring Initializrから製作したファイルをinteliljで開くが`broken pipe`とエラーが出て解決ができない為  
ソースコードを共有。

### 動作確認
<img width="1394" alt="スクリーンショット 2024-03-11 17 10 02" src="https://github.com/yukky1325/yukihisakadai6/assets/102965212/2533560b-c911-47b6-b38e-71c14d97594a">

## 前回Pushの指摘箇所を手順に沿って改善し、再度pushしました。  
- このGitHubのリポジトリは削除（削除が怖ければprivateにしておくでもよい）
  <img width="1156" alt="スクリーンショット 2024-03-11 15 34 32" src="https://github.com/yukky1325/yukihisakadai6/assets/102965212/17c9cc8b-77b3-4c15-b053-44b5ea198701">

- /Documents ディレクトリがある階層にあるであろう .git を削除
 <img width="761" alt="スクリーンショット 2024-03-11 16 17 04" src="https://github.com/yukky1325/yukihisakadai6/assets/102965212/d507ce09-2e1c-453e-9008-6e7cb934d58e">

 ただその上の階層に.gitがあり、時間帯的に原因と思われるので削除しました。  
- /Documents/yukihisakadai6/の下、つまり src や build.gradle がある階層で git init して commitする
- 新規リポジトリをつくり git pushする
<img width="1027" alt="スクリーンショット 2024-03-11 16 30 27" src="https://github.com/yukky1325/yukihisakadai6/assets/102965212/4d0796f3-84a0-49be-ab41-0dc632f9b68d">


  
