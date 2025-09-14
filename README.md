TP: Mineração de Repositórios de Software

## Objetivo 

O projeto consiste no desenvolvimento de uma ferramenta de linha de comando em Python capaz de analisar as dependências de um projeto a partir de arquivos como requirements.txt ou poetry.lock.

A ferramenta consulta a API do PyPI para verificar versões vulneráveis, dependências desatualizadas ou repositórios que foram descontinuados. Além disso, avalia o histórico de atualizações, medindo a frequência de releases e o tempo médio de adoção de novas versões pelo projeto.

Os resultados são apresentados em um relatório HTML, contendo gráficos e tabelas interativas que destacam riscos de segurança, obsolescência e padrões de manutenção das dependências.

- Origem dos dados: GitHub

- Artefatos analisados: código, arquivos do projeto, histórico  de dependências.

- Apresentação de resultados: relatório HTML, contendo gráficos e tabelas interativas que destacam métricas de dependências.

- Tecnologias utilizadas: pydriller, GitHub API, PyPI API, typer, click, python-fire, argparse

## Membros

- Cecilia Junqueira Vieira Machado Pereira

- Felipe Lopes Gomide

- Lucas Junqueira Carvalhido

- Lucca Alvarenga de Magalhaes Pinto
