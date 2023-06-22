---
layout: default
use_math : true
---

## 研究紹介


外場によって駆動されている非平衡量子系を主な舞台として、「新奇な量子相を実現するための物理系の設計」や「非平衡状態に特有な新しい物理現象の探求」といったテーマについて理論的な研究を行っています。



### 非摂動的な効果に起因する伝導現象

絶縁体や半導体といったエネルギーギャップを持った物質では、通常は電圧を印加しても電流が流れません。しかし、電場を強くしていくと量子力学的な効果(Landau-Zenerトンネリング)によって突然大きな電流が流れ始めることが知られています。  
このトンネル効果が起こる確率は電場に関してTaylor展開できない関数形であることが知られており、電場強度に関する摂動展開がベースになっている従来の応答理論ではこの伝導現象が記述できません。我々は複素解析を応用した理論手法を用いることで、この非摂動的な効果に起因する伝導現象の従来にない新しい特徴を明らかにする研究を進めています。

#### 幾何学効果による非相反トンネリング

電子は弱い電場のもとでは断熱的に運動します(断熱定理)。その意味で、強い電場のもとで起こるトンネリング現象は、断熱性の破綻ともみなすことができます。一方、電子の断熱運動には、物質のトポロジカルな応答の起源となる幾何学位相と呼ばれるものが顔を出します。  
そこで我々はトンネリング現象への幾何学位相の寄与に着目した解析を行いました。すると、一般に空間反転対称性の破れた絶縁体においては、幾何学効果によってトンネル確率が非相反性を獲得すること、つまりは電圧の符号に応じて電流量が変化する整流性が現れることを明らかにしました。

{% include image.html url="/kitamura/images/nrlz.png" description="(a) 非相反トンネリングの概念図。空間反転対称性の破れた絶縁体では伝導帯と価電子帯で電子の重心位置がずれることがある。このずれはシフトベクトル<i>R</i>と呼ばれる幾何学的な量で表される。電場<i>E</i>のもとで電子の波数<i>k</i>が変化する過程で、価電子帯から伝導帯へ一定確率<i>P</i>で電子がすりぬける。(b) 電場<i>E</i>に関して非摂動的なトンネル確率<i>P</i>。幾何学効果により電場の正負で値が異なる。" %}


- S. Kitamura, N. Nagaosa, and T. Morimoto:
_"Nonreciprocal Landau-Zener tunneling"_,
[Commun. Phys. **3**, 63 (2020)](https://doi.org/10.1038/s42005-020-0328-0).  <!--[<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1908.00819)-->

#### トンネリング問題における非平衡定常状態

トンネリング現象における非摂動的なキャリア生成確率の計算については理論手法が確立されており、幅広い研究がなされている一方で、固体中でこのキャリアが運ぶ電流量の理論的な評価は意外にもほとんどなされていません。強い電場によって定常的なキャリア生成が起こっている状況では系が平衡状態から大きくかけ離れてしまい、緩和過程との釣り合いによって生じる非平衡定常状態を決定しなければ系の応答が計算できない困難が背景にはあります。  
我々はトンネル確率の複素解析手法と非平衡グリーン関数法を組み合わせて、フェルミオン熱浴中での定常状態を半定量的に計算する公式を導出しました。また、この定常状態では、熱浴への散逸の強さに応じて電流応答が質的に変化することや、空間反転対称性の破れとの協奏により非相反な電流・スピン流が得られうることを示しました。

{% include image.html url="/kitamura/images/dissipative.png" description="(左) 非平衡定常状態のスケッチ。電場<i>E</i>で加速された電子は確率<i>P</i>のトンネリングによって伝導帯に励起されるが、寿命<i>1/2Γ</i>を迎えると価電子帯に緩和する。この過程が絶えず起こることで定常状態が実現し、指数減衰する非対称な運動量分布<i>n<sub>+</sub></i>が実現される。(右) 得られた非平衡グリーン関数の公式。<i>f</i>はフェルミ分布関数。" %}

- S. Kitamura, N. Nagaosa, and T. Morimoto:
_"Current response of nonequilibrium steady states in Landau-Zener problem: Nonequilibrium Green's function approach"_,
[Phys. Rev. B **102**, 245141 (2020)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.245141).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/2009.03596)



### 周期駆動系における新奇量子相の設計・制御

一般に、外場によって駆動された量子系の性質を調べるためには時間依存Schrödinger方程式を直接解く必要があります。しかし系に加わる外場が周期的である場合は、ハミルトニアンが時間に関する離散的な並進対称性を持つため、それに対応する保存量を考えることができます。この保存量は駆動周波数を単位としたエネルギーの小数部分に対応しており、擬エネルギーと呼ばれています。  
Floquet理論という微分方程式の理論を応用すると、時間依存Schrödinger方程式をこの擬エネルギーの固有状態を求める問題に帰着させることができます。擬エネルギーのスペクトルを再現する有効ハミルトニアンを考えると、非平衡の問題であるにも関わらず平衡統計力学をベースにした静的な解析によって系の性質が理解できることが多々あります。この有効ハミルトニアンをうまく設計(Floquetエンジニアリング)することで様々な量子状態を実現することを目指した研究をこれまで進めてきました。

レビュー論文・解説

