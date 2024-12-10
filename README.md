# VoronoiShell for Bitaxe

![LookBook1](https://github.com/user-attachments/assets/16795312-05c9-4595-8f53-940d38d0571f)
![LookBook2](https://github.com/user-attachments/assets/6631ae99-bd79-4c5a-8bf5-bd2f7ed7cf3e)
![LookBook3](https://github.com/user-attachments/assets/1d75cec0-9d6e-4997-98e6-624fa3c3e863)
![FromView](https://github.com/tko-combinator/BitaxeVoronoiShell/blob/main/images/VoronoiShell_FrontView.png)

## 概要
Bitaxe Gamma(601)をベースとして設計をしています。
先にリリースをしたAirLiftFrameよりコンパクトになる事を目指しております、冷却や汎用性等のデメリットが多少あります。
(ESP32-S3のアンテナが飛び出しているモデルも意識して設計をしていますが、全くの未検証です。)
L字タイプなどのコネクタ類は干渉の恐れがあるので、USB-CやDC電源のコネクタはストレートタイプのものを推奨します。
下記の検証済み適合機種に限らず、2024/11現在発売されているシングルASICのBitaxeであればほぼ適合をするのではないかと考えています。

## 検証済み適合機種
基板の製造上の誤差や3Dプリント時の誤差や歪みなどによって、多少の調整が必要になるかもわかりません。
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## 必要な部品
* M3のタッピングネジ
(基板とマウンターの厚みが7mmのため、6mmの長さが推奨されます)
* 必要に応じて、インサートナットおよび適合するネジを用意してください。

## 製造情報
私は、AnkerMake M5を使用し、標準の0.4mmノズルと純正のPLA+フィラメントで出力しました。  
スライサーソフトウェアにはAnkerMake Studioを使用しました。
設定は各社3Dプリンタ事に異なると思いますが、参考になるよう情報共有をします。
デザインが複雑なので、サポート材の除去などが少しだけ難しいです。

### 出力時の設定
* 品質設定: 品質優先
* 造形方向: ケース背面から全面へ向かって積層
* 積層ピッチ: 0.16mm
* 充填密度: 60%
* サポート: オーガニック

形状やケースとしての用途を考えると、充填密度はある程度上げた方が安全です。  
ネジ穴は2.5mmとして設計していますが、使用するネジや出力品質によっては、2.5mm程度のドリルで二次加工が必要になる場合があります。  
※頻繁に基板の付け外しを行う場合は、インサートナットの使用を検討してください。  
面取りやバリを削るなどの仕上げをすると、見た目もより良くなります。

## カスタムの楽しみ
デカールを貼ったり、複数色のフィラメントやペイントなどのカスタムを加えて、個性的な仕上げにするのも面白いでしょう。  
では、DIYマイニングをエンジョイしましょう！
改良品や色んなバージョンを見てみたいです！

## ライセンス
このプロジェクトはMITライセンスの下で提供され、自由に使用、変更、配布することができます。
本リポジトリ内のデータ及び、データを元に制作された成果物に対しての一才の保証はございません。
詳細は同封のLICENSEをご覧ください。



## Overview
The design is based on the Bitaxe Gamma (601).
This model aims to be more compact than the previously released AirLiftFrame. However, it does have some drawbacks in terms of cooling and versatility.
(This design also considers models with protruding ESP32-S3 antennas, but this is entirely untested.)
L-shaped connectors may interfere with the case, so straight-type USB-C and DC power connectors are recommended.
While the tested compatible models are listed below, we believe that most single-ASIC Bitaxe models currently available as of November 2024 should fit.

## Confirmed Models
Due to manufacturing tolerances in the circuit board or errors and distortions during 3D printing, slight adjustments may be required.
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## Required Parts
M3 tapping screws  
(Since the thickness of the board and the mount is 7mm, screws with a length of 6mm are recommended.)  
Please prepare insert nuts and compatible screws as needed.

## Manufacturing
I used an AnkerMake M5 with a standard 0.4mm nozzle and genuine PLA+ filament to print this case.  
For slicing, I used AnkerMake Studio.  
The settings may vary depending on your 3D printer, but I’m sharing the details for reference.
The design is a bit intricate, so removing support materials can be slightly challenging.

### Settings
* Quality: Prioritize quality
* Orientation: Layered from the back of the case to the front
* Layer height: 0.16mm
* Infill density: 60%
* Support: Organic

Considering the shape and function as a case, it is safer to increase the infill density.  
The screw holes are designed to be 2.5mm, but depending on the screws used and the print quality, you may need to use a 2.5mm drill for post-processing.  
※ If you intend to frequently remove and reattach the board, consider using insert nuts.  
Also, finishing touches like chamfering or trimming burrs will also improve the overall appearance.

## Enjoy Customizing!
Adding decals, using multi-colored filaments, or painting can make for a fun, personalized finish.  
Enjoy your DIY mining journey! I can't wait to see how you "Kaizen" it with your own improvements and versions!

## License
This project is provided under the MIT license, allowing free use, modification, and distribution.  
No warranty is provided for any data in this repository or for any products created using the data.  
For more details, please see LICENSE file.




