---
title: "Permissions-Policy: web-share"
slug: Web/HTTP/Reference/Headers/Permissions-Policy/web-share
original_slug: Web/HTTP/Headers/Permissions-Policy/web-share
---

{{HTTPSidebar}} {{SeeCompatTable}}

HTTP の {{HTTPHeader("Permissions-Policy")}} ヘッダーにおける `web-share` ディレクティブは、減殺の文書が Web Share API の {{domxref("Navigator.share","Navigator.share()")}} メソッドを使用して、テキスト、リンク、画像、その他のコンテンツをユーザーが選択した任意の宛先にシェアすることを許可するかどうかを制御します。

## 構文

```
Permissions-Policy: web-share <allowlist>;
```

- \<allowlist>
  - : この機能を許可するオリジンのリストです。 [`Permissions-Policy`](/ja/docs/Web/HTTP/Reference/Headers/Permissions-Policy#%E6%A7%8B%E6%96%87) を参照してください。

## 既定のポリシー

既定値は `'self'` です。

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}

ブラウザーへの実装は <https://github.com/w3c/web-share/issues/169> で議論されています。

## 関連情報

- {{HTTPHeader("Permissions-Policy")}} ヘッダー
- [機能ポリシー](/ja/docs/Web/HTTP/Guides/Permissions_Policy)
- [機能ポリシーの使用](/ja/docs/Web/HTTP/Guides/Feature_Policy/Using_Feature_Policy)
