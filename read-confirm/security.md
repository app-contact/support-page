# Security Policy - Read Confirm

**Last updated: April 2026**

## Overview

Read Confirm ("the App") is a Confluence Cloud application built on Atlassian Forge. This Security Policy describes the security measures and architecture that protect your data.

## Architecture & Infrastructure

Read Confirm is built entirely on **Atlassian Forge**, a serverless platform that runs within Atlassian's own cloud infrastructure. This architecture provides significant security advantages:

- **Backend (Resolvers)**: All server-side code executes within Atlassian's serverless environment — no external servers are involved
- **Frontend**: Runs in a sandboxed iframe within the Confluence interface, isolated from other content
- **Data Storage**: All data is stored in Forge Storage, managed and encrypted by Atlassian
- **No External Services**: The App does not make any outbound network requests to external servers or third-party services

## Data Protection

### Encryption

- **At Rest**: All data stored in Forge Storage is encrypted at rest by Atlassian's infrastructure
- **In Transit**: All communications are encrypted using TLS/HTTPS

### Data Isolation

- Data is scoped to each Confluence site installation
- No data is shared between different customer installations
- No data leaves Atlassian's infrastructure

### Data Minimization

We collect only the minimum data required for confirmation tracking:

- User account IDs (for tracking who confirmed)
- Confirmation timestamps
- Request metadata (deadlines, messages, target settings)

## Access Control

- Any Confluence user with page editing permissions can create confirmation requests
- Users can view confirmation status for requests associated with pages they have access to
- All access is governed by Confluence's existing permission model
- The App requests only the minimum permission scopes necessary for its functionality

## Permissions

The App requests only the minimum permissions necessary for its functionality, including reading page and user information for confirmation tracking and storing data via Forge Storage. For details on how Forge manages app permissions and scopes, refer to [Atlassian's Forge documentation](https://developer.atlassian.com/platform/forge/manifest-reference/permissions/).

## Vulnerability Management

- The App follows secure coding practices
- Dependencies are regularly reviewed and updated
- The Forge platform handles underlying infrastructure security, patching, and updates

## Incident Response

In the event of a security incident:

1. We will investigate and assess the scope and impact promptly
2. Corrective measures will be implemented and verified
3. A post-incident review will be conducted to prevent recurrence

## Compliance

- The App is designed to support **GDPR** and **CCPA** compliance requirements
- No personal data is transferred outside of Atlassian's infrastructure
- See our [Privacy Policy](https://app-contact.github.io/support-page/read-confirm/privacy) for details on data handling practices

## Third-Party Audits & Certifications

The App runs entirely within Atlassian's Forge infrastructure, which benefits from Atlassian's own security certifications, including SOC 2 and ISO 27001. For details, refer to [Atlassian's Trust Center](https://www.atlassian.com/trust).

## Changes to This Policy

We may update this Security Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Security Policy, please contact:

**middlecore**
Email: contact@middle-core.com

---

*This security policy is effective as of April 2026.*

---
---

# セキュリティポリシー - Read Confirm

**最終更新: 2026年4月**

## 概要

Read Confirm（以下「本アプリ」）は、Atlassian Forge 上に構築された Confluence Cloud アプリケーションです。本セキュリティポリシーは、お客様のデータを保護するセキュリティ対策とアーキテクチャについて説明します。

## アーキテクチャとインフラ

Read Confirm は **Atlassian Forge** 上に完全に構築されています。Forge は Atlassian 独自のクラウドインフラ内で動作するサーバーレスプラットフォームです。このアーキテクチャにより、以下のような重要なセキュリティ上の利点があります:

- **バックエンド（リゾルバー）**: すべてのサーバーサイドコードは Atlassian のサーバーレス環境内で実行されます。外部サーバーは関与しません
- **フロントエンド**: Confluence インターフェース内のサンドボックス化された iframe で動作し、他のコンテンツから隔離されています
- **データストレージ**: すべてのデータは Forge Storage に保存され、Atlassian によって管理・暗号化されています
- **外部サービスなし**: 本アプリは外部サーバーやサードパーティサービスへのアウトバウンドネットワークリクエストを行いません

## データ保護

### 暗号化

- **保存時**: Forge Storage に保存されるすべてのデータは、Atlassian のインフラにより保存時に暗号化されます
- **通信時**: すべての通信は TLS/HTTPS を使用して暗号化されます

### データの隔離

- データは各 Confluence サイトのインストールごとに分離されています
- 異なる顧客のインストール間でデータが共有されることはありません
- データが Atlassian のインフラ外に出ることはありません

### データの最小化

確認追跡に必要な最小限のデータのみを収集します:

- ユーザーアカウント ID（誰が確認したかの追跡用）
- 確認日時
- 依頼のメタデータ（期限、メッセージ、対象設定）

## アクセス制御

- ページ編集権限を持つ Confluence ユーザーが確認依頼を作成できます
- ユーザーは、アクセス権のあるページに関連する確認依頼のステータスを閲覧できます
- すべてのアクセスは Confluence 既存の権限モデルに基づいて管理されます
- 本アプリは機能に必要な最小限の権限スコープのみをリクエストします

## 権限

本アプリは機能に必要な最小限の権限のみをリクエストします。これには、確認追跡のためのページおよびユーザー情報の読み取り、Forge Storage によるデータの保存が含まれます。Forge がアプリの権限とスコープをどのように管理するかの詳細については、[Atlassian の Forge ドキュメント](https://developer.atlassian.com/platform/forge/manifest-reference/permissions/) をご参照ください。

## 脆弱性管理

- 本アプリはセキュアコーディングの慣行に従っています
- 依存関係は定期的にレビュー・更新されます
- Forge プラットフォームが基盤インフラのセキュリティ、パッチ適用、アップデートを管理します

## インシデント対応

セキュリティインシデントが発生した場合:

1. 速やかに調査を行い、範囲と影響を評価します
2. 是正措置を実施し、検証します
3. 再発防止のためのインシデント後レビューを実施します

## コンプライアンス

- 本アプリは **GDPR** および **CCPA** のコンプライアンス要件に対応するよう設計されています
- 個人データが Atlassian のインフラ外に移転されることはありません
- データの取り扱いの詳細については、[プライバシーポリシー](https://app-contact.github.io/support-page/read-confirm/privacy) をご参照ください

## 第三者監査・認証

本アプリは Atlassian の Forge インフラ内で完全に動作するため、SOC 2 および ISO 27001 を含む Atlassian 自身のセキュリティ認証の恩恵を受けています。詳細については、[Atlassian Trust Center](https://www.atlassian.com/trust) をご参照ください。

## 本ポリシーの変更

弊社は、本セキュリティポリシーを随時更新する場合があります。変更は更新日とともに本ページに掲載されます。

## お問い合わせ

本セキュリティポリシーに関するご質問は、以下までお問い合わせください:

**middlecore**
Email: contact@middle-core.com

---

*本セキュリティポリシーは 2026年4月 より有効です。*
