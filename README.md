# Ciência de Dados e Tomada de Decisão

Este repositório reúne bases de dados, exemplos práticos e materiais complementares associados ao livro *Ciência de Dados e Tomada de Decisão*, de Wesley Marcos Almeida.

O livro apresenta fundamentos e aplicações de Ciência de Dados, Estatística, Python, aprendizado de máquina, Big Data, inteligência artificial e gestão de projetos. O repositório complementa a obra com os arquivos necessários à execução de exemplos e atividades.

Os exemplos estão organizados em pastas identificadas pelo capítulo a que pertencem. As bases de dados utilizadas ficam na pasta `dados/`. Scripts em Python, com extensão `.py`, serão organizados na pasta `scripts/`.

## Como usar este repositório

1. Consulte no livro o capítulo e a seção relacionados ao tema de interesse.
2. Acesse a pasta do capítulo correspondente para localizar os arquivos do exemplo.
3. Quando o exemplo utilizar uma base compartilhada, localize o arquivo na pasta `dados/`.
4. Se o exemplo tiver um script Python independente, consulte a pasta `scripts/`.
5. Siga as instruções do livro e dos arquivos para executar a atividade e interpretar os resultados.

Os materiais são complementares ao livro. A leitura do capítulo correspondente é recomendada para compreender o problema analisado, as decisões de preparação dos dados e os limites das conclusões.

## Estrutura do repositório

```text
cienciadedados/
├── README.md
├── requirements.txt
├── dados/
│   ├── caso_tech.csv
│   ├── dados_loja_xyz.xlsx
│   └── ...
├── cap 1/
│   └── ...
├── cap 2/
│   └── ...
├── cap 3/
│   └── ...
├── cap 4/
│   └── ...
├── cap 5/
│   └── ...
├── cap 6/
│   └── ...
├── cap 7/
│   └── ...
├── cap 8/
│   └── ...
├── cap 9/
│   └── ...
├── cap 10/
│   └── ...
├── cap 11/
│   └── ...
├── cap 12/
│   └── ...
├── cap 13/
│   └── ...
├── cap 14/
│   └── ...
└── scripts/
    └── ...
```

A lista acima ilustra a organização do repositório. A estrutura efetivamente disponível pode variar conforme os materiais de cada capítulo sejam incluídos.

### Pastas `cap 1/`, `cap 2/` e demais capítulos

Cada pasta identificada por `cap` e pelo número do capítulo reúne os exemplos e materiais práticos correspondentes àquele capítulo. Os arquivos podem incluir notebooks, planilhas e outros materiais de apoio, conforme a ferramenta utilizada na atividade.

Essa organização permite localizar os exemplos diretamente pelo capítulo do livro, sem uma pasta geral intermediária para os materiais dos capítulos.

### Pasta `dados/`

Contém as bases de dados utilizadas nos exemplos. Os arquivos podem estar em formatos como CSV e XLSX.

Uma mesma base pode ser utilizada em mais de um capítulo. Nesse caso, o arquivo fica na pasta `dados/`, e as pastas dos capítulos contêm os materiais específicos de cada aplicação.

Antes de iniciar uma análise, consulte no livro ou nos próprios arquivos as informações disponíveis sobre a origem dos dados, a unidade de observação, o significado das variáveis, o período coberto e eventuais limitações.

### Pasta `scripts/`

Destina-se aos scripts independentes em Python, com extensão `.py`. Quando um script depender de uma base armazenada em `dados/`, as instruções do próprio script ou do capítulo correspondente devem indicar como localizar e carregar o arquivo.

### Arquivo `requirements.txt`

Relaciona as dependências Python necessárias para executar os materiais que utilizam essa linguagem. A instalação e a execução devem considerar as instruções de cada exemplo e o ambiente Python utilizado.

## Ferramentas utilizadas

Os exemplos do livro podem utilizar diferentes ferramentas, conforme o objetivo da atividade:

- **Excel:** organização, cálculo e análise de dados em planilhas;
- **JASP:** análises estatísticas e inferenciais;
- **Power BI:** modelagem e construção de relatórios interativos;
- **Python:** preparação de dados, análise, modelagem preditiva e operacionalização.

A ferramenta utilizada em cada exemplo é indicada no capítulo correspondente. Nem todos os exemplos exigem programação.

## Notebooks Python e Google Colab

Quando houver um notebook compatível com o Google Colab, ele poderá incluir um botão **Abrir no Colab**. O notebook deve ser localizado na pasta do capítulo a que pertence.

Alguns notebooks podem depender de arquivos armazenados em `dados/`. Nesses casos, as instruções do notebook devem indicar como acessar ou carregar a base.

## Bases de dados e interpretação

As bases disponibilizadas têm finalidade didática e devem ser analisadas considerando suas características e limitações. A presença de registros em uma base não garante, por si só, que ela represente uma população ou permita conclusões causais.

Nos exemplos, é importante observar:

- qual é a unidade de análise;
- como cada variável foi definida;
- quais registros foram incluídos ou excluídos;
- quais transformações foram aplicadas;
- se há valores ausentes, duplicidades ou inconsistências;
- qual período e contexto os dados representam;
- quais conclusões podem ou não ser sustentadas pelos dados.

Quando a origem ou as condições de uso de uma base forem especificadas no livro, no arquivo ou na fonte original, essas informações devem ser consideradas.

## Reprodutibilidade

Para facilitar a reprodução dos exemplos:

1. utilize os arquivos indicados no capítulo;
2. mantenha os dados originais separados dos dados transformados, quando aplicável;
3. registre as alterações realizadas durante a preparação dos dados;
4. confira as versões das bibliotecas Python quando houver diferenças de execução;
5. considere as premissas e limitações descritas no livro ao interpretar os resultados.

## Relação entre o livro e o repositório

A organização dos materiais procura manter uma relação direta entre:

- **livro:** apresenta os conceitos, os objetivos e a interpretação;
- **pastas dos capítulos:** reúnem os exemplos e arquivos específicos de cada capítulo;
- **pasta `dados/`:** armazena as bases utilizadas nos exemplos;
- **pasta `scripts/`:** reúne scripts Python independentes, quando disponíveis;
- **arquivo `requirements.txt`:** relaciona dependências necessárias para os materiais em Python.

Um mesmo conjunto de dados pode ser utilizado em capítulos diferentes, com perguntas e procedimentos distintos. Por isso, não se deve presumir que a preparação feita em um exemplo seja adequada para outro sem consultar as instruções correspondentes.

## Atualizações dos materiais

Os arquivos do repositório podem ser atualizados para acompanhar revisões do livro e dos exemplos. Quando houver diferença entre um arquivo e a descrição apresentada na obra, consulte a versão mais recente dos materiais e as orientações do capítulo correspondente.

## Referência ao livro

Almeida, Wesley Marcos. *Ciência de Dados e Tomada de Decisão*. 2026.

Consulte a edição utilizada para conferir os dados editoriais completos.

## Licença e condições de uso

As condições de uso podem variar conforme o arquivo e a origem da base de dados. Antes de reutilizar ou redistribuir qualquer material, consulte a licença do repositório e as informações associadas ao arquivo. Quando uma base tiver condições específicas de uso, elas devem ser respeitadas.
