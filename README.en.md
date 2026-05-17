<div align="right">

[🇯🇵 日本語](README.md)　|　**English**

</div>

<h1 align="center">Yuanru&nbsp;Liu &nbsp;·&nbsp; <ruby>劉<rt>リュウ</rt></ruby> <ruby>淵茹<rt>エンジョ</rt></ruby></h1>

<p align="center">
  <em>M.S., Graduate School of Bioresource and Bioenvironmental Sciences, Kyushu University · Mathematical Modeling Lab (Sept 2025)</em><br />
  Deep Learning × Applied Statistics
</p>

<p align="center">
  <a href="mailto:yuanruliu123@gmail.com">📧 Email</a>　·　
  <a href="https://github.com/liuyuanru123">🐙 GitHub</a>　·　
  <a href="https://liuyuanru123.github.io/">🌐 Website</a>
</p>

---

## 🙋 About Me

I **completed my M.S. in September 2025** at the
[Mathematical Modeling Lab](https://www.agr.kyushu-u.ac.jp/lab/ta/),
Graduate School of Bioresource and Bioenvironmental Sciences, Kyushu University,
under the supervision of **Associate Professor Ton Viet Ta**. With an undergraduate
background in **Applied Statistics**, I have applied that foundation to
**deep learning** for rainfall prediction and time-series data analysis.

Beyond model development, I deliver research through **full end-to-end
implementations** — including both web and desktop applications. I am currently
preparing PhD program applications.

## 📰 News

- **May 2026** — Submitted manuscript *RainNet-MT* to *CMC – Computers, Materials & Continua*; currently under review.
- **2026** — Preparing PhD program applications.
- **Ongoing** — Continued development of the *RainNet-MT* web and desktop apps.

## 🎓 Education

| Period | Affiliation |
|---|---|
| **2023.10 – 2025.09** | M.S. completed, Mathematical Modeling Lab, Graduate School of Bioresource and Bioenvironmental Sciences, Kyushu University<br />*Advisor: Assoc. Prof. Ton Viet Ta* |
| **2022.10 – 2023.09** | Research Student, Mathematical Modeling Lab, Graduate School of Bioresource and Bioenvironmental Sciences, Kyushu University |
| **2015.09 – 2019.06** | B.S. in Science, Department of Applied Statistics, College of Science, Changchun University, China |

## 🧑‍🏫 Part-time Experience

Teaching has kept my **mathematical foundations** active while building pedagogy and communication — qualities I intend to draw on for theory-oriented deep-learning research.

### 📐 Differential Equations Instructor — Graduate-Entrance-Exam Prep
**2022 – 2025　／　Cram school**

Taught **ordinary and partial differential equations** at the level of Japanese
**graduate-school entrance exams (院試)** — content well beyond standard
undergraduate calculus. Systematically explaining this material kept the
**mathematical foundation** (analysis and linear algebra included) needed for
theory-oriented ML / DL research sharp and active.

### 🗣️ TOEIC Instructor
**2022 – 2025　／　Cram school**

Taught TOEIC preparation — practical training in both language fluency and
pedagogy. (Leveraging my own TOEIC 805 score.)

### 🌿 Git / GitHub Repository Management
**Ongoing　／　Research lab &amp; personal projects**

Continuously managed GitHub repositories for the lab&apos;s *RainNet-MT* and related projects —
branching strategy, commit discipline, conflict resolution, and multi-account SSH workflow
(personal + research).

### 🏪 7-Eleven — Part-time
**2022 – 2025**

Customer service in a Japanese-language work environment.

## 📄 Publications

### Under Review

1. **Yuanru Liu**, Ton Viet Ta. *RainNet-MT: A Multi-Task Deep Learning Framework for Simultaneous Rainfall Occurrence and Intensity Prediction.* Manuscript under review at *CMC – Computers, Materials & Continua*, 2026.

## 🔬 Research Interests

- Deep learning & machine learning (especially **multi-task learning**)
- Time series & spatiotemporal forecasting
- Applied statistics & data modeling
- Meteorological data analysis

## 🎤 Academic Activities

- **Nov 28 – Dec 1, 2024** — Attended [The Workshop on Interdisciplinary Sciences (WIS 2024)](https://www.agr.kyushu-u.ac.jp/lab/ta/wis2024.html), Kyushu University Ito Campus &amp; Kuju Training Center *(no presentation)*
- **Sep 14 – 15, 2023** — Attended [The Workshop on Interdisciplinary Sciences (WIS 2023)](https://www.agr.kyushu-u.ac.jp/lab/ta/wis2023.html), Kyushu University Ito Campus *(no presentation)*

---

## 💻 Selected Projects

I am intentional about taking research **all the way to usable software**,
implementing the same model behind multiple frontends (web + desktop) so it
can be evaluated in real workflows, not just on paper.

### 🌧️ RainNet-MT — Multi-Task Deep Learning for Rainfall Prediction

> Flagship project of my Master&apos;s work. A multi-task deep learning framework
> that jointly predicts **rainfall occurrence** and **rainfall intensity**
> from a single model. Manuscript submitted to *CMC – Computers, Materials &
> Continua* (under review).

**Three delivery forms**:

- 🌐 **Web Application** — [`RainNet-MT-webapp`](https://github.com/liuyuanru123/RainNet-MT-webapp)<br />
  Flask Python backend with HTML/CSS/JavaScript frontend, connected via a REST API.<br />
  *Python · Flask · HTML/CSS/JavaScript · PyTorch*

- 🖥️ **Desktop Application** — [`RainNet-MT-rainfall-prediction-APP`](https://github.com/liuyuanru123/RainNet-MT-rainfall-prediction-APP)<br />
  Native GUI built with PyQt5: trained-model loading, real-time inference, and result visualization.<br />
  *Python · PyQt5 · PyTorch*

- 📄 **Paper** (under review) — multi-task loss design and meteorological application.

#### ☁️ Production Deployment on AWS

Took the research **beyond a paper** and implemented a production-style cloud system.
**Amazon EC2** hosts a 5-stage pipeline: **①Flask API → ②cron → ③Weather Data Fetcher → ④RainNet-MT inference → ⑤Notification Judgement**.
**Amazon RDS (MySQL)** persists predictions.
**IoT sensors (rainfall, water-level, soil)** stream real-time observations alongside external Weather APIs (JMA / OpenWeather);
**Amazon SNS** publishes rainfall alerts to my own **Web / Desktop applications**;
**CloudWatch** logs every stage.
Later migrated parts of the stack to **Sakura Rental Server** for cost optimization.

`AWS EC2` · `RDS (MySQL)` · `CloudWatch` · `SNS` · `VPC` · `Flask` · `cron` · `IoT Sensors` · `Sakura Rental Server`

### 🖼️ CNN Image Classification

> Implementation and training of a convolutional neural network (CNN) in PyTorch:
> a full end-to-end ML pipeline covering data preprocessing, model design,
> training, and evaluation.

[`CNN_-PyTorch-`](https://github.com/liuyuanru123/CNN_-PyTorch-) · *Python · PyTorch*

### 🧂 Salt Production Monitoring (Arduino)

> A hardware &amp; embedded systems practice project. An Arduino Uno integrates several sensors (wind speed, air temperature, humidity, water temperature, conductivity) and is deployed at an outdoor salt field, logging readings to an SD card.

*Arduino Uno · C++ · Sensors*

---

## 🛠️ Skills

I work with intention across both research and engineering.

### 🔬 Research & Academic

| Category | Stack |
|---|---|
| **ML &amp; Deep Learning** | PyTorch · TensorFlow · Keras · scikit-learn ／ Multi-task learning · time-series models · CNN · GRU · Attention |
| **Data &amp; Statistics** | NumPy · Pandas · SciPy · statsmodels ／ regression · time-series · hypothesis testing · multivariate · Bayesian |
| **Visualization** | Matplotlib · Seaborn · Plotly · ggplot2 (R) |

### ⚙️ Engineering &amp; Development

| Category | Stack |
|---|---|
| **Programming Languages** | **Python** (primary) · R · C / C++ · JavaScript · SQL · HTML / CSS |
| **☁️ Cloud &amp; Infrastructure** | **AWS**: EC2 · RDS (MySQL) · CloudWatch · SNS · VPC ／ **JP Cloud**: Sakura Rental Server ／ Linux server admin · cron · production deployment · cost optimization |
| **App Development** | **Web**: Flask · REST API · HTML/CSS/JS ／ **Desktop**: PyQt5 ／ Comfortable end-to-end with both frontend &amp; backend |
| **Databases &amp; Tooling** | MySQL · SQLite ／ Git · GitHub · Linux · Conda · Jupyter · VS Code |

## 🌏 Languages

- **Chinese** — Native
- **Japanese** — JLPT N2
- **English** — TOEIC 805

## 📫 Contact

- 📧 yuanruliu123@gmail.com
- 🐙 [github.com/liuyuanru123](https://github.com/liuyuanru123)
- 🌐 [liuyuanru123.github.io](https://liuyuanru123.github.io/)

---

<div align="right">
<sub><a href="README.md">← 日本語版を見る</a></sub>
</div>
