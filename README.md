<div align="right">

**🇯🇵 日本語**　|　[English](README.en.md)

</div>

<h1 align="center">Yuanru&nbsp;Liu &nbsp;·&nbsp; <ruby>劉<rt>リュウ</rt></ruby> <ruby>淵茹<rt>エンジョ</rt></ruby></h1>

<p align="center">
  <em>M.S., 九州大学大学院 生物資源環境科学府 · 数理モデリング学研究室（2025 年 9 月修了）</em><br />
  深層学習 × 応用統計
</p>

<p align="center">
  <a href="mailto:yuanruliu123@gmail.com">📧 Email</a>　·　
  <a href="https://github.com/liuyuanru123">🐙 GitHub</a>　·　
  <a href="https://liuyuanru123.github.io/">🌐 Website</a>
</p>

---

## 🙋 自己紹介

九州大学大学院 生物資源環境科学府にて、**Ton Viet Ta 准教授**指導のもと
[数理モデリング学研究室](https://www.agr.kyushu-u.ac.jp/lab/ta/members_ja.html)
に所属し、**2025 年 9 月に修士課程を修了**。学部では**応用統計学**を専攻し、
そのバックグラウンドを活かして**深層学習**による降雨予測・時系列データ
解析に取り組んできました。

研究テーマの実装にとどまらず、**Web アプリ・デスクトップアプリ**まで
含めたエンドツーエンドの開発経験を有しています。博士課程への進学を
準備中です。

## 🎓 学歴

| 期間 | 所属 |
|---|---|
| **2023.10 – 2025.09** | 修士課程修了, 九州大学大学院 生物資源環境科学府 **環境農学専攻**（数理モデリング学研究室）<br />*指導教員: Ton Viet Ta 准教授* |
| **2022.10 – 2023.09** | 研究生 (Research Student), 九州大学大学院 生物資源環境科学府 環境農学専攻（数理モデリング学研究室） |
| **2015.09 – 2019.06** | 学士 (理学), 長春大学 (中国) 理学部　応用統計学科 |

## 🏆 受賞・奨学金

- **2015 – 2018　／　長春大学** — **一等奨学金**を 3 年連続で受賞（応用統計学科）。

## 📰 最近の動向

- **2026.05** — 論文 *RainNet-MT* を *CMC – Computers, Materials & Continua* に投稿、現在査読中。
- **2026** — 博士課程プログラムへの出願準備中。
- **継続中** — 降雨予測モデル *RainNet-MT* の Web / Desktop アプリケーション開発・改良。

## 🧑‍🏫 アルバイト経験

教える経験を通じて、**数学的基礎**と教育・コミュニケーション能力を実践的に磨いてきました。理論的な深層学習研究の土台として、今後も重視している部分です。

### 📐 微分方程式 講師（院試対策）
**2022 – 2025　／　私塾**

日本の大学院入試（**院試**）レベルの **常微分方程式・偏微分方程式** を担当。
学部の標準カリキュラムを超える内容を体系的に説明する経験により、
深層学習の理論研究で必要となる **数学的基礎**（解析学・線形代数を含む）を
実践的に維持・強化。

### 🗣️ TOEIC 講師
**2022 – 2025　／　私塾**

TOEIC 受験対策を指導。語学運用力と教育・解説能力の両面を実践。
（自身の TOEIC 805 取得経験を活かす：2020 年 1 月取得。）

### 🏪 セブン-イレブン（アルバイト）
**2022 – 2025**

接客・日常業務を通じた日本語の実務経験。

## 📄 論文

### 査読中 / Under Review

1. **Yuanru Liu**, Ton Viet Ta. *RainNet-MT: A Multi-Task Deep Learning Framework for Simultaneous Rainfall Occurrence and Intensity Prediction.* Manuscript under review at *CMC – Computers, Materials & Continua*, 2026.

## 🔬 研究関心

- 深層学習・機械学習（特に**マルチタスク学習**）
- 時系列・時空間データ予測
- 応用統計学・データモデリング
- 気象データ解析

## 🎤 学会活動

- **2024.11.28 – 12.01** — [The Workshop on Interdisciplinary Sciences (WIS 2024)](https://www.agr.kyushu-u.ac.jp/lab/ta/wis2024.html) ／ 九州大学 伊都キャンパス ＋ 九重共同研修所 ／ *聴講参加*（発表なし）
- **2023.09.14 – 09.15** — [The Workshop on Interdisciplinary Sciences (WIS 2023)](https://www.agr.kyushu-u.ac.jp/lab/ta/wis2023.html) ／ 九州大学 伊都キャンパス ／ *聴講参加*（発表なし）

---

## 💻 主要プロジェクト

研究成果を**論文発表だけでなく実用化まで届ける**ことを意識しており、
同一研究テーマに対して複数のフロントエンド（Web / Desktop）を実装しています。

### 🌧️ RainNet-MT — マルチタスク深層学習による降雨予測

> 修士研究のフラッグシップ・プロジェクト。降雨の**発生有無**と**降水強度**を
> 単一モデルで同時に予測するマルチタスク深層学習フレームワークの提案・実装。
> 論文を *CMC – Computers, Materials & Continua* 誌へ投稿（査読中）。

**3 つの実装フォーム**を開発：

- 🌐 **Web アプリケーション** — [`RainNet-MT-webapp`](https://github.com/liuyuanru123/RainNet-MT-webapp)<br />
  Flask による Python バックエンドと HTML/CSS/JavaScript フロントエンドを REST API で連携。<br />
  *Python · Flask · HTML/CSS/JavaScript · PyTorch*

- 🖥️ **デスクトップアプリケーション** — [`RainNet-MT-rainfall-prediction-APP`](https://github.com/liuyuanru123/RainNet-MT-rainfall-prediction-APP)<br />
  PyQt5 によるネイティブ GUI。学習済みモデルのロード、リアルタイム推論、結果可視化を統合。<br />
  *Python · PyQt5 · PyTorch*

- 📄 **論文**（査読中）— マルチタスク学習の損失設計と気象データへの適用。

#### ☁️ AWS への本番デプロイ実装

研究を**論文だけで終わらせず**、本番想定のクラウドシステムとして実装。
**Amazon EC2** 上で **①Flask API → ②cron → ③Weather Data Fetcher → ④RainNet-MT 推論 → ⑤通知判断** の 5 段階パイプラインを稼働、
**Amazon RDS (MySQL)** に予測結果を保存。
**IoT センサー（雨量・水位・土壌）** からのリアルタイム観測と外部 Weather API (JMA / OpenWeather) を統合し、
**Amazon SNS** 経由で自前の **Web / Desktop アプリ** に降雨通知を配信、
**CloudWatch** で全プロセスをロギング。
コスト最適化のため、後に **さくらのレンタルサーバ** へ一部を移行。

`AWS EC2` · `RDS (MySQL)` · `CloudWatch` · `SNS` · `VPC` · `Flask` · `cron` · `IoT Sensors` · `Sakura Rental Server`

### 🖼️ CNN による画像分類

> PyTorch を用いた畳み込みニューラルネットワーク (CNN) の実装と学習。
> データ前処理 → モデル設計 → 学習 → 評価のエンドツーエンドな機械学習パイプライン。

[`CNN_-PyTorch-`](https://github.com/liuyuanru123/CNN_-PyTorch-) · *Python · PyTorch*

### 🧂 塩生産プロセス・モニタリング (Arduino)

> ハードウェア × 組込みシステムの練習プロジェクト。Arduino Uno で複数センサー（風速・気温・湿度・水温・電導率）を統合し、屋外塩田に設置して SD カードに記録するモニタリングシステム。

*Arduino Uno · C++ · Sensors*

---

## 🛠️ スキル

研究とエンジニアリングの両面にバランスよく取り組んでいます。

### 🔬 研究・学術系

| カテゴリ | 内容 |
|---|---|
| **機械学習・深層学習** | PyTorch · TensorFlow · Keras · scikit-learn ／ マルチタスク学習・時系列モデル・CNN・GRU・Attention |
| **データ分析・統計** | NumPy · Pandas · SciPy · statsmodels ／ 回帰分析・時系列分析・仮説検定・多変量解析・ベイズ統計 |
| **データ可視化** | Matplotlib · Seaborn |

### ⚙️ エンジニアリング・開発系

| カテゴリ | 内容 |
|---|---|
| **プログラミング言語** | **Python** (主力) · R · C / C++ · JavaScript · SQL · HTML / CSS |
| **☁️ クラウド・インフラ** | **AWS**: EC2 · RDS (MySQL) · CloudWatch · SNS · VPC ／ **JP Cloud**: さくらのレンタルサーバ ／ Linux サーバー運用 · cron · 本番デプロイ · コスト最適化 |
| **アプリ開発** | **Web**: Flask · REST API · HTML/CSS/JS ／ **Desktop**: PyQt5 ／ フロント・バックエンドの両方を一貫して開発可能 |
| **データベース・ツール** | MySQL · SQLite ／ Git · GitHub · Linux · Conda · Jupyter · VS Code |

## 🌏 言語

- **中国語** — 母語
- **日本語** — JLPT N2
- **英語** — TOEIC 805（2020 年 1 月取得）

## 📫 連絡先

- 📧 yuanruliu123@gmail.com
- 🐙 [github.com/liuyuanru123](https://github.com/liuyuanru123)
- 🌐 [liuyuanru123.github.io](https://liuyuanru123.github.io/)

---

<div align="right">
<sub><a href="README.en.md">English version →</a></sub>
</div>
