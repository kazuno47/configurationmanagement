# はじめに
Configuration Management(CM)とは、構成管理、形態管理、変更管理などと訳されることが多いが、本ドキュメント内ではコンフィギュレーションマネジメントあるいはCMと表記する。理由は、構成管理や変更管理はConfiguration Managementの一端に過ぎず、誤った印象を持つ可能性があるためである。

CMはWikipediaでは下記のように記載されている。

> Configuration management ( CM ) is a systems engineering process for establishing and maintaining consistency of a product's performance, functional, and physical attributes with its requirements, design, and operational information throughout its life.

> 構成管理 （ CM ）は、製品の性能、機能、および物理的属性の要件、設計、運用情報を一貫して確立し、維持するためのシステムエンジニアリングプロセスです。

> CM is the practice of handling changes systematically so that a system maintains its integrity over time

> CMは、 システムが時間の経過とともにその整合性を維持するように、変更を体系的に処理するプラクティスです。

## システム開発におけるCMの対象

システム開発においては、管理する対象（Configuration Item）により、大きく下記3つの分類が行われる。

1. ドキュメント管理
2. ライブラリ管理
3. 環境管理

それぞれの管理対象の概要について説明する。

### ドキュメント管理

システム開発で必要なドキュメントを管理する。プロジェクト計画書、アーキテクチャ設計書、画面設計書、テーブル設計書など。

### ライブラリ管理

システムを構成するソースコードや設定ファイル。初期登録データなどを管理する。.java,.xml,.propatiesなど。

### 環境管理

システム開発で使用する、各種環境について管理する。開発環境、試験環境、本番環境など。
