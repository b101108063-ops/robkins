---
layout: single
title: "Chapter 01: The Cell as a Unit of Health and Disease"
---

# Chapter 1: The Cell as a Unit of Health and Disease

## Chapter 1 導讀

本章是全書的基礎，介紹構成人體的基本單位——細胞。細胞既是健康的基礎，也是疾病的起點。內容涵蓋三個核心面向：首先，基因體（genome）的結構與調控——從 DNA 序列、chromatin 組織、histone 修飾，到 microRNA、lncRNA 的基因調控機制，以及新興的 CRISPR 基因編輯技術；其次，細胞的基礎 housekeeping 功能——包括各胞器的結構與職責、plasma membrane 的運輸機制、cytoskeleton 的支撐與運動功能、cell-cell interaction 的連接結構；最後，細胞的老化（cellular aging）與 senescence 機制。理解這些基本概念，是深入學習後續各系統病理的必備台階。

---

## The Genome

### DNA 的結構與功能

人類基因體大約含有 30 億個鹼基對（base pairs），編碼約 20,000 個蛋白質基因。值得注意的是，人類基因體中只有約 1.5% 的序列實際轉譯為蛋白質，其餘絕大部分（約 80%）屬於調控區域，負責基因表現的時空控制。

DNA 以雙股螺旋（double helix）形式存在，每一股由核苷酸（nucleotide）組成，包含一個五碳糖、一個磷酸基團，以及四種鹼基——adenine（A）、thymine（T）、guanine（G）、cytosine（C）。A 與 T 以兩個氫鍵配對，G 與 C 以三個氫鍵配對，這種互補配對原則是 DNA 複製與轉錄的基礎。

### 染色質的組織

在細胞核中，DNA 並非游離存在，而是與 histone 蛋白質緊密結合，形成 nucleosome 結構——147 個鹼基對繞著由四種 histone（H2A、H2B、H3、H4 各兩個）組成的八聚體核心纏繞約 1.8 圈。Nucleosome 是 chromatin 的基本單位。

Chromatin 以兩種形式存在：
- **Heterochromatin**：結構緻密，轉錄活性低，主要分布於核膜邊緣及著絲粒（centromere）周圍
- **Euchromatin**：結構較為鬆散，轉錄活性高，是基因表現活躍的區域

這種動態轉換決定了哪些基因被「開啟」或「關閉」，是細胞分化（differentiation）的分子基礎。

### 基因變異的形式

兩個個體之間的 DNA 序列差異小於 0.5%，但這不到 1500 萬個鹼基的差異決定了所有人的獨特性以及疾病易感性。最常見的兩種變異形式為：

- **單核苷酸多態性（SNP）**：在特定位置上只有兩種鹼基選項（如 A 或 T）。大多數 SNP 位於非編碼區，可影響基因調控進而與疾病相關。
- **拷貝數變異（CNV）**：大片段 DNA（1000 鹼基對至數百萬鹼基對）重複或缺失，約有一半的 CNV 涉及基因編碼序列，可能導致顯著的表型差異。

---

## Epigenetics and Chromatin Regulation

### Epigenetics 的概念

Epigenetics（表觀遺傳學）是指不改變 DNA 序列本身，卻能穩定遺傳的基因表現變化。這些變化解釋了為何具有相同基因組的細胞（如肝細胞與神經元）可以有截然不同的功能，也能解釋同卵雙胞胎隨年齡增長而出現差異的原因。

### DNA 甲基化

DNA 甲基化（methylation）是最重要的表觀遺傳機制之一。在 gene regulatory elements（如 promoter）上的高甲基化通常導致 chromatin 凝縮與轉錄沉默。DNA 甲基化由 methyltransferase 催化，並可被 demethylating enzyme 逆轉。異常的甲基化模式與癌症、神經退化疾病等多種病理狀態密切相關。

### Histone 修飾

Nucleosome 並非靜態結構，而是受多種後轉譯修飾（post-translational modification）動態調控：

