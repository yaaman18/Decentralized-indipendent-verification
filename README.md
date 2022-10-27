# Decentralized-indipendent-verification
　　
## 分散型検証プログラムのデザインについて 
　　　　　
   
### １、概要
- イーサリアムの EVM上に展開されるスマートコントラクトを用いて、参加する全ての人々が相互に言語に基づく全ての事象を検証していくシステムを構築する。
- 解決すべき課題：　現代のインターネット上の情報は信用性の低い情報が多く、またそれらの情報が特定の人物や大きなIT企業のアルゴリズムで無分別に拡散していて、情報に関する正確さが担保されない。
- また巨大企業が持つデータセンターに情報が集中して管理されており、それらの会社の方針によってユーザーの排除や情報のブロックが行われている。
それらの問題を解決する為に中央の管理者が存在しない、そして透明性の高い非中央集権型のデータ検証用の組織を構築する。
- それは全ての人々が参加可能であり、それによって得た利益を参加者全員が共有できるものであるようにする。
　　　　　　　　　　　　　　　　　　　　　
                     　　　
### ２、取り扱う対象
- 言語を基とした全情報。
例えば思想、ジャーナリズムの正確性、学術的な論文の査読、歴史の考証、文芸批評、趣味の情報、旅行先の記録、詩の定義などの言語や文字に関する全ての種類の情報を正確に評価や検証していく。
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
                                   
### ３、手法
  
- 構築したプロトコル上にDAOを作り、その内部で各課題や各言語に関するグループを作る。
- それらのグループが興味のあるテーマを検証した後に一般公開する。
- 検証した内容はNFTとしてmintしてその価値を更にDAOの内部で判定する（グループが所有するのは検証した内容であり、そこで引用されている文章そのものは元の著作権者のもののままである。）
- 公開された検証物の内容は評価値を算出するシステムを介してDAO全体に公開する。その評価値とマーケットでの売却総額により検証しているグループの総合的な価値が決まる。

#### 検証したテーマの評価方法
- テーマの評価するメンバーは事前に自身が持っているerc20 tokenを預ける。
- レビュワーの人数は混乱を避ける為に予め発表したグループが上限を決めておく（例えば２０人上限など）。同様にレビューの期限も決める。
- レビューが公開した内容とは関係無い場合はそれを消去してトークンを返還する。
- 公開側のグループは評価の重要性に順位付けをする。貢献値が高ければレビュワーにtokenを支払う。
（ここから先はどのように公開側のERC７２１を利用してグループの評価値を高めるか検討する必要がある。形式的にはグループに株価的な要素を蒸して、その評価額を上げていくようにしたい。）





