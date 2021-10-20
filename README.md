# 新型コロナウイルスの感染拡大状況とワクチン接種進捗に応じた医療需要の予測ツール


　新型コロナウイルスに対するワクチン接種が進む中、その効果によって、感染者数（検査陽性者数）が多くとも必ずしも直ちに医療提供体制の逼迫につながるわけではなくなってきている。われわれは、今後の感染拡大の際に必要となる病床数（酸素投与を必要とする患者や重症者の数にもとづく。）といった医療需要について、短期的（1から4週間後）あるいは中期的（1から2ヶ月後）に予測するためのツールを開発した（EXCELファイル：医療需要予測ツール_20211020.xlsx　ダウンロードするには、ファイル名をクリック後、「Download」を選択）。本ツールでは、任意の状況を想定して「新規陽性者数、ワクチン接種率、感染拡大スピード」を使用者が入力する。さらに、ワクチンの効果・年代別の重症化率・入院期間といったパラメータがあらかじめ入力されている。これらの初期値は、科学論文や複数の自治体からのデータをもとに設定したが、使用者が任意の値に変更することも可能である。

　本ツールによって、2021年の冬期の流行をそれぞれの自治体で想定しながら、必要とする病床の確保ならびに、どういう段階で地域での感染対策の強化などを呼びかける必要があるかの検討に用いることができる。また、今後リバウンドが起こった際には、その後に起こりうる状況の見える化にも用いることができる。


・短期的な予測

短期的な予測において2週間～4週間後の状況が現在の確保病床数を越えるか否かを検討することで、警戒や感染対策の強化を行うべきか判断の参考として用いることができる。（なお、4週間にわたって同じ感染拡大スピードであり続けると仮定している。一方で、市民の行動の変化などがあった場合にはその想定は過大になる可能性があることに注意が必要である。）

・中期的な予測

今後の流行で想定される感染の広がりとして、たとえば、ある時点での新規陽性者数・ワクチン接種率を入力し、「拡大シナリオ：横ばい（1.0→横ばい）」とすることで、現在の状態が続いた場合に医療需要がどの程度になるのかを検討することができる。また、今後、リバウンドが見られ始めたとき、「そのときの新規陽性者数」と「そのときのワクチン接種率」を入力し、「拡大シナリオ：増加（1.3～1.5→先月と同様）」と設定することで、第６波で起きうるその後２か月間の悲観的な予測を検討できる。さらに、「さまざまな新規陽性者数」と「今冬に想定されるワクチン接種率」を入力し、予測ツールによって算出される「酸素投与を要する人の数、重症者数、必要な確保病床数」を参照することで、【現在の確保病床ではどの程度の規模の感染状況に耐えられるのか】や【想定される感染規模に対して、どの程度の確保病床数が必要になるのか】を検討するためのデータを得ることができる。詳しくは、PDF資料（医療需要予測ツール_説明資料_20211020.pdf）に説明がある。


　本ツールはインターネット上で公開されており、行政・医療機関・一般市民が自由に利用することができる。あくまでモデルであり絶対的なものではないことには留意されたい。１つの参考資料として、本ツールが今後の流行に対する備えや、更なる議論の発展に役立つことを期するものである。


本ツール、およびモデルの詳細や説明資料を入手できるURL：
https://github.com/yukifuruse1217/COVIDhealthBurden

予測ツールの開発・検証チーム
古瀬 祐気（京都大学）、和田 耕治（国際医療福祉大学）、押谷 仁（東北大学）、髙 勇羅（国立感染症研究所）、鈴木 基（国立感染症研究所）、脇田 隆字（国立感染症研究所）

文責：古瀬 祐気
問い合わせ先：furusey.kyoto@gmail.com
