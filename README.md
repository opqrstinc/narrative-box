# narrative-box

<p align="center">
  <img src="https://github.com/user-attachments/assets/3396854e-a1aa-4cf0-bea5-f0311c0edcb1" width="300">
</p>

## 概要

Narrative boxは、**株式会社OPQRST**が開発した、AIを用いて模擬症例を作成するプロジェクトです。疾患の典型例を提供することで、稀な疾患の症状や検査、治療、その後の経過を理解するのに役立ちます。AIで生成した症例を、医師が修正したバージョンも作成中です。自己学習、教育、研究にご利用いただけます。現在、日本語以外の言語でも症例を作成しています。
また医学以外の分野にも拡充予定です。

## 特徴

- **多言語対応**：日本語以外にも症例を提供
- **AIで出力**：OpenAI社の複数のモデルを利用して生成。独自のプロンプトを使用
- **専門家の監修**：医師等各分野による修正と監修（予定）
- **教育用途**：自己学習や教育現場での活用

## 使い方

1. リポジトリをクローンまたはダウンロードします。
2. 必要な言語や疾患のフォルダを参照します。
3. 症例ファイルを閲覧またはダウンロードしてご利用ください。

## ディレクトリ構成

Narrative box

|-　日本語：言語ごとに分けています  
　|-　Medical：医師の臨床のNarrative  
　　|-　Disease：疾患ごとに分けています
　　　  |-　Vignette：診断名から生成したVignette（症例集）です  
　　　  |-　Dialogue：Vignetteから生成したDialogue（医師と患者の対話）です  
　　　  |-　Semantic qualifier：診断名から生成したSemantic Qualifierです  
　　　  |-　Illness script：診断名から生成したIllness Scriptです 
       |-　Questionnaire：診断名から生成した問診票です  
　　　　　　|-　診断名_書類種類_使用モデル_通し番号.yaml　書類本文です  
　　　　　　|-　診断名_書類種類_使用モデル_通し番号_MD-modified.yaml：専門家（医師）が修正したテキスト  
　|-　Nurseing:看護師のケア現場のNarrative  
　|-　Legal：法曹関係者のNarrative  
　|-　School Health：養護教諭のNarrative  
|-　English  
|-　Español  
|-　中文（普通话）  
⋮  

## 書類本文形式
YAML形式を使用しています。メタデータとしてNarrative boxの構成や使用モデル、作成に使用した情報などを含みます。

## 使用モデル
現在はOpenAI社のモデルを使用しています。
モデルの詳細については以下を参照してください。
https://platform.openai.com/docs/models

## ライセンス
このプロジェクトは、MITライセンスの下で公開されています。詳細はライセンスファイルをご確認ください。

## 免責事項
- 本プロジェクトで提供する症例は教育・研究目的であり、医療行為の参考とするものではありません。
- 症例情報は正確性を期していますが、内容の完全性や最新性を保証するものではありません。
- 本プロジェクトの利用により生じた如何なる損害についても、開発者およびOPQRST Inc.は一切の責任を負いません。

## 貢献
バグ報告や内容の選定の提案などの貢献を歓迎します。詳しくはCONTRIBUTING.mdをご覧ください。

## コンタクト
ご質問やご提案がございましたら、Issueを作成するか、以下の連絡先までご連絡ください。
- Email: contact@opqrst.co.jp
- 公式サイト: https://www.opqrst.co.jp/
