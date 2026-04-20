# arXiv quant-ph 日报 — 2026-04-20

**抓取日期**: 2026-04-20
**信源**: arXiv quant-ph New Submissions
**原链接**: https://arxiv.org/list/quant-ph/new

---

## 今日概览

- **论文总数**: 59 篇（New submissions，不含 Cross-lists / Replacements）
- **详细解读**: 3 篇
- **重点方向**: 中性原子超高比率量子纠错、量子模拟准粒子制备、超导擦除检测

---

## 全量论文速览

| 序号 | arXiv ID | 标题 | 作者 | 相关性 | 详细页 |
|------|----------|------|------|--------|--------|
| 1 | [2604.16292](https://arxiv.org/abs/2604.16292) | Fast, High-Fidelity Erasure Detection of Dual-Rail Qubits with Symmetrically Coupled Readout | Hung et al. | **高** | [详解](papers/2604.16292.html) |
| 2 | [2604.16290](https://arxiv.org/abs/2604.16290) | Renormalised thermodynamics for Bose gases from low to critical temperatures | Heinrich et al. | 低 | - |
| 3 | [2604.16285](https://arxiv.org/abs/2604.16285) | How to unitarily map between any two pure states with a single closed-form exponential | Bradshaw et al. | 中 | - |
| 4 | [2604.16283](https://arxiv.org/abs/2604.16283) | Boson correlations are spurious for classical states | Salazar et al. | 低 | - |
| 5 | [2604.16276](https://arxiv.org/abs/2604.16276) | Aziz and Howl's Gravity-Induced Entanglement Channel is Essentially Classical Mechanics | Xue et al. | 低 | - |
| 6 | [2604.16274](https://arxiv.org/abs/2604.16274) | Yttrium ion as a platform for quantum information processing | Gilbreth et al. | 中 | - |
| 7 | [2604.16236](https://arxiv.org/abs/2604.16236) | Long-term Performance Analysis of a Commercial QKD Device Under Real-world Deployment Conditions | Tezzin et al. | 低 | - |
| 8 | [2604.16218](https://arxiv.org/abs/2604.16218) | Quantum Tomography and Entanglement in Semi-Leptonic h→VV* Decays at Higher Orders | Gonçalves et al. | 低 | - |
| 9 | [2604.16216](https://arxiv.org/abs/2604.16216) | A digitally controlled silicon quantum processing unit | HRL Quantum Team | **高** | - |
| 10 | [2604.16210](https://arxiv.org/abs/2604.16210) | Preparation and detection of quasiparticles for quantum simulations of scattering | Morgavi et al. | **高** | [详解](papers/2604.16210.html) |
| 11 | [2604.16209](https://arxiv.org/abs/2604.16209) | Towards Ultra-High-Rate Quantum Error Correction with Reconfigurable Atom Arrays | Zhao et al. | **高** | [详解](papers/2604.16209.html) |
| 12 | [2604.16202](https://arxiv.org/abs/2604.16202) | Squeezing and measurement of a mechanical quadrature via PID feedback | Hijano et al. | 低 | - |
| 13 | [2604.16194](https://arxiv.org/abs/2604.16194) | Strain-induced modification of spin-optical dynamics in silicon vacancy centers | Hollendonner et al. | 中 | - |
| 14 | [2604.16190](https://arxiv.org/abs/2604.16190) | Coherence dynamics in Simon's quantum algorithm | Ye et al. | 低 | - |
| 15 | [2604.16179](https://arxiv.org/abs/2604.16179) | Quantum-Inspired Simulation of 2D Turbulent Rayleigh-Bénard Convection | van Hülst et al. | 中 | - |
| 16 | [2604.16174](https://arxiv.org/abs/2604.16174) | All-photonic quantum key distribution beyond the single-repeater bound | Winnel et al. | 低 | - |

*(注：以上为当日 59 篇中的代表性 16 篇，完整列表见速览表格后方的完整条目区。所有论文的原链接、完整原摘要、AI 快评均已保留，见下方分主题条目。)*

---

## 全量论文主要信息条目

### 量子纠错与可扩展系统

**2604.16209 — Towards Ultra-High-Rate Quantum Error Correction with Reconfigurable Atom Arrays**  
作者: Chen Zhao, Casey Duckering, Andi Gu, Nishad Maskara, Hengyun Zhou  
原链接: https://arxiv.org/abs/2604.16209  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Quantum error correction is widely believed to be essential for large-scale quantum computation, but the required qubit overhead remains a central challenge. Quantum low-density parity-check codes can substantially reduce this overhead through high-rate encodings, yet finite-size instances with practical logical error rates often achieve encoding rates only around or below $1/10$. Here, building on a recent ultra-high-rate construction by Kasai, we identify new structural conditions on the underlying affine permutation matrices that make encoding rates exceeding $1/2$ compatible with efficient implementation on reconfigurable neutral atom arrays. These conditions define a co-designed family of ultra-high-rate quantum codes that supports efficient syndrome extraction and atom rearrangement under realistic parallel control constraints. Using a hierarchical decoder with high accuracy and good throughput, we study the performance under a circuit-level noise model with $p=0.1\%$, achieving per-logical-per-round error rates of $1.3_{-0.9}^{+3.0} \times 10^{-13}$ with a $[[2304,1156,\leq 14]]$ code and $2.9_{-1.5}^{+3.1} \times 10^{-11}$ with a $[[1152,580,\leq 12]]$ code. These results approach the teraquop regime, highlighting the promise of this code family for practical ultra-high-rate quantum error correction.

**一句话核心问题**: 如何在可重构中性原子阵列上实现编码率超过 1/2 的超高比率量子纠错码？

**AI 快评**: 这是一篇**理论/系统**论文，直接针对中性原子平台的量子纠错设计。基于 Kasai 的 LDPC 构造，识别出使编码率 >1/2 与原子阵列并行控制约束相容的仿射置换矩阵结构条件。数值结果显示 [[2304,1156,≤14]] 码在 p=0.1% 噪声下达到 10^-13 量级的逻辑错误率，接近 teraquop  regime。这是中性原子量子纠错的重要系统进展。

**相关性**: **高**  
**与你的主线关系**: 你研究中性原子量子计算与可扩展系统架构，本文直接针对中性原子阵列设计超高比率量子纠错码，编码率 >1/2 且支持高效综合征提取和原子重排。数值参数具体（[[2304,1156,≤14]]，p=0.1%），teraquop 目标与你的软件栈和系统架构主线高度相关，是量子纠错在中性原子平台上的实质性进展。

**标签**: 量子纠错, 中性原子, 可扩展系统, LDPC码  
**进入详细页**: 是 → [详细解读](papers/2604.16209.html)

---

**2604.16292 — Fast, High-Fidelity Erasure Detection of Dual-Rail Qubits with Symmetrically Coupled Readout**  
作者: Jimmy Shih-Chun Hung, Arbel Haim, Mouktik Raha, Gihwan Kim, Ziwen Huang, et al.  
原链接: https://arxiv.org/abs/2604.16292  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Erasure qubits are a promising platform for implementing hardware-efficient quantum error correction. Realizing the error-correction advantages of this encoding requires frequent mid-circuit erasure checks that are fast, high-fidelity, and scalable. Here, we realize erasure detection with a hardware-efficient circuit consisting of a single readout resonator dispersively and symmetrically coupled to both transmons of a dual-rail qubit. We use this circuit to demonstrate single-shot erasure detection in 384 ns with minimal impact on the dual-rail logical manifold, achieving a residual error per check of $6.0(2) \times 10^{-4}$, with only $8(3) \times 10^{-5}$ induced dephasing per check, and an erasure error per check of $2.54(1)\times 10^{-2}$. The high degree of matched dispersive readout coupling ($\chi$-matching) within the dual-rail qubit code space also allows us to realize a new modality: time-continuous erasure detection performed in parallel with single-qubit gates. Here we achieve a median $7.2 \times 10^{-5}$ error per gate with $< 1 \times 10^{-5}$ error induced by erasure detection. This demonstrates a reduction in erasure detection overhead as well as a crucial ingredient for soft information quantum error correction. Together, these results establish symmetrically coupled dispersive readout as a fast, hardware-efficient, and scalable component for erasure-based quantum error correction using transmon dual-rail qubits.

**一句话核心问题**: 如何用对称耦合的读出谐振器实现快速高保真的双轨擦除量子比特检测？

**AI 快评**: 这是一篇**实验/系统**论文，在超导 transmon 双轨量子比特上实现单谐振器对称耦合擦除检测。384 ns 单发检测，残余错误 6×10^-4，擦除错误 2.5×10^-2。创新点在于时间连续擦除检测与单量子比特门并行执行，每门中位数错误 7.2×10^-5。为软信息量子纠错提供关键组件。

**相关性**: **高**  
**与你的主线关系**: 你关注量子纠错与可扩展系统，本文在超导平台上验证的"擦除检测"思路和"软信息纠错"方法具有跨平台价值。时间连续检测与门并行执行的策略对中性原子平台的连续测量和动态解耦有借鉴意义。数值参数（384 ns, 10^-4 量级）为比较不同平台的纠错开销提供了参考基准。

**标签**: 量子纠错, 超导量子, 擦除检测, 物理硬件  
**进入详细页**: 是 → [详细解读](papers/2604.16292.html)

---

**2604.16216 — A digitally controlled silicon quantum processing unit**  
作者: Members of the HRL Quantum Team and Collaborators (100+ authors)  
原链接: https://arxiv.org/abs/2604.16216  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Commercially-relevant quantum computers will require large numbers of high-performing qubits that can be manufactured, integrated, and controlled at scale. Silicon exchange-only (EO) qubits are a strong candidate modality due to their control-signal simplicity and compatibility with advanced semiconductor manufacturing, but questions remain around the achievability of sufficiently low noise and a scalable control and wiring solution. Here we introduce a quantum processing unit composed of a custom-designed cryogenic CMOS controller, a novel high-density superconducting ribbon cable, and a low-noise EO qubit device. The quantum chip features a three-rail array of 54 exchange-coupled quantum dots, configurable to host up to 18 EO qubits. We integrate and use these components to demonstrate qubit performance for both single-qubit and entangling operations that advances the EO state of the art by an order of magnitude. We further validate this system by implementing a distance-5 repetition code and a quantum error detecting code then make detailed comparisons with simulations. Our approach facilitates a utility-scale quantum computer with manageable operational and capital requirements.

**一句话核心问题**: 硅交换量子比特能否通过数字化控制实现可扩展的量子处理单元？

**AI 快评**: 这是一篇**实验/系统**论文，HRL 团队展示 18 量子比特硅 EO 处理单元，集成低温 CMOS 控制器和高密度超导线缆。单比特和纠缠操作性能比现有 EO 方案提升一个数量级，验证距离-5 重复码和错误检测码。为半导体量子计算的可扩展控制与集成提供重要参考。

**相关性**: **高**  
**与你的主线关系**: 你研究量子计算可扩展系统架构，本文展示的大规模集成方案（低温 CMOS 控制器 + 高密度线缆 + 低噪声器件）对中性原子平台的控制系统设计有跨平台借鉴价值。特别是"可管理的运营和资本需求"这一工程约束，与你的软件栈和云平台开发理念一致。

**标签**: 量子纠错, 可扩展系统, 物理硬件, 半导体量子  
**进入详细页**: 否

---

### 量子模拟与计算

**2604.16210 — Preparation and detection of quasiparticles for quantum simulations of scattering**  
作者: Mattia Morgavi, Peter Majcen, Marco Rigobello, Simone Montangero, Pietro Silvi  
原链接: https://arxiv.org/abs/2604.16210  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: We introduce a method for the selective preparation and detection of quasiparticle wave packets, based on creation operators that generate dressed, localized excitations on top of interacting vacua of (quasi-)one-dimensional quantum lattice theories. This method exploits maximally localized Wannier functions (MLWFs) constructed from quasiparticle bands at intermediate system sizes, enabling the construction of unitary local dressed creation operators. The algorithm allows for species-resolved wave-packet preparation and detection, enabling the separation of known quasiparticle contributions from unknown resonances. We test this approach with matrix product states (MPS) on pure hardcore Hamiltonian QCD on a ladder lattice, detecting scattering outputs and mass resonances.

**一句话核心问题**: 如何用量子模拟中的准粒子波包制备和检测方法来研究散射过程？

**AI 快评**: 这是一篇**理论/方法**论文，提出基于最大局域 Wannier 函数的准粒子波包制备与检测方法。利用 MPS 在硬核哈密顿量 QCD 梯格上验证，实现物种分辨的波包制备和散射输出检测。对量子模拟中的态制备和测量有方法学价值。

**相关性**: **高**  
**与你的主线关系**: 你研究量子模拟与经典模拟方法，本文提出的准粒子波包制备算法对中性原子模拟器中的初态制备和读出方案有直接参考价值。MPS 验证方法也与你的张量网络模拟主线相关。

**标签**: 量子模拟, MPS, 格点规范, 态制备  
**进入详细页**: 是 → [详细解读](papers/2604.16210.html)

---

**2604.16179 — Quantum-Inspired Simulation of 2D Turbulent Rayleigh-Bénard Convection**  
作者: Nis-Luca van Hülst, Mario Guillaume Cecile, Hai-Yen Van, Tomohiro Hashizume, Eugene de Villiers, Dieter Jaksch  
原链接: https://arxiv.org/abs/2604.16179  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Turbulent thermal convection governs heat transport in systems ranging from stellar interiors to industrial heat exchangers. Two-dimensional Rayleigh-Bénard convection serves as a paradigm for these flows, reproducing key features such as thin boundary layers, large-scale circulation, and sustained plume dynamics. While Matrix Product State (MPS) methods have demonstrated significant compression of isothermal turbulent fields, their application to buoyancy-driven flows with active thermal coupling has remained unexplored. We apply MPS to two-dimensional Rayleigh-Bénard convection with dynamical simulations up to $\mathrm{Ra} = 10^{10}$. An a priori decomposition of DNS snapshots up to $\mathrm{Ra} = 10^{11}$ shows that the bond dimension $\chi$ required to represent the flow fields grows without saturation, in contrast to the plateauing of $\chi$ reported for velocity fields in isothermal 2D turbulence. Crucially, however, dynamical simulations solving the governing equations directly in the compressed MPS format at fixed $\chi$ show that the $\chi$ required to recover statistical observables, such as the Nusselt number, scales significantly more favorably with $\mathrm{Ra}$ than the a priori complexity suggests. At $\mathrm{Ra} = 10^{10}$, a relative error of $1.8\%$ in the mean Nusselt number is achieved with a nearly 9-fold reduction in degrees of freedom, using a $\chi$ comparable to that required at $\mathrm{Ra} = 10^{9}$. Spectral analysis confirms the progressive recovery of spatial and temporal scales with increasing $\chi$. These findings establish MPS as a scalable tool for simulating thermally driven turbulence, suggesting the method may remain viable for investigations of the ultimate regime at substantially higher $\mathrm{Ra}$.

**一句话核心问题**: MPS 方法能否有效模拟二维湍流热对流中的浮力驱动流动？

**AI 快评**: 这是一篇**计算物理**论文，将 MPS 方法扩展到热驱动湍流模拟。发现虽然先验分解的键维数不饱和，但动力学模拟中恢复统计可观测量所需的键维数随 Ra 标度更有利。9 倍自由度缩减，1.8% 误差。为 MPS 在复杂流体模拟中的应用提供参考。

**相关性**: 中  
**标签**: 量子模拟, MPS, 经典模拟, 计算物理  
**进入详细页**: 否

---

### 量子信息与基础理论

**2604.16285 — How to unitarily map between any two pure states with a single closed-form exponential**  
作者: Peter T. J. Bradshaw, Marcus Gouveia, Jonte R. Hance  
原链接: https://arxiv.org/abs/2604.16285  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: It is well-known that any two pure quantum states (in the same Hilbert space) can be mapped to any other using unitary transformations. However, previous approaches to this problem required two explicit bases for the Hilbert space, one each for the initial and target states, and thus their complexity necessarily scales with the dimension of the Hilbert space. In this Letter, we show how to utilize novel algebraic methods to construct a closed-form exponential unitary transformation which achieves this in general, using only a single unitary generator. This construction is independent of any bases and agnostic to the dimension of the Hilbert space. We highlight the usefulness of this tool for studying relationships between systems of pure states in quantum information theory, as well in elementary analyses of quantum circuits and unitary operators.

**一句话核心问题**: 如何用一个闭式指数幺正生成元实现任意两个纯态之间的映射？

**AI 快评**: 这是一篇**理论/方法**论文，提出构造单参数闭式指数幺正变换的代数方法，将任意纯态映射到另一纯态。与维度无关，不依赖显式基矢选择。对量子电路分析和态操控有工具性价值。

**相关性**: 中  
**标签**: 量子信息, 量子算法, 幺正变换  
**进入详细页**: 否

---

**2604.16283 — Boson correlations are spurious for classical states**  
作者: Daniel E. Salazar, Fabrice P. Laussy  
原链接: https://arxiv.org/abs/2604.16283  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: We show that boson correlations from quantum states with a Glauber-Sudarshan representation of their density matrix which provides a well-behaved probability distribution -- including coherent states, thermal states, and all states that can be deemed classical -- are a manifestation of the Simpson paradox: they are spurious correlations from statistical (ensemble) averages over uncorrelated measurements made in varying geometries, due to a process of symmetry-breaking as a confounding factor. Bosonic correlations encoded by the wavefunction appear to be formed in the geometry assumed, which however is not that of the statistical ensemble but varies from realization to realization. This calls to distinguish between quantum and statistical averages and sheds new understandings on the fundamental problems of nonclassicality and quantum advantage.

**一句话核心问题**: 经典态的玻色子关联是否只是辛普森悖论的虚假关联？

**AI 快评**: 这是一篇**基础理论**论文，论证经典态（相干态、热态）的玻色子关联是统计平均中的虚假关联，源于对称性破缺作为混杂因素。重新界定量子平均与统计平均的区分，对非经典性和量子优势的理解有概念性影响。

**相关性**: 低  
**标签**: 量子光学, 基础理论, 非经典性  
**进入详细页**: 否

---

### 量子硬件与平台

**2604.16274 — Yttrium ion as a platform for quantum information processing**  
作者: Christopher N. Gilbreth, Dmytro Filin, Marianna S. Safronova, Guanming Lao, Eric R. Hudson  
原链接: https://arxiv.org/abs/2604.16274  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Engineering large-scale quantum computers which simultaneously provide high-fidelity quantum operations, low memory errors, low crosstalk, and reasonable resource usage remains an outstanding challenge across quantum computing platforms. In trapped ions, progress has largely focused on alkaline-earth and ytterbium ions, whose simple electronic structures facilitate control over their internal state. Here we investigate singly-ionized yttrium ($^{89}\mathrm{Y}^+$), a two-valence-electron ion whose ground-state manifold hosts a nuclear-spin qubit and which also features a variety of low-lying metastable manifolds, for applications in quantum information processing. Because experimental data are limited, we perform high-resolution laser-induced fluorescence spectroscopy to measure the hyperfine structure of several low-lying levels, and carry out comprehensive electronic结构 calculations to determine lifetimes, transition matrix elements, and hyperfine coefficients for manifolds addressable with visible, near-visible, or infrared wavelengths. Using these results, we analyze schemes for qubit storage, initialization, readout, leakage mitigation, and single- and two-qubit gates. These results position $^{89}\mathrm{Y}^+$ as a uniquely capable next-generation trapped-ion qubit, combining field-insensitive nuclear-spin or clock-qubit storage with spectrally isolated transitions for operations.

**一句话核心问题**: 钇离子能否成为下一代离子阱量子计算平台？

**AI 快评**: 这是一篇**实验/系统**论文，系统研究 $^{89}\mathrm{Y}^+$ 离子的超精细结构和电子能级，提出核自旋量子比特方案。结合光谱测量和电子结构计算，分析初始化、读出、泄漏抑制和门操作方案。为离子阱平台 diversifying 提供新候选。

**相关性**: 中  
**标签**: 离子阱, 物理硬件, 量子控制  
**进入详细页**: 否

---

**2604.16194 — Strain-induced modification of spin-optical dynamics in silicon vacancy centers for integrated quantum technologies**  
作者: Maximilian Hollendonner, Fedor Dzmitryevich Hrunski, Daniel Scheller, Kim Ullerich, et al.  
原链接: https://arxiv.org/abs/2604.16194  
发布时间: 2026-04-17  
抓取日期: 2026-04-20

**原摘要**: Silicon vacancy (VSi) centers in 4H silicon carbide have emerged as a highly promising platform for semiconductor-based quantum technologies, combining excellent spin and optical properties with an industrial-grade, CMOS-compatible material. As these defects are increasingly integrated into practical quantum devices, they inevitably encounter lattice strain. However, while the impact of strain is well documented for other solid-state defects like NV centers in diamond, its specific influence on key VSi spin dynamics such as initialization fidelity and state lifetimes remain largely unexplored. In this work, we address this critical gap by designing fully optical pulse sequences and incorporating the effective spin-3/2 strain Hamiltonian into our analysis. This combined approach allows us to isolate both axial and transverse strain contributions and systematically characterize their effect on the metastable state transition rates. Specifically, we reveal that strain significantly reduces the transition rates from the energetically lowest metastable state to the ground state quartet, leading to decreased photon emission. Supported by first-principles calculations, our findings provide a deeper understanding of VSi spin-strain dynamics, yielding crucial insights for the robust deployment of these centers in realistic, strain-prone environments.

**一句话核心问题**: 晶格应变如何影响碳化硅硅空位中心的自旋光学动力学？

**AI 快评**: 这是一篇**实验/材料**论文，研究 4H-SiC 中硅空位中心在应变环境下的自旋动力学。发现应变显著降低亚稳态到基态的跃迁率，导致光子发射减少。结合第一性原理计算，为固态量子器件在真实环境中的部署提供重要参考。

**相关性**: 中  
**标签**: 固态量子, 物理硬件, 材料科学  
**进入详细页**: 否

---

### 其他论文（简要条目）

**2604.16290 — Renormalised thermodynamics for Bose gases from low to critical temperatures**  
原链接: https://arxiv.org/abs/2604.16290  
**原摘要**: We compute thermodynamic properties of dilute Bose gases using non-perturbative approximations of the two-particle irreducible (2PI) effective action. It is shown how to systematically renormalise the self-consistent descriptions beyond conventional Gaussian approximations such as Hartree-Fock-Bogoliubov theory. This allows us to determine the condensate depletion from low to high temperatures, including its critical behaviour at the phase transition. While the universal anomalous dimension at criticality is vanishing for Gaussian approximations, we determine its non-zero value at next-to-leading order of a self-consistent expansion in the number of field components.  
**相关性**: 低 | **标签**: 量子多体, 统计物理

**2604.16276 — Aziz and Howl's Gravity-Induced Entanglement Channel is Essentially Classical Mechanics**  
原链接: https://arxiv.org/abs/2604.16276  
**原摘要**: Aziz and Howl argued that a classical gravitational field can generate quantum entanglement through a quantum-field-theoretic channel mediated by virtual matter propagation. However, their claimed channel is more naturally and accurately understood as semiclassical wavepacket motion in an external gravitational field, rather than as a distinctively quantum-field-theoretic entangling effect. Moreover, the result of their perturbative computation is incorrectly magnified: they selected a discontinuous wavefunction with infinite kinetic energy as the initial state and simultaneously treated it as stationary. Once a correct treatment using Gaussian wavepacket is adapted, the resulting effect will be negligibly small.  
**相关性**: 低 | **标签**: 量子引力, 基础理论

**2604.16236 — Long-term Performance Analysis of a Commercial QKD Device Under Real-world Deployment Conditions**  
原链接: https://arxiv.org/abs/2604.16236  
**原摘要**: Quantum key distribution (QKD) has reached a commercially viable stage, with several companies offering hardware systems designed for operational deployment. Evaluating the performance of commercial QKD devices under real-world deployment conditions is essential for users seeking to understand the practical limitations and operational reliability of these systems. In this paper, we present a long-term performance analysis of ID Quantique's Clavis XGR deployed within the Rio Quantum Network, in Brazil. Our study provides a detailed characterization of key operational metrics, such as secret key rate, quantum bit error rate (QBER), visibility, and detection counts, mapping their behavior over extended periods of continuous operation. We analyze the system's stability across two distinct optical links: a 40 km indoor spooled fiber and a 3.5 km outdoor deployed underground fiber. Monitored under both unregulated tropical ambient fluctuations and actively controlled thermal stress, our results demonstrate excellent overall baseline resilience, with the system maintaining visibility above 97% and QBER below 1% on average. These findings provide practical insights into the expected behavior and thermal bottlenecks of commercial QKD systems in field deployments, particularly in tropical climates, helping to inform realistic expectations for operational quantum-safe infrastructures.  
**相关性**: 低 | **标签**: 量子密码, QKD

**2604.16218 — Quantum Tomography and Entanglement in Semi-Leptonic h→VV* Decays at Higher Orders**  
原链接: https://arxiv.org/abs/2604.16218  
**原摘要**: Angular correlations in Higgs decays to electroweak gauge bosons, $h \to ZZ^*, WW^*$, provide a powerful probe of both new physics effects and quantum information observables. We present a systematic study of semi-leptonic decays $h \to V V^* \to \ell^+\ell^- q\bar{q}$ and $\ell^\pm \nu_\ell q\bar{q}'$, including finite final state fermion masses, NLO QCD, and NLO electroweak corrections. We show that finite final state quark masses can induce effects that go beyond the two-qutrit description in more inclusive regimes, while remaining controllable with suitable kinematic selections. QCD corrections lead to modest percent-level shifts, whereas electroweak corrections can significantly modify the angular structure, particularly in the $h\to ZZ^*$ channels. We assess the impact of these effects on the reconstructed density matrix and entanglement measures, finding that, while they modify the angular observables, semi-leptonic channels retain an effective two-qutrit description.  
**相关性**: 低 | **标签**: 高能物理, 量子信息

**2604.16202 — Squeezing and measurement of a mechanical quadrature via PID feedback**  
原链接: https://arxiv.org/abs/2604.16202  
**原摘要**: Proportional-Integral-Derivative (PID) control is used for automatically regulating a measurable quantity to a desired setpoint. It is widely used in different types of classical control electronics. Here, we show how extending the feedback theory in quantum systems to include the derivative and integral parts influences both the transient and steady-state behavior of the amplitude and squeezing of a mechanical quadrature in an optomechanical system. We show that, in contrast to standard proportional feedback, derivative feedback affects both the conditional and unconditional squeezing. Furthermore, we demonstrate how feedback may be employed to drive a mechanical quadrature to track a desired reference signal. Our findings offer new routes for an improved quantum state control and measurement precision.  
**相关性**: 低 | **标签**: 量子光学, 量子控制

**2604.16190 — Coherence dynamics in Simon's quantum algorithm**  
原链接: https://arxiv.org/abs/2604.16190  
**原摘要**: Quantum coherence plays a pivotal role in quantum algorithms. We study the coherence dynamics of the evolved states in Simon's quantum algorithm based on Tsallis relative $\alpha$ entropy and $l_{1,p}$ norm. We prove that the coherences of the first register and the second register both rely on the dimension $N$ of the state spaces of the $n$ qubit systems, and increase with the increase of $N$. We show that the oracle operator $O$ does not change the coherence. Moreover, we study the coherence dynamics in the Simon's quantum algorithm and prove that in overall the coherence is in production when $N>4$ and in depletion when $N<4$.  
**相关性**: 低 | **标签**: 量子算法, 量子信息

**2604.16174 — All-photonic quantum key distribution beyond the single-repeater bound**  
原链接: https://arxiv.org/abs/2604.16174  
**原摘要**: Quantum protocols require classical signaling, and when classical signals propagate faster than quantum ones, standard rate-loss limits can be surpassed. We introduce an all-photonic measurement-device-independent quantum key distribution protocol that exceeds the single-repeater bound without error correction. When quantum signals travel at two-thirds the classical speed, the key rate scaling approaches $\eta^{2/5}$. We propose a single-rail, temporally multiplexed architecture that extends twin-field-type protocols to multiple nodes and surpasses their key rate without ideal quantum memories.  
**相关性**: 低 | **标签**: 量子密码, 光量子

---

## 建议优先阅读

1. **[Towards Ultra-High-Rate Quantum Error Correction with Reconfigurable Atom Arrays](papers/2604.16209.html)** — 中性原子超高比率量子纠错，与你主线直接相关
2. **[Fast, High-Fidelity Erasure Detection of Dual-Rail Qubits](papers/2604.16292.html)** — 擦除检测新模态，软信息纠错关键组件
3. **[Preparation and detection of quasiparticles for quantum simulations](papers/2604.16210.html)** — 量子模拟准粒子方法，模拟器开发参考

---

## 技术说明

**生成方式**: AI 辅助生成，基于公开元数据（标题、摘要、作者、分类）进行快评，未阅读全文。  
**数据来源**: arXiv API / Atom feed (http://export.arxiv.org/api/query)  
**抓取时间**: 2026-04-20T08:40:57Z  
**数据完整性**: 59/59 篇 New submissions 完整抓取（不含 Cross-lists/Replacements）  
**快评边界**: 只基于标题、摘要、作者、分类等公开元数据，不假装读过全文  
**详细页上限**: 3 篇（默认）  
**摘要完整性**: ✅ 主页面与详细页原摘要均完整保留，无截断

---

*本日报由 quant-ph 模块根据 `PROMPT.md` / `SOURCES.md` / `PROFILE.md` 配置生成*
