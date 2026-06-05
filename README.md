# Category Theory Visualizer: The Hom-Functor & Natural Transformations

An interactive, step-by-step visualizer designed to build a geometric and intuitive understanding of abstract concepts in Category Theory, implemented in pure JavaScript and HTML5 Canvas.

圏論（カテゴリーセオリー）の抽象的な概念を、純粋なJavaScriptとHTML5 Canvasを用いて直感的・幾何学的に理解するためのインタラクティブな可視化ツールです。

## 🌟 Key Visual Features / 特徴

- **Induced Maps Navigation (誘導された写像の可視化)** See exactly how a morphism $f: X \to Y$ in category $\mathcal{C}$ induces a map $\text{Hom}(A, f)$ in $\mathbf{Set}$ by copying elements instead of consuming them.  
  圏 $\mathcal{C}$ における射 $f: X \to Y$ が、集合の圏 $\mathbf{Set}$ においてどのように写像 $\text{Hom}(A, f)$ を誘導するのかを、要素の「複製移動」のアニメーションを通して厳密に表現しています。

- **Micro to Macro Perspective (ミクロからマクロへのダイナミックな視点移動)** Transitions seamlessly from local element-wise mapping to a global category-wide scan. It visualizes how identity morphisms $\text{id}_A$ map to elements, how path counts multiply in free categories, and how unreachable objects result in empty sets $\emptyset$.  
  局所的な要素の動きから、カメラが引いて圏全体の構造を一括スキャンするマクロ視点へとシームレスに移行します。恒等射 $\text{id}_A$ のマッピング、自由圏における経路数（合成射）の爆発、到達不能な対象が空集合 $\emptyset$ に写る様子を数学的な整合性を保って可視化します。

- **The Yoneda Perspective (米田の補題への接続)** Designed for learners to naturally grasp the core philosophy of the Yoneda Lemma: understanding an object not in isolation, but through its entire network of relations with other objects.  
  「対象そのものではなく、他の対象との関係性の総体（射の集まり）を通してその対象を理解する」という、のちに学ぶ『米田の補題』の核心的な思想を自然に体得できるステップ構成になっています。
