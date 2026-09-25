<h1 align="center">Hi, I'm Sathvik 👋</h1>
<p align="center"><b>Deep learning for brain–computer interfaces</b> · decoding intent from EEG</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/braindecode-4B8BBE?style=flat-square" />
</p>

---

### What I work on

Motor imagery decoders work well on the person they were trained on and badly on anyone new.
I build and evaluate models on the harder question — **how well does a decoder do for a user it has never seen?**

### 🧠 Featured: [Neural Decoder — EEG Motor Imagery](https://github.com/sathvikparangi907-web/neural-decoder-eeg-motor-imagery)

Four-class motor imagery decoding on BCI Competition IV-2a, evaluated leave-one-subject-out across nine subjects.

- **HCT-Net**, a hybrid CNN–transformer I designed, benchmarked against FBCSP, EEGNet, ATCNet, EEG Conformer and CTNet
- **51.9% cross-subject accuracy** (chance = 25%) — statistically level with ATCNet and EEG Conformer
- Component ablation (V0–V5), an adversarial subject-invariant variant, Euclidean alignment
- Wilcoxon signed-rank tests with Holm–Bonferroni correction; **negative results reported, not hidden**
- Every result reproducible in one command, no GPU needed: `py phase3/report.py`

### How I work

- Measure against published baselines before claiming anything
- Change one thing at a time, select on validation, report what didn't work
- Every script ends in a self-check that fails loudly

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sathvikparangi907-web&layout=compact&hide_border=true&theme=transparent" height="140" />
</p>
