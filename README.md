# Análise da Cobertura da Atenção Básica no Brasil

Este projeto tem como objetivo explorar e analisar dados sobre a cobertura da Atenção Básica no Brasil, com foco no monitoramento da atuação das equipes de saúde da família (eSF) e das equipes de Atenção Básica (eAB). A base de dados utilizada traz informações populacionais e operacionais importantes para compreender o acesso da população aos serviços essenciais de saúde ofertados pelo SUS.

## Objetivos da Análise

- Avaliar a evolução da cobertura populacional ao longo do tempo por município e estado.
- Analisar a distribuição das equipes de saúde e suas cargas horárias.
- Investigar a relação entre a população total e a população efetivamente coberta pelos serviços.
- Comparar a cobertura entre a estratégia de saúde da família e a atenção básica como um todo.

## Principais Colunas da Base de Dados

- `ano`, `mes`: Período de referência da informação.
- `id_municipio`, `sigla_uf`: Identificadores geográficos.
- `populacao`: População total estimada do município.
- `populacao_coberta_estrategia_saude_familia`, `populacao_coberta_total_atencao_basica`: Cobertura populacional pelos serviços.
- `proporcao_cobertura_estrategia_saude_familia`, `proporcao_cobertura_total_atencao_basica`: Percentual da população coberta.
- `carga_horaria_medica_atencao_basica_tradicional`, `carga_horaria_enfermagem_atencao_basica_tradicional`: Total de horas trabalhadas por médicos e enfermeiros.
- `quantidade_equipes_saude_familia`, `quantidade_equipes_atencao_basica_total` (e variações): Quantidade de equipes atuantes.

## Ferramentas Utilizadas

- Python
- Pandas
- Matplotlib / Seaborn (para visualizações)
- Jupyter Notebook

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com sugestões de melhorias ou novas análises.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