- **乙醯化（Acetylation）**：由 histone acetyltransferase（HAT）催化，通常使 chromatin 結構鬆開，促進轉錄；由 histone deacetylase（HDAC）逆轉，導致基因沉默。HDAC 抑制劑已用於癌症治療。
- **甲基化（Methylation）**：取決於被修飾的特定賴氨酸或精氨酸殘基，可激活或抑制轉錄。
- **磷酸化（Phosphorylation）**：可活化或抑制轉錄。

這些修飾被比喻為「標記」（marks），由特定的「writer」添加、由「eraser」移除，並由「reader」蛋白質解讀。另一類重要因子是 chromatin remodeling complexes，能移動 nucleosome 在 DNA 上的位置，暴露或遮蔽啟動子。

### 表觀遺傳與疾病

由於表觀遺傳修飾是可逆的，這些機制成為重要的治療靶點。HDAC 抑制劑及 DNA 甲基化抑制劑已在多种癌症中使用。相較之下，基因突變一旦發生便難以逆轉，這是表觀遺傳學在治療上的最大優勢。

---

## Noncoding RNA

基因體中大部分轉錄產物並不轉譯成蛋白質，而是以非編碼 RNA（noncoding RNA）的形式直接執行調控功能。

### MicroRNA（miRNA）

miRNA 是約 22 個核苷酸長度的小型 RNA 分子，調控轉錄後的基因表現。人類基因體約有 6000 個 miRNA 基因，每個 miRNA 可同時調控多個目標 mRNA，形成龐大的基因調控網絡。

miRNA 的生成流程：
1. miRNA 基因轉錄為 primary miRNA（pri-miRNA）
2. 在細胞核內被 Drosha 酶修剪為 pre-miRNA（具有髮夾結構）
3. Exportin 將 pre-miRNA 運出細胞核
4. 細胞質中的 Dicer 酶將其裁切為約 22 核苷酸的雙股 miRNA
5. 單股 miRNA 與 RISC（RNA-induced silencing complex）結合
6. 根據與目標 mRNA 的互補程度，引導 RISC 進行 mRNA 切割或轉譯抑制

臨床上，miRNA 的異常表達與多種疾病相關，包括癌症、神經退化疾病與心血管疾病。

### Long Noncoding RNA（lncRNA）

lncRNA 是超過 200 個核苷酸的非編碼 RNA，人類基因體中可能含有超過 30,000 種 lncRNA。lncRNA 以多樣化機制調控基因表現：

- **促進轉錄因子結合**：協助轉錄因子接近目標基因，激活轉錄
- **隔離轉錄因子**：搶先結合轉錄因子，防止其作用於目標基因
- **引導染色質修飾酶**：招募 histone modifier 或 DNA methyltransferase 至特定基因座
- **作為結構骨架**：稳定多蛋白複合體的組裝

最著名的例子是 XIST lncRNA——由 X 染色體轉錄而來，在該染色體上形成抑制性「 cloaking」，導致 X 染色體失活（X-inactivation）。

---

## Gene Editing: CRISPR-Cas9

基因編輯技術的突破來自於對細菌適應性免疫系統的研究——CRISPR（clustered regularly interspaced short palindromic repeats）與 Cas9 核酸酶。

### 作用機制

CRISPR-Cas9 系統利用人工設計的 guide RNA（gRNA）引導 Cas9 核酸酶至目標 DNA 序列，產生精確的雙股 DNA 斷裂（double-strand break）：

- **非同源性末端連接（NHEJ）**：細胞以易出錯的機制修復斷裂，導致隨機的插入或缺失突變（indels），可破壞基因功能
- **同源性重組修復（HDR）**：在提供含目標序列的 donor DNA 模板時，細胞可進行精確的序列置換

### 臨床與研究應用

CRISPR-Cas9 技術的應用包括：
- 建立疾病模型（導入特定突變至細胞或動物）
- 修正遺傳疾病的致病突變
- 沉默致病基因
- 改造免疫細胞用於癌症治療

