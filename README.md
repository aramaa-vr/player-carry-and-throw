# だこちてギミック【ワールド版】

VRChatのワールドで、プレイヤーを抱っこしたり、投げたりして遊べるギミックです。遊ぶ人のアバター側への導入は必要ありません。

パッケージID：`jp.aramaa.player-carry-and-throw` ／ 権利者：あらまあ

本体入りパッケージ：`0.1.0`。

## ワールドへの導入・更新

1. [VCCに配布リポジトリを追加](https://aramaa-vr.github.io/vpm-repos/redirect.html)します。
2. VRChat Creator Companion（VCC）で、導入先のWorldsプロジェクトに本パッケージを追加します。更新もVCCで行います。
3. Unityでワールドのシーンを開き、`Tools > Aramaa > だこちてギミック【ワールド版】` から、だこちて・組体操・投げ合いのいずれか1つを配置します。本体は1シーンに1つ配置してください。

動作を細かく調整したい場合は、カスタムモードを選び、ルートの日本語Inspectorとワールド設定UIで設定します。

Unity 2022.3のVRChat Worldsプロジェクトを使用してください。必要な依存パッケージはWorlds SDK（3.10.5以上・4.0.0未満）、TextMesh Pro 3.0.6、uGUI 1.0.0です。追加・更新前にプロジェクトをバックアップしてください。

同梱の日本語フォントは、現行UIで使う文字を収録しています。独自の文言やプレイヤー名などを表示する場合は、必要な文字を含むフォントを別途用意してください。

詳しい手順は[ワールドへの導入](https://aramaa-vr.github.io/player-carry-and-throw-pages/install/)をご覧ください。

## 遊び方

自分の「抱っこする」と相手の「抱っこされる」をONにして、相手の腰付近をつかみます。固定・投げ・解除の操作はモードによって異なります。

VRでは右スティックを下に約1秒長押しすると本人用UIを開閉できます。Desktopでは常設UIを使います。許可のON／OFFはUI内で切り替えます。

詳しい操作は[導入方法と遊び方](https://aramaa-vr.github.io/player-carry-and-throw-pages/)をご覧ください。

## 利用規約とクレジット

利用前に[利用規約](LICENSE.md)をご確認ください。正式な利用規約は日本語版VN3ライセンスPDFです。

第三者素材には各権利者のライセンスが適用されます。[第三者素材の通知とクレジット](<Third Party Notices.md>)をご確認ください。

- [変更履歴](CHANGELOG.md)
- [配布リポジトリ](https://github.com/aramaa-vr/player-carry-and-throw)
