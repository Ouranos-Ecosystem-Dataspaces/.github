<img src="https://github.com/Ouranos-Ecosystem-Dataspaces/.github/blob/main/images/OE%20Logo%20Ouranos%20Blue.png" width="45%">

## Ouranos Ecosystem Dataspaces (ウラノス・エコシステム・データスペーシズ) 関連Organization

独立行政法人情報処理推進機構（IPA）のデジタルアーキテクチャ・デザインセンター（[DADC](https://www.ipa.go.jp/dadc/index.html)）では、[経済産業省](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/index.html)をはじめとした関係省庁、国立研究開発法人 新エネルギー・産業技術総合開発機構（NEDO）とともに、運用及び管理を行う者が異なる複数の情報処理システムの連携の仕組みに関して、アーキテクチャの設計、研究開発・実証、社会実装・普及の取組（[ウラノス・エコシステム](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/ouranos.html)）を進めています。

ウラノス・エコシステムでは、産業界がデータスペースの社会実装を早急に進めるためのサービスライフサイクルに焦点をおいた参照モデル「[ウラノス・エコシステム・データスペーシズ リファレンスアーキテクチャモデル (Ouranos Dataspaces Reference Architecture Model)](https://www.ipa.go.jp/digital/architecture/reports/ouranos-ecosystem-dataspaces-ram-white-paper.html)」（以下、「ODS-RAM」という。）を公開しています。
ODS-RAMは技術非依存の仕様をはじめとした概念レベルを含み、4つの疎結合なレイヤと4つのパースペクティブ、それらに対応する役割、プロトコル及びサービスモデルで構成されます。
構成要素は、ODS共通と個々の社会実装のユースケース固有の要素に分けられ、その分類に沿ってOrganizationを作成しています。


<img src="https://github.com/Ouranos-Ecosystem-Dataspaces/.github/blob/main/images/ODS-RAM.png" width="60%">


■Ouranos-Ecosystem Dataspaces共通

　4つのレイヤなどの主要なサービスと、補助的なサービスに分けられます。
 
　[主要なサービス]
 
　Organizationの名前はODS-DES（Ouranos Ecosystem Dataspaces – Data Space Essential Services）で始まります。
 
　・ODS-DFS-L1 : L1データレイヤ
 
　・[ODS-DFS-L2](https://github.com/ODS-DFS-L2) : L2トランザクションレイヤ
 
　・[ODS-DFS-L3](https://github.com/ODS-DFS-L3) : L3アイデンティティレイヤ
 
　・[ODS-DFS-L4](https://github.com/ODS-DFS-L4) : L4セマンティクスレイヤ
 
　・ODS-DFS-CF (CF: Common Functionalities) : 各レイヤ共通機能