同時，該技術也引發了關於基因改造倫理議題的社會討論。

---

## Cellular Housekeeping

所有細胞，不論分化程度高低，都需要執行維持生命的基本功能——這些被稱為「housekeeping」功能。

### 主要胞器的體積分布（以肝細胞為例）

| 胞器 | 佔細胞體積比 |
|------|-------------|
| Cytosol | 54% |
| Mitochondria | 22% |
| Rough ER | 9% |
| Nucleus | 6% |
| Smooth ER + Golgi | 6% |
| Lysosomes | 1% |
| Peroxisomes | 1% |
| Endosomes | 1% |

---

## Mitochondria

Mitochondria 是細胞的能量工廠，透過 oxidative phosphorylation 將營養物質氧化產生 ATP。每個細胞約含有數百至數千個 mitochondria，擁有自己的 DNA（mtDNA，為環狀雙股分子，編碼 37 個基因）。

Mitochondria 的重要功能包括：
- **ATP 合成**：電子傳遞鏈與化學滲透偶聯產生大部分細胞能量
- **代謝中間產物供應**：提供胺基酸、脂肪酸、血紅素等生物合成前驅物
- **Apoptosis 調控**：釋放 cytochrome c，啟動內在性細胞凋亡途徑
- **鈣離子儲存**：調控細胞內鈣離子濃度

粒線體的生物合成（biogenesis）與自噬性降解（mitophagy）共同維持粒線體數量與品質的恆定。

---

## Proteasome 與 Lysosome：細胞的兩種降解系統

細胞同時運行兩套相互補充的蛋白質降解系統：

### Proteasome

Proteasome 是存在於細胞質與細胞核中的大型蛋白質複合體，負責降解：
- 受損或錯誤折疊的蛋白質
- 被泛素（ubiquitin）標記的蛋白質
- 調控蛋白（如轉錄因子、cyclin 等），進而控制訊號傳遞途徑

降解後產生的短肽（peptides）可用於抗原呈現（MHC class I），是適應性免疫的一環。

### Lysosome

Lysosome 是細胞的「消化中心」，內含多種水解酶（hydrolases），在酸性環境（pH 4.5–5.0）下活化，分解：
- 吞噬進來的微生物
- 受損的胞器（autophagy）
- 細胞外物質（透過 endocytosis）

Lysosome 膜上的質子泵（H+-ATPase）維持其內部酸性環境。

### Peroxisome

Peroxisome 含有 catalase 與其他氧化酶，專門處理極長鏈脂肪酸（very long-chain fatty acids）的 β-氧化，過程中產生過氧化氫（H₂O₂）。由於 catalase 可快速分解 H₂O₂，peroxisome 是細胞抵禦氧化壓力的重要胞器。

---

## Plasma Membrane

### 膜的結構

Plasma membrane 以磷脂雙分子層（phospholipid bilayer）為基礎，鑲嵌膽固醇（cholesterol）與多種蛋白質。磷脂分布具有不對稱性：
- **外層**：phosphatidylcholine 與 sphingomyelin 含量較高
- **內層**：phosphatidylserine（帶負電）與 phosphatidylethanolamine 為主

這種不對稱性在 apoptosis 時會逆轉——phosphatidylserine 外翻至細胞表面，成為吞噬細胞識別的「eat me」信號。

### 膜蛋白的整合方式

膜蛋白以四種方式與雙分子層結合：
1. **跨膜蛋白（Transmembrane proteins）**：以一個或多個 α 螺旋結構域穿越雙層，內側段通常帶正電荷，與內層磷脂的負電荷相互作用
2. **脂肪酸/異戊二烯修飾蛋白**：透過 myristoylation、palmitoylation 或 farnesylation 附著於膜內側
3. **GPI-anchored proteins**：以糖基磷脂醯肌醇錨附於膜外側
4. **外周蛋白**：透過蛋白質-蛋白質交互作用非共價附著於膜表面

