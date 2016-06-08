# Hello Git
## 2016.6.8
Thanks, umisama (Ibaraki).

## umisamaがされてた作業
umisamaがbeer コミットを消した時
git reset --hard sXXXXXXX

## Pull requestを送るまで
git branch topic-menuで新しいブランチを作る  
git checkout topic-menuで作ったブランチに移動  
git push origin topic-menuで自分のリモートリポジトリにアップデート  
Git Hubで目的のリポジトリに行って、「Pull Request」→「New Pull request」
base: master
compare topic-menu
「masterにtopic-menuを反映させてください！」というリクエスト  
pull requestはbranchを依頼する。直接コミットするのではなく。  
管理者がマージするときは、ブランチの最新状態をマージする。（pull requestしてからのブランチ更新も反映される）



