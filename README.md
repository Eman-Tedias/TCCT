**Análise de Elementos Nostálgicos em *Toy Story 3* através de Inteligência Artificial e Processamento de Linguagem Natural**

**Autor:** Emanuel Turibio Dias  
**Curso:** Bacharelado em Cinema de Animação - Universidade Federal de Pelotas  
**Orientadora:** Profa. Dra. Carla Schneider  
**Ano:** 2025

---

## Objetivo do Projeto

Este trabalho teve como objetivo investigar como ferramentas de **Inteligência Artificial (IA)** e **Processamento de Linguagem Natural (PLN)** podem ser utilizadas como **metodologia para identificar elementos estéticos e narrativos de nostalgia** no filme *Toy Story 3* (2010).

A ideia inicial era realizar a análise fílmica, criar um painel semântico e fazer o cruzamento bibliográfico, porém ao final da primeira etapa, já existiam mais de 60 elementos nostálgicos e eu precisava pensar em uma solução para de alguma forma, conseguir selecionar apenas uma parcela das amostras. Então me veio a ideia de verificar quais cenas foram mais marcantes para os espectadores do filme e junto ao meu conhecimento com análise de dados e programação, acabou dando um outro rumo para o trabalho.

---

## Metodologia

A metodologia foi dividida em **sete etapas**, integrando abordagens qualitativas (análise fílmica e de roteiro) e quantitativas (PLN) para obtenção e análise dos dados:

### 1. Identificação de Cenas Nostálgicas no Filme
- Realização de análise fílmica manual.
- Registro de cenas potencialmente nostálgicas com descrição e minutagem.
- Ferramenta usada: **Google Docs**.

### 2. Análise do Roteiro do Filme
- Obtenção do roteiro via Scriptslug.
- Divisão do roteiro em 12 partes.
- Envio dos trechos ao modelo **GPT-4o** da OpenAI com prompts estruturados para detectar elementos nostálgicos.

### 3. Comparação entre Cenas e Roteiro
- Cruzamento entre os dados da análise fílmica e do roteiro processado pela IA.
- Verificação de elementos adicionais não percebidos inicialmente.

### 4. Organização dos Dados em Categorias
- Agrupamento das informações textuais em **cinco categorias temáticas** através do ChatGPT:
  - Elementos Icônicos e Referências Pop
  - Infância, Crescimento e Despedida
  - Vida dos Brinquedos: Abandono e Emoção
  - Aventuras e Trabalho em Equipe
  - O Mundo dos Brinquedos: Cenários e Metáforas

### 5. Coleta de Comentários de Espectadores
- Extração de 890 comentários da base de dados IMDb via Kaggle.

### 6. Processamento dos Comentários
- Análise individual dos comentários com IA para identificar menções nostálgicas.
- Uso de código em Python para estruturar prompts personalizados por categoria.
- Geração de colunas temáticas em uma tabela final contendo o cruzamento de dados.

### 7. Geração de Rankings de Nostalgia
- Execução de script em Python para ranquear as cenas mais mencionadas por categoria e no total.
- Exemplo: “Andy indo para a faculdade” foi a cena mais citada (446 menções).

---

## Ferramentas Utilizadas

- **Python (Jupyter Notebook)**
- **OpenAI GPT-4o**
- **Google Docs**
- **Pandas / JSON**

---

## Conclusões

- A metodologia aplicada revelou-se inovadora ao combinar cinema, análise textual e ciência de dados.
- A IA demonstrou bom desempenho, embora algumas inconsistências tenham sido observadas.
- Recomenda-se a melhora da contextualização semântica nos prompts para maior precisão.
- O estudo propõe novas possibilidades de aplicação da IA em pesquisas nas áreas de cinema e artes.

---

## Referências

- Toy Story 3 (2010)
- Johnson-Laird & Oatley (1989) - Emoções e linguagem  
- Wildschut et al. (2006) - Função social da nostalgia  
- Kessous (2015) - Nostalgia e marcas  
- Zhou et al. (2013) - Nostalgia e identidade  
- IMDb Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/ebiswas/imdb-review-dataset)

## Acesso
[URL para leitura](https://acervosvirtuais.ufpel.edu.br/tccscinema/wp-content/uploads/sites/24/tainacan-items/16/11879/1829393199143517_analise_de_elementos_nostalgicos_em_toy_story_3_atraves_de_inteligencia_artificial_e_processamento_de_linguagem_natural.pdf)
