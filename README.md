# uplatexをwsl上で爆速実行できる環境づくり（インストールから実行まで）
[Qiita](https://qiita.com/utaoji/items/d2a880905172440b27fe)にもあげてます。できればこっちで反応がほしい・・・
## WSLおよびUbuntuのインストール
LinuxとかWSLとかUbuntuとか、何言ってるかわからないよって人はここから

[WindowsにUbuntuをインストール](./install)
## LaTeXのインストール
Linuxの仮想環境を自分で用意できるけどLaTeXのインストール方法がわからない人はここから
内容は[TeX Wiki](https://texwiki.texjp.org/?Linux#texliveinstall)のものとほとんど同じなので、こちらを参照しても変わらないです

[LaTeXのインストール](./install/latex.md)
## VSCodeのインストールおよび準備
Windows上で行う作業です。すでにVScodeを使っている人はスキップしてよいです

[VScodeのインストールおよび準備](./install/VSCode.md)
## latexをVSCode上で使えるようにする
>[!CAUTION]
>すでにWindows上でLaTeXを使用するためにVSCodeのSettings.jsonを編集している場合、そちらの内容によっては正常に動作しない場合があります。
>Windowsの方でもこちらと同じ設定にするか、自分で書き換えるか、あきらめるかしてください

[latexmkrcの設定](./install/latexmkrc.md)

[setting.jsonの設定](./install/json.md)
## さらに高速化（任意）
[draftを用いて図を省略](./install/draft.md)

[subfilesを用いてファイル自体を短く](./install/subfiles.md)
