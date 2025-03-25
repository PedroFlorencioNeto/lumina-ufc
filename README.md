# Lumina

Uso de Visão Computacional no Apoio ao Diagnóstico de Doenças Oculares.


## Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina de Visão Computacional do Programa de Pós-Graduação em Ciência da Computação (PPGCC) na Universidade Federal de Santa Catarina (UFSC). O objetivo é explorar técnicas de visão computacional para auxiliar no diagnóstico de doenças oculares, aplicando métodos clássicos e modelos de Deep Learning em imagens médicas de fundoscopia.

## Objetivos

- Implementar um pipeline de análise de imagens oftalmológicas.
- Utilizar técnicas de aprendizado de máquina para detectar padrões relacionados a doenças oculares.
- Desenvolver um modelo capaz de classificar diferentes tipos de patologias oculares.
- Avaliar a performance dos modelos e discutir seus resultados.

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Frameworks:** TensorFlow, PyTorch, OpenCV
- **Bibliotecas:** NumPy, Pandas, Scikit-learn, Matplotlib
- **Ambiente de Desenvolvimento:** Jupyter Notebook

## Estrutura do Projeto

```
/
|-- data/                   # Conjunto de dados utilizado
|-- notebooks/              # Jupyter Notebooks para experimentos
|-- src/                    # Código-fonte do projeto
|   |-- preprocessing.py     # Preprocessamento das imagens
|   |-- model.py             # Definição do modelo de deep learning
|   |-- train.py             # Script de treinamento
|   |-- evaluate.py          # Avaliação do modelo
|-- results/                # Resultados e modelos treinados
|-- requirements.txt        # Dependências do projeto
|-- README.md               # Documentação do projeto
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://gitlab.com/pedroflorencio/lumina.git
   cd lumina
   ```

2. Crie um ambiente virtual e instale as dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Execute os notebooks ou scripts para treinamento e avaliação do modelo.

## Conjunto de Dados

O projeto utiliza imagens de fundo de olho obtidas do [Kaggle](https://www.kaggle.com/datasets/ruhulaminsharif/eye-disease-image-dataset).

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)
3. Faça commit das mudanças (`git commit -m 'Adicionando nova feature'`)
4. Faça push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request

## Autor

- [Pedro Florencio](https://github.com/PedroFlorencioNeto) - Universidade Federal do Ceará (UFC)

## Licença

Este projeto está sob a [Licença MIT](LICENSE).