### Lipid Rafts

膜上膽固醇豐富的區域形成相對有序的微結構域，稱為 lipid rafts。這些區域富集特定種類的膜蛋白（如 GPI-anchored proteins），是訊號傳遞與膜運輸的重要平台。

---

## 跨膜運輸

### 被動運輸

- **簡單擴散**：小、非極性分子（O₂、CO₂、steroid hormones）可直接穿越脂雙層
- **水通道（Aquaporins）**：高效促進水分子通過細胞膜
- **離子通道（Ion channels）**：形成親水性孔道，選擇性透過特定離子（依大小與電荷），傳輸速度快；可分為配體門控（ligand-gated）、電壓門控（voltage-gated）等類型

### 主動運輸

- **一次主動運輸（Primary active transport）**：直接以 ATP 水解為能源，典型代表為 Na+/K+-ATPase（每消耗一分子 ATP，泵出 3 個 Na+、泵入 2 個 K+），維持細胞內低鈉高鉀的離子梯度
- **二次主動運輸（Secondary active transport）**：利用離子梯度（如 Na+ 梯度）的電化學勢能來驅動其他分子的共同運輸，包括同向轉運（symport）與反向轉運（antiport）

### 受體介導內吞作用

大分子物質（如 LDL、transferrin）與細胞表面特定受體結合後，聚集於 clathrin-coated pits，內化為 coated vesicles。接續歷程：
1. Clathrin 殼層迅速脫落
2. Vesicle 與 early endosome 融合
3. 在 endosome 的酸性環境中，ligand 與受體分離
4. 受體回收至細胞表面，ligand 進入 lysosome 進行降解

LDL receptor 缺陷導致家族性高膽固醇血症（familial hypercholesterolemia），是受體介導內吞失能的經典範例。

---

## Cytoskeleton

細胞骨架是由三類蛋白質纖維組成的動力學系統，支撐細胞形態、驅動細胞運動，並負責胞器與分子貨物的細胞內運輸。

### Actin Microfilaments

直徑 5–9 nm，由 G-actin 單體聚合成 F-actin 雙股螺旋。與 myosin 相互作用產生肌肉收縮的機械力；在非肌肉細胞中，actin 形成應力纖維（stress fibers）與絲狀偽足（filopodia），調控細胞形態與遷移。

### Intermediate Filaments

直徑 10 nm，是最大且最多樣化的細胞骨架家族，各成員具有組織特異性，可作為腫瘤來源鑑定的標記：

| 成員 | 主要分布 |
|------|---------|
| Vimentin | 间充质细胞（fibroblasts、endothelium） |
| Desmin | 肌肉細胞 |
| Neurofilaments | 神經元軸突 |
| GFAP | 膠質細胞 |
| Cytokeratins | 上皮細胞（超過 30 種） |
| Lamins（A、B、C） | 細胞核膜（nuclear lamina） |

Nuclear lamins 維持核形態並參與基因轉錄調控。Lamins 突變導致多種疾病，包括某些肌肉失養症與早衰症（progeria）。

### Microtubules

直徑 25 nm，由 α- 與 β-tubulin 異二聚體排列成中空管狀結構，具有極性（正端與負端）。Microtubules 是「分子馬達」蛋白的軌道：
- **Kinesins**：負責正向（−至+）運輸
- **Dyneins**：負責反向（+至−）運輸

此外，microtubules 參與有絲分裂時姐妹染色單體的分離，以及纖毛（cilia）與鞭毛（flagella）的運動。Primary cilia 是位於大多數有核細胞表面的單一非運動性突起，調控細胞增殖與分化，其功能缺陷與多種發育異常相關。

---

## Cell-Cell Interactions

上皮細胞層與組織的整体性依賴三類細胞連接結構的協同作用：

