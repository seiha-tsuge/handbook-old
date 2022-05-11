---
sidebar_position: 1
---

# 公式ドキュメント

## IAM

https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/introduction.html

### ルートユーザー

AWSアカウントは、すべての操作ができる操作権限を保有しているため、[ルートユーザー](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_root-user.html)とも呼ばれます。ルートユーザーは非常に強力な権限を保有しているため、乗っ取られた場合のリスクが大きくなります。そのため、AWSではサービスを利用するためだけのIAMユーザーの作成を推奨しています。

### IAMユーザー

[IAMユーザー](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_users.html)は、AWSアカウント内で何らかの権限を与えられたユーザーまたはアプリケーションです。各ユーザーには、個別のアクセスキーを作成できるため、アプリケーションが使うことも出来ます。

### IAMポリシー

[IAMポリシー](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/access_policies.html)は、実行者(ユーザー、グループ、ロール)が、AWSリソースに対してどのようなアクションを許可または拒否するのかを定義したものです。

#### AWS管理ポリシー

#### カスタマー管理ポリシー

#### インラインポリシー

#### リソースベースポリシー

#### JSONステートメント記法

### IAMユーザーグループ

[IAMユーザーグループ](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_groups.html)は、IAMユーザーの集合です。IAMユーザーグループを使用すると、複数のIAMユーザーに対してアクセス許可を指定でき、それらのIAMユーザーのアクセス許可を容易に管理できます。

### IAMロール

https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_roles.html
