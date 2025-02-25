---
title: Window.outerHeight
slug: Web/API/Window/outerHeight
---

{{APIRef}}

**`Window.outerHeight`** は読み取り専用のプロパティで、サイドバー、ウィンドウの操作部分、ウィンドウをリサイズする境界やハンドルを含む、ブラウザーウィンドウ全体の高さをピクセル単位で表します。

## メモ

ウィンドウの大きさを変更するには、 {{domxref("window.resizeBy()")}} および {{domxref("window.resizeTo()")}} を使用してください。

ウィンドウの内側の高さ、つまりページが表示される高さを取得するには、 {{domxref("window.innerHeight")}} を使用してください。

### 図による例示

以下の図は、 `outerHeight` と `innerHeight` の違いを示しています。

![innerHeight vs outerHeight illustration](/@api/deki/files/213/=FirefoxInnerVsOuterHeight2.png)

## 仕様書

| 仕様書                                                                                               | 状態                             | 備考 |
| ---------------------------------------------------------------------------------------------------- | -------------------------------- | ---- |
| {{ SpecName('CSSOM View', '#dom-window-outerwidth', 'Window.outerWidth') }} | {{ Spec2('CSSOM View') }} |      |

## ブラウザーの対応

{{Compat("api.Window.outerHeight")}}

## 関連情報

- {{domxref("window.innerHeight")}}
- {{domxref("window.innerWidth")}}
- {{domxref("window.outerWidth")}}
- {{domxref("window.resizeBy()")}}
- {{domxref("window.resizeTo()")}}
