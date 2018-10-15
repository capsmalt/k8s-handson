# 1. はじめに
## 1.1  当ハンズオンの目的
RESTで文字列をGETするシンプルなマイクロサービスを作成し，Kubernetes上 (IBM Cloud Private上)に継続的にデプロイする方法を体験します。
具体的には，コンテナとして動作するツール (IBM Microclimate) を使って「CI (Continuous Integration) / CD (Continuous Delivery) 」を実践します。

※注意: 
本ハンズオンはKubernetes 自体の詳説は行いません。

## 1.2  ハンズオン環境について
利用環境は，Lab1と同様です。
受講者1人につきIBM Cloud Private シングル構成 (Kubernetesクラスター) を1つ用意しています。

受講者はリモート環境 (Ubuntu上に構築したK8s環境) に接続し，ターミナル(TeraTermなど)でのコマンド操作の他，クライアントPCのブラウザ (Chrome or Firefox) を使用します。
クラウドネイティブのアプリやインフラの開発・運用において重要なパーツとなるツールを構築するところから学びます。

## 1.3  ハンズオンコンテンツについて
以下，2つのことを実施します。
- (Lab3-1) IBM Microclimate ツールを Kubernetes上に構築
- (Lab3-2) マイクロサービスを新規作成して Kubernetes 上に自動デプロイ