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

BERTedBCCWJ の768次元ベクトルです

