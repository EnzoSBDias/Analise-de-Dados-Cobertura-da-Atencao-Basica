# 📊 Análise da Cobertura da Atenção Básica no Brasil

Este projeto tem como objetivo explorar e analisar dados relacionados à cobertura da Atenção Básica no Brasil, com foco na atuação das **Equipes de Saúde da Família (eSF)** e das **Equipes de Atenção Básica (eAB)**. A análise visa compreender o acesso da população aos serviços essenciais de saúde oferecidos pelo SUS, com base em informações populacionais e operacionais.

---

## 🎯 Objetivos da Análise

- 📈 Avaliar a evolução da cobertura populacional ao longo do tempo, por município e estado.
- 🏥 Analisar a distribuição das equipes de saúde e suas respectivas cargas horárias.
- 🔍 Investigar a relação entre a população total e a população efetivamente coberta pelos serviços.
- ⚖️ Comparar a cobertura entre a Estratégia Saúde da Família e a Atenção Básica como um todo.

---

## 🧾 Descrição das Principais Variáveis

- **Período**
  - `ano`, `mes`: Indicam o período de referência das informações.
  
- **Geolocalização**
  - `id_municipio`, `sigla_uf`: Identificadores do município e estado.

- **Cobertura Populacional**
  - `populacao`: População total estimada.
  - `populacao_coberta_estrategia_saude_familia`: Total de pessoas cobertas pela Estratégia Saúde da Família.
  - `populacao_coberta_total_atencao_basica`: Total coberto por toda a Atenção Básica.
  - `proporcao_cobertura_estrategia_saude_familia`: Percentual de cobertura pela eSF.
  - `proporcao_cobertura_total_atencao_basica`: Percentual de cobertura pela AB.

- **Recursos Humanos**
  - `carga_horaria_medica_atencao_basica_tradicional`: Total de horas de trabalho médico.
  - `carga_horaria_enfermagem_atencao_basica_tradicional`: Total de horas de trabalho de enfermagem.
  - `quantidade_equipes_saude_familia`, `quantidade_equipes_atencao_basica_total`: Número de equipes em atuação.

---

## 🛠️ Ferramentas e Tecnologias

- Python (Análise de dados)
- Pandas (Manipulação de dados)
- Matplotlib e Seaborn (Visualizações gráficas)
- Jupyter Notebook (Ambiente interativo)

---

## 🤝 Contribuição

Contribuições são muito bem-vindas! Sinta-se à vontade para:

- Abrir **issues** com sugestões ou dúvidas
- Criar **pull requests** com correções, melhorias ou novas análises

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