- T. Oka and S. Kitamura:
_"Floquet Engineering of Quantum Materials"_,
[Ann. Rev. Cond. Mat. Phys. **10**, 387-408 (2019)](https://www.annualreviews.org/doi/abs/10.1146/annurev-conmatphys-031218-013423).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1804.03212)

- Takahiro Morimoto, Sota Kitamura, and Naoto Nagaosa:  
_"Geometric aspects of nonlinear and nonequilibrium phenomena"_,  
[J. Phys. Soc. Jpn. **92**, 072001 (2023)](https://journals.jps.jp/doi/10.7566/JPSJ.92.072001).  

- 北村想太: 
"周期駆動量子系の物理",  
[物性若手夏の学校テキスト **1**, 81 (2023)](https://doi.org/10.57393/natsugaku.1.0_81).  


#### Brillouin-Wignerの摂動論の周期駆動系への応用

Floquet理論を用いた周期駆動量子系の解析にあたっては、系統的に有効ハミルトニアンを構築するフレームワークが不可欠です。有効ハミルトニアンの周波数の逆冪での級数展開はその一つですが、導出方法によって異なる級数が得られることがあります。  
これは周期振動する動的な状態を静的な状態にマップする方法が一通りでないことに起因しています。我々はBrillouin-Wignerの摂動論を周期駆動系に応用することで新しいタイプの級数展開を定式化しました。既存手法は動的な状態をユニタリ変換することで有効ハミルトニアンを得る方法になっていますが、この手法では射影を行うことで有効ハミルトニアンが得られます。このような展開手法間の関係も明確にしました。  
また、射影の選び方を工夫することで、周波数が低く逆冪展開が破綻する場合にもこのフレームワークが有用であることを、円偏光によって動的に生成されるWeyl点の振る舞いの解析を通じて実証しました。


{% include image.html url="/kitamura/images/fwsm.png" description="強度<i>A</i>の円偏光をDirac半金属に照射したときに生じるWeyl点(0,0,<i>k<sub>3</sub></i>)の軌跡を、(左)Brillouin-Wignerの摂動論を用いて計算した解析的な軌跡と、(右)数値的に計算した軌跡で比較したもの。破線のところで展開が破綻するためWeyl点どうしの結合は記述できないが、高周波展開では捉えられない無数のWeyl点の生成が記述できている。" %}

- T. Mikami, S. Kitamura, K. Yasuda, N. Tsuji, T. Oka, and H. Aoki:
_"Brillouin-Wigner theory for high-frequency expansion in periodically driven systems: Application to Floquet topological insulators"_,
[Phys. Rev. B **93**, 144307 (2016)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.93.144307).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1511.00755)
- L. Bucciantini, S. Roy, S. Kitamura, and T. Oka:
_"Emergent Weyl nodes and Fermi arcs in a Floquet Weyl semimetal"_,
[Phys. Rev. B **96**, 041126\(R\) (2017)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.96.041126).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1612.01541)

#### 周期駆動された強結合電子系における新奇量子相

上に述べた周期数の逆冪での展開には量子系の典型的なエネルギーが光子のエネルギーより低いことが必要です。電子間に強い相互作用が働いているモット絶縁体ではこの条件を満たすことは難しく、むしろ応用上は電荷ギャップよりも小さい周波数での駆動に興味がもたれます。  
我々は相互作用の逆冪での展開(強結合展開)を周期駆動系に拡張することで、このような状況にも応用できる有効ハミルトニアンの系統的な構築方法を確立しました。この理論を応用するとモット絶縁体のスピン自由度を電場でコントロールすることができます。  
また、引力Hubbard模型で強い引力によりBEC型の超伝導状態が実現している状況にもこの理論を応用しました。Hubbard模型はη-SU(2)対称性と呼ばれる隠れた対称性のために引力模型と斥力模型が数学的に等価になることが知られていますが、電場を印加するとこの対称性が破れ、引力系に特有な非平衡現象が現れることを見出しました。

{% include image.html url="/kitamura/images/sce.png" description="(a) 周期駆動系の強結合展開における仮想遷移。電子がホッピングする際に光子の吸収や放出が起こる。(b) 駆動された引力Hubbard模型の相図。クーパー対のホッピング<i>J</i>と対間の斥力<i>V</i>の実効的な値が外場<i>A</i>の影響で赤い線に沿って変化し、ηペアリング超伝導と呼ばれる特殊な超伝導状態が実現する(実線と破線は駆動周波数が異なる)。<i>s</i>-SC:
通常の<i>s</i>波超伝導、CDW:電荷密度波、η-SC:ηペアリング超伝導、PS:相分離。" %}

- S. Kitamura, T. Oka, and H. Aoki:
_"Probing and controlling spin chirality in Mott insulators by circularly polarized laser"_,
[Phys. Rev. B **96**, 014406 (2017)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.96.014406).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1703.04315)
- S. Kitamura and H. Aoki:
_"$\eta$-pairing superfluid in periodically-driven fermionic Hubbard model with strong attraction"_,
[Phys. Rev. B **94**, 174503 (2016)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.174503).  [<i class="ai ai-arxiv ai-lg" title="arXiv"></i>](https://arxiv.org/abs/1511.07890)
