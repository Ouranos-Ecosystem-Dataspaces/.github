<img src="https://github.com/Ouranos-Ecosystem-Dataspaces/.github/blob/main/images/OE%20Logo%20Ouranos%20Blue.png" width="45%">

## Ouranos Ecosystem Dataspaces (ウラノス・エコシステム・データスペーシズ) 関連Organization

独立行政法人情報処理推進機構（IPA）のデジタルアーキテクチャ・デザインセンター（[DADC](https://www.ipa.go.jp/dadc/index.html)）では、[経済産業省](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/index.html)をはじめとした関係省庁、国立研究開発法人 新エネルギー・産業技術総合開発機構（NEDO）とともに、運用及び管理を行う者が異なる複数の情報処理システムの連携の仕組みに関して、アーキテクチャの設計、研究開発・実証、社会実装・普及の取組（[ウラノス・エコシステム](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/ouranos.html)）を進めています。

ウラノス・エコシステムでは、産業界がデータスペースの社会実装を早急に進めるためのサービスライフサイクルに焦点をおいた参照モデル「[ウラノス・エコシステム・データスペーシズ リファレンスアーキテクチャモデル (Ouranos Dataspaces Reference Architecture Model)](https://www.ipa.go.jp/digital/architecture/reports/ouranos-ecosystem-dataspaces-ram-white-paper.html)」（以下、「ODS-RAM」という。）を公開しています。
ODS-RAMは技術非依存の仕様をはじめとした概念レベルを含み、4つの疎結合なレイヤと4つのパースペクティブ、それらに対応する役割、プロトコル及びサービスモデルで構成されます。
構成要素は、ODS共通と個々の社会実装のユースケース固有の要素に分けられ、その分類に沿ってOrganizationを作成しています。


<img src="https://github.com/Ouranos-Ecosystem-Dataspaces/.github/blob/main/images/ODS-RAM.png" width="70%">


■Ouranos-Ecosystem Dataspaces共通

4つのレイヤなどの主要なサービスと、補助的なサービスに分けられます。

[主要なサービス]   
Organizationの名前はODS-DES（Ouranos Ecosystem Dataspaces – Data Space Essential Services）で始まります。
- ODS-DFS-L1 : L1データレイヤ
- [ODS-DFS-L2](https://github.com/ODS-DFS-L2) : L2トランザクションレイヤ
- [ODS-DFS-L3](https://github.com/ODS-DFS-L3) : L3アイデンティティレイヤ
- [ODS-DFS-L4](https://github.com/ODS-DFS-L4) : L4セマンティクスレイヤ
- ODS-DFS-CF (CF: Common Functionalities) : 各レイヤ共通機能
  
[補助的なサービス]
- ODS-DCS (Ouranos Ecosystem Dataspaces - Dataspace Complementary Services)

<br>
■ユースケース固有

Organizationの名前はODS-IS (Ouranos Ecosystem Dataspaces - Industry Services)で始まります。
- [ODS-IS-CAVC](https://github.com/ODS-IS-CAVC) (CAVC : Connected Autonomous Vehicle Corridors): 自動運転支援道
- [ODS-IS-IMDX](https://github.com/ODS-IS-IMDX) (IMDX : Infrastructure Management DX): インフラDX
- [ODS-IS-UASL](https://github.com/ODS-IS-UASL) (UASL : Unmanned Aircraft Systems Lines): ドローン航路
- [ODS-IS-ALCA](https://github.com/ODS-IS-ALCA) (ALCA : Automotive Life Cycle Assessment): 自動車LCA
- [ODS-IS-STID](https://github.com/ODS-IS-STID) (STID : Spatio-Temporal ID): ウラノス4次元空間ID
- [Ouranos-Ecosystem-IDI](https://github.com/ouranos-ecosystem-idi) (IDI : Interoperable Data Infrastructure): サプライチェーンデータ連携基盤

