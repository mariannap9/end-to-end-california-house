# Projeto de Machine Learning de ponta a ponta — California Housing

Atividade da disciplina de Inteligência Artificial e Computacional, baseada no Capítulo 2 de *Hands-On Machine Learning* (Aurélien Géron).

Previsão do valor mediano de imóveis por distrito da Califórnia (regressão supervisionada).

## Conteúdo
- `Projeto_ML_California_MariannaCastro.ipynb`: notebook executado (estudo guiado, 4 desafios, 5 questões e conclusões).
- `data/housing.csv`: dados de referência do livro (repositório de Géron). O notebook baixa o arquivo sozinho se ele não existir.
- `requirements.txt`: bibliotecas usadas.

## Como executar?
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m jupyter lab
```
Abra o notebook, use *Kernel → Restart Kernel and Run All Cells*. A pasta `models/` (modelo salvo) é criada na execução e não é versionada.

## Resultado principal
Floresta aleatória ajustada por Random Search: RMSE ≈ US$ 46.912, MAE ≈ US$ 31.258 e R² ≈ 0,831 no conjunto de teste.
