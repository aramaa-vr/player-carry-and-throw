# Third Party Notices

以下は本VPMパッケージに同梱する第三者製素材です。各素材にはそれぞれのライセンスが適用され、自作ギミックのVN3による再配布禁止等は適用されません。著作権表示と必要な通知を維持してください。

## Noto Sans JP

`Runtime/Fonts/NotoSansJP-Medium.ttf` と、このフォントから生成したSDFアトラスを日本語UIに使用します。

(c) 2014-2021 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'.

SIL Open Font License 1.1。著作権表記は同梱TTFのnameテーブルに従います。[ライセンス全文](docs/licenses/NotoSansJP.txt)を同梱します。

## OtoLogic

以下の効果音素材はOtoLogicが提供しています。

- `Runtime/Audio/Anime_Motion27-1(High).mp3`
- `Runtime/Audio/Motion-Blow_Away04-2(Long).mp3`

効果音提供：OtoLogic (https://otologic.jp/) / CC BY 4.0

公式サイト：[OtoLogic](https://otologic.jp/)。ライセンス：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。[OtoLogic公式利用規約](https://otologic.jp/free/license.html)を参照してください。

これらの音源にはPlayerCarryAndThrow独自の利用規約ではなく、OtoLogic／CC BY 4.0のライセンス条件が適用されます。PlayerCarryAndThrow独自の再配布禁止等の条件は、これらの音源のCC BY 4.0上の権利を制限しません。

音源の変更について、既存の[収録記録](docs/licenses/OtoLogic.md)ではユーザー提供のMP3を内容変更・形式変換なしで収録しています。原配布ファイルとの照合は未実施です。UnityのAudioClipへのインポートと、AudioSource／VRC Spatial Audioによる再生時の音量・空間化・距離減衰の設定があります。今回、音源ファイルやインポート・再生設定は変更していません。

公開ワールドの説明・クレジット等には、例えば次のように表示してください。音源を改変した場合は変更内容も表示してください。

> 効果音：OtoLogic (https://otologic.jp/) / CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)

## TextMesh Pro shaders

対象は `Runtime/UI/Shaders/TMP_SDF.shader`、`CarryHUDText.shader`、`TMPro.cginc`、`TMPro_Properties.cginc` です。TextMesh Pro 3.0.6のSDFシェーダーとincludeを基にしています。専用シェーダー名とGUIDを使用し、外部のMobileシェーダーへのFallbackを無効にしています。

TextMesh Pro copyright © 2021 Unity Technologies ApS

Unity Companion License。元パッケージの[ライセンス表記](docs/licenses/TextMeshPro.md)を同梱します。Unity依存のプロジェクトで使用してください。

## 別途取得する依存パッケージ

VRChat SDK／UdonSharp（`com.vrchat.worlds`）、TextMesh Pro（`com.unity.textmeshpro`）、uGUI（`com.unity.ugui`）は依存パッケージとして別途取得します。上記に明記したTMP由来の同梱ファイルを除き、これらのパッケージ本体は再梱包しません。依存パッケージには各パッケージのライセンスが適用されます。