### Tight Junctions（Occluding Junctions）

 Tight junctions 封堵相鄰上皮細胞之間的細胞間隙，阻止溶質的旁路擴散（paracellular transport），同時作為上皮細胞頂端與基底外側膜 domain 的物理邊界。主要由 claudin 與 occludin 蛋白構成。

### Desmosomes（Anchoring Junctions）

機械性連接相鄰細胞的細胞骨架，提供組織抗機械應力的強度。spot desmosomes 以 cadherin 家族的 desmoglein/desmocollin 為跨膜黏附分子，細胞內端與 intermediate filaments（通常為 desmoplakin）相連。Hemidesmosomes 則以 integrin 連接細胞與細胞外基質（ECM）。

### Gap Junctions（Communicating Junctions）

由 six connexin 蛋白組成的 connexon（半通道）在兩相鄰細胞間配對，形成 1.5–2 nm 的親水性通道，允許離子、 nucleotides、胺基酸、維生素等小分子（<1 kDa）直接通過。在心肌組織中，gap junctions 使細胞間 Ca2+ 訊號同步傳遞，確保心肌以功能合胞體（functional syncytium）形式協調收縮。

---

## Cellular Aging

### 複製性衰老（Replicative Senescence）

正常人類體細胞在體外培養時，約經歷 50–70 次細胞分裂後進入不可逆的生長停滯狀態，稱為複製性衰老。此極限與染色體末端的 telomere 逐漸縮短密切相關。

每次 DNA 複製時，由於 DNA 聚合酶（DNA polymerase）無法完整複製線性分子的末端，telomere 會損失 50–200 個鹼基。當 telomere 縮短至臨界長度時，細胞啟動 DNA damage response，導致 p53 依賴性的生長停滯。

### Stress-Induced Premature Senescence（SIPS）

除 telomere 縮短外，多種刺激可誘發衰老表型：
- **氧化壓力（Oxidative stress）**：累積的氧化損傷加速衰老進程
- **DNA 損傷**：輻射、致癌物等造成嚴重 DNA 損傷
- **線粒體功能障礙**：能量代謝失調觸發衰老路徑

衰老的細胞呈現特徵性的形態學與分子表型：細胞擴大、SA-β-gal 活性增加、衰老相關分泌表型（SASP，包含 IL-6、IL-8、MMPs 等），這些分泌因子可誘導鄰近細胞的衰老樣變化並激活免疫系統。

### Telomere 與腫瘤

值得注意的是，腫瘤細胞可透過活化 telomerase（85–95% 的癌症）或使用替代性 telomere 延長機制（alternative lengthening of telomeres，ALT）來維持 telomere 長度，獲得「immortality」。這種機制使癌細胞突破複製性衰老的限制，得以無限增殖。

---

## Summary

- 人類基因體超過 99.5% 的序列在個體間相同，但少於 0.5% 的差異決定了疾病易感性，主要變異形式為 SNP 與 CNV
- Epigenetics（DNA 甲基化、histone 修飾）調控基因表現而不改變 DNA 序列；這些修飾是可逆的，成為治療靶點
- miRNA 與 lncRNA 構成龐大的非編碼 RNA 調控網絡，調控發育、分化與疾病
- CRISPR-Cas9 技術實現精確的基因編輯，具有治療遺傳疾病的巨大潛力
- 細胞的 housekeeping 功能由各胞器分區執行：mitochondria 產生能量，proteasome 與 lysosome 負責蛋白質降解，ER 與 Golgi 負責蛋白質合成與修飾
- Plasma membrane 的磷脂雙分子層與整合膜蛋白共同執行識別、運輸與信號傳遞功能
- Cytoskeleton（actin、intermediate filaments、microtubules）提供細胞結構支撐與運動能力
- 細胞間連接（tight junctions、desmosomes、gap junctions）維護組織結構完整性與細胞通訊
- 細胞老化由 telomere 縮短與多种 stress 共同驅動，腫瘤細胞透過 telomerase 活化逃脫此限制
