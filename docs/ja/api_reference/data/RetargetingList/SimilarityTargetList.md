# SimilarityTargetList
類似ユーザーターゲットの情報を保持するオブジェクトです。
### Service
+ [RetargetingListService](../../services/RetargetingListService.md)

### Namespace
[RetargetingListService#Namespace](../../services/RetargetingListService.md#namespace)

| フィールド | データ型 | maxOccurs | minOccurs | response | add | set | remove | 説明 |
|---|---|---|---|---|---|---|---|---|
| <a href="./RetargetingTargetList.md">RetargetingTargetList</a>(inherited)|||||||||
| SimilarityTargetList|||||||||
| targetListId| long| 1| 0| ○| Req| -| -| 類似ユーザーをリターゲティングするターゲットIDです。 |
| similarityLevel| enum <a href="./SimilarityLevel.md">SimilarityLevel</a>| 1| 0| ○| Optional<br>Default: LOW| Optional| Ignore| 類似度です。 |

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
