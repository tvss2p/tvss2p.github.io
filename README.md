# tvss2p.github.io

「ファミリー物語」（https://tvss2p.github.io/family-monogatari/）の Googleログイン用の置き場所。

- `__/auth/` … Firebase のログイン用ファイル（family-monogatari.firebaseapp.com/__/auth/ から取ってきたもの）。GitHub Pages で `/__/auth/handler` として開けるよう `.html` を付けている
- `__/firebase/init.json` … Firebase の設定（ブラウザに配る前提の値）
- `.nojekyll` … `__` で始まるフォルダを GitHub Pages に出すため

iPhone のホーム画面アプリやSafariは、別のドメイン（firebaseapp.com）の保存を読めずログインが戻ってこないため、ゲームと同じドメインに置いている。
参考：https://firebase.google.com/docs/auth/web/redirect-best-practices （Option 4）
