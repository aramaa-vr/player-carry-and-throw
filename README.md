# だこちてギミック【ワールド版】

権利者：あらまあ  
パッケージID：`jp.aramaa.player-carry-and-throw`

パッケージ版 **0.0.1** は、利用規約のみを収録する初回の配布確認用パッケージです。初回公開予定であり、ギミック本体は含まれません。導入してもギミックやメニューは追加されません。

## 利用規約

利用規約版は **1.0** です。パッケージ版0.0.1とは別の番号です。

- [日本語版VN3ライセンスPDF（正式な利用規約）](docs/licenses/VN3/20261031051655vn3license_ja.pdf)
- [英語版（参考資料）](docs/licenses/VN3/20261031051655vn3license_en.pdf)
- [中国語版（参考資料）](docs/licenses/VN3/20261031051655vn3license_zh.pdf)
- [韓国語版（参考資料）](docs/licenses/VN3/20261031051655vn3license_ko.pdf)

あらまあ制作の本ギミックの改変、VRChatワールドへの導入・公開は、利用規約の範囲内で許可されます。ギミック本体および改変版の二次配布は禁止されます。利用条件の詳細は日本語版PDFを確認してください。この案内は原本に条件や例外を追加するものではありません。

第三者素材にはそれぞれ個別のライセンスが適用され、VN3の案内がその許諾を制限するものではありません。今回の配布物には音源・フォント等の第三者素材を含みません。[利用規約の案内](LICENSE.md)も参照してください。

## 配布確認

GitHub Releasesに添付する導入用ZIPは `jp.aramaa.player-carry-and-throw-0.0.1.zip` です。GitHubが自動生成する「Source code (zip)」「Source code (tar.gz)」はリポジトリのスナップショットで、導入用ZIPとは別です。

**同じIDのギミック本体を導入済みのプロジェクトを0.0.1へダウングレードしないでください。** 別のテストプロジェクトで確認してください。SDK・TMP・uGUI等を導入する依存関係はありません。

VCC用ZIPではPDFを `Documentation~/Licenses/VN3/` に収録します。このリポジトリの `docs/licenses/VN3/` とは配置が異なります。

## 公開準備の状態と今後の更新

[更新履歴](CHANGELOG.md)と[VPM Listingの下書き](index.json)を収録しています。公開先情報が未確定のため、現時点の `index.json` は公開用として未完成です。公開前にListing自身のURLと、0.0.1のRelease添付ZIPの実URLを設定してください。`zipSHA256` は今回作成したZIPから計算した値です。

今後はVCC用パッケージZIPをGitHub Releasesへ追加し、README・更新履歴・VPM Listingを必要に応じて更新します。開発プロジェクト全体やギミックのソースはこのリポジトリに持ち込みません。
