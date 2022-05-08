# Bachelor Thesis

## Outline
- [ ] **Introduction**
   - [ ] Spanning-forest model
   - [ ] Monte Carlo methods
   - [ ] Plan of the work
- [ ] **The Spanning-forest model**
   - [ ] Connection to Potts mdeol
   - [ ] Fermionic Representations
   - [ ] Questions we want to solve
- [ ] **Algorithm and data structure**
   - [ ] Sweeny Algorithm
   - [ ] Link-cut tree
- [ ] **Results**
- [ ] **Conclusion**


## Template Download

- GitHub Releases：https://github.com/ustctug/ustcthesis/releases

- 校内镜像：https://git.lug.ustc.edu.cn/ustctug/ustcthesis

- Overleaf 模板 https://www.overleaf.com/latex/templates/latex-template-for-ustc-thesis/jvtdfkqsrycm

- 研究生院网站（版本较旧，不推荐）：https://gradschool.ustc.edu.cn/column/65


## Compile Document

- 编译模板的使用说明文档 `ustcthesis-doc.pdf`：
   ```
   latexmk -xelatex ustcthesis-doc.tex
   ```
- 编译论文 `main.pdf`：
   ```
   latexmk -xelatex main.tex
   ```
- 如需清理论文编译过程中的临时文件，可以：
   ```
   latexmk -c
   ```

- 以上编译过程也可以用 `make` 工具：
   ```
   make doc        # 编译生成 ustcthesis-doc.pdf
   make            # 编译生成论文 main.pdf
   make clean      # 删除编译过程中生成的临时文件
   ```
