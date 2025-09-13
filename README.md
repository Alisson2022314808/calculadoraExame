# Calculadora de nota para exame IFFar - Cursos Superiores
## **Descrição**
O sistema tem por objetivo auxiliar estudantes dos cursos superiores da rede do IFFar a calcular, de forma precisa e imediata, a nota mínima a ser obtida no exame para alcançar a média necessária em seus componentes curriculares.
### **Motivo**
Constatou-se que muitos colegas enfrentavam dificuldades em localizar e interpretar as normas de avaliação de aprendizagem, previstas nos [Projetos Pedagógicos de Curso (PPCs)](https://www.iffarroupilha.edu.br/projeto-pedag%C3%B3gico-de-curso).
Foi feita, então, uma pesquisa documental aprofundada, nas versões mais recentes desses documentos, buscando e comparando os critérios que compõem o cálculo da nota final do aluno.
* Destaca-se, para fins de esclarecimento que, no PPC de cada curso, esses detalhes foram encontrados no capítulo "Organização Didático-Pedagógica", no item com título "Avaliação da Aprendizagem", títulos mantidos embora a numeração varie conforme o curso — o que evidencia, portanto, a especificidade necessária na busca pela mencionada seção.

A estrutura da aplicação foi inspirada na "[calculadora para cursos técnicos do IFFar](https://github.com/Uianes/calculadoraExame)", produzido integralmente pelo Uianes Luiz Rockenbach Biondo há algum tempo. Seu projeto está disponível para acesso em: [https://calcnotas.netlify.app](https://calcnotas.netlify.app)

## **Principais ferramentas empregadas**
* *HTML5* para a estrutura das páginas Web
* *CSS3* — integrado com *Bootstrap* — para a estilização e responsividade
* *JavaScript* para para a implementação da lógica de cálculo

## **Funcionalidades**
O site apresenta, primeiramente, os métodos de cálculo da nota mínima necessária para aprovação no exame, e uma fórmula para calcular a nota final após o exame.
Conta com um único campo de entrada da dados, para inserir o valor da média na disciplina desejada. Após clicar no botão de "calcular", o sistema verifica a necessidade de realizar o exame e, em caso positivo, qual a nota a atingir.

## **Escopo e Limitações**
Destinada exclusivamente a estudantes dos cursos de nível superior da rede do IFFar. Ressalta-se também que a ferramenta não considera critérios de frequência mínimas em aula (carga horária presencial), nem métodos suplementares de avaliação, em caso de desempenho insuficiente no exame.
