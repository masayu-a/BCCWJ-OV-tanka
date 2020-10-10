# BCCWJ-OV-tanka

## Description
『現代日本語書き言葉均衡コーパス』BCCWJ OV サンプルのうち短歌について、評定値と BERT のベクトルを付与したもの

## OV-masked.txt

1行目がヘッダです。

- tankaID 短歌に対するID （独自付与 0-origin）
- サンプルID BCCWJ 上のサンプルID
- 書字形出現位置 BCCWJ 上の書字形出現位置
- 短歌　（本データでは X でマスクしています）
- subjID 評定者のID
- metric 5種類の評定タイプ (GOODorBAD/良い-悪い(7-1), LIKEorDISLIKE/好き-嫌い(7-1), METAPHORICAL/比喩を含むor含まない, TEMPORAL/時間を表現するorしない), COMMENT/連想語を自由記述)
- value 評定タイプ

## OV-vector.txt

BERTed-BCCWJ の768次元ベクトルです。

## References
浅原正幸・加藤祥 (2020) [BERTed-BCCWJ:多層文脈化単語埋め込み情報を付与した『現代日本語書き言葉均衡コーパス』データ](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P2-5.pdf) 『言語処理学会第26回年次大会発表論文集』

## License
CC BY-NC-SA 3.0 https://creativecommons.org/licenses/by-nc-sa/3.0/deed.ja

## Acknowledgements
本データは科研費新学術領域研究 18H05521 [「言語による時間生成」](https://kaken.nii.ac.jp/ja/grant/KAKENHI-PLANNED-18H05521/)、科研費挑戦的研究（萌芽）[「コーパスからの比喩表現収集とその分析」](https://kaken.nii.ac.jp/ja/grant/KAKENHI-PROJECT-18K18519/)、国立国語研究所コーパス開発センター共同研究プロジェクト、大学共同利用機関法人4機構の異分野融合・新分野創成委員会「機構間連携・異分野連携プロジェクト」として採択した「知性と認識の情報神経物理学」の成果物です。

