
---
## **ユースケース 1: （PXT社）商談記録の自動生成・分析による営業スキル向上**
**課題**  
- 商談データの入力が手作業で行われており、営業負担が大きく、適当に入力しているケースもある  
- 営業担当者の能力によって記録のクオリティがばらつき、必要な情報が適切に残っていない  
- 蓄積された 商談データの質・量が十分ではなく、データの活用が困難  
- 営業ナレッジが個々の経験に依存しており、ベテラン営業の成功ノウハウが共有されなく、営業担当者のスキルにばらつきがある

**実現方法**

**① 商談記録の自動収集・分析**
- **マルチモーダル生成AI** を活用し、商談の 音声・テキスト・資料 を統合し、AIが 自動要約  
- **プロンプト・エンジニアリング** により、商談の 論点整理やキーワード抽出 を行い、営業担当者が重要ポイントを振り返りやすくする 

**② 記録の標準化とノウハウ共有**
- **検索拡張生成（RAG）** を活用し、過去の商談データを検索・整理し、成功パターンを抽出 
- 商談データをCRMやSFAと統合し、データの質を向上  

**③ 営業担当者へのフィードバック・活用支援**
- **生成AI対応アプリケーション** により、商談ごとに **改善点や次回の推奨アクションを提示**  
- **営業パフォーマンスの定量化**（記録の質・成功確率・商談の流れ）を自動で可視化  

**想定結果**
- **手入力負担の削減** → AIが自動で要約し、営業担当者の記録作成を簡素化  
- **記録の質向上** → 営業スキルに依存せず、AIが適切なフォーマットで情報を整理  
- **営業の振り返り精度向上** → 自動生成レポートで、営業担当者が **自身の強み・改善点を把握** できる  
- **成約率向上** → AIが過去の成功パターンを分析し、営業担当者が商談前に **最適な戦略を立案** 可能に  
- **組織全体の営業力強化** → ベテラン営業のスキルをAIが分析し、**営業全体に最適な商談戦略を展開**  

**業務プロセスの変化**
| **業務プロセス** | **As-Is（現状）** | **To-Be（改善後）** | **必要な機能** |
|----------------|----------------|----------------|----------------|
| 商談記録作成 | 営業担当者が手入力（ばらつきあり） | AIが自動で音声・テキストを要約 | 音声認識、要約生成、感情分析 |
| 記録フォーマットの標準化 | 営業担当者の記録スタイルに依存 | AIが統一フォーマットで自動作成 | プロンプト最適化、ドメイン特化モデル |
| 成功パターンの分析 | データが不十分で分析が難しい | AIがデータを統合し、成功要因を抽出 | RAG、データ統合 |
| 商談の振り返り | 自己評価に依存 | AIが商談ごとにフィードバック | プロンプト最適化、データ可視化 |
| 過去事例の活用 | ベテラン営業が経験的に判断 | AIがCRM/SFAから最適な事例を提示 | データ検索 |

---

---

## **ユースケース 1: 商談記録の自動要約・分析**
**課題:**  
- 営業担当者が商談後に手入力で記録を作成しており、記録の属人化や記入漏れが発生  
- 商談データが未構造化のままで、分析や共有が難しい  

**実現方法:**  
- **マルチモーダル生成AI** を活用し、音声・テキスト・画像を統合して商談を自動要約  
- **検索拡張生成（RAG）** を用いて過去の商談記録を検索し、類似案件やベストプラクティスを提示  
- **ドメイン固有生成AIモデル** により業界・クライアント特化のナレッジを組み込む  

**想定結果:**  
- 商談記録の作成負担が削減され、記録の標準化と精度向上  
- 過去の商談データと比較して、商談の成功パターンやリスク要因を可視化  
- 営業担当者が次回のアクションをより適切に判断可能  

| **業務プロセス** | **As-Is（現状）** | **To-Be（改善後）** | **必要な機能** |
|----------------|----------------|----------------|----------------|
| 商談記録作成 | 営業担当者が手作業で記録作成 | AIが自動で音声・テキストを要約 | 音声認識、要約生成、感情分析 |
| 過去データの検索 | 過去記録を手動で検索 | RAGで類似案件を自動提示 | 商談データベース、検索拡張生成 |
| 商談ナレッジ活用 | 経験則に依存 | 生成AIで適切な次回アクションを提示 | ドメイン固有モデル、プロンプト最適化 |

---
