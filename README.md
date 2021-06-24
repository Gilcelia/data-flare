# data-flare
BI Master_Trabalho final_ Matrícula: 192.190.100
# Aplicação de Machine Learning para análise de queima de gás em flare em plataforma de petróleo 

#### Aluna: [Gilcelia Borges](https://github.com/Gilcelia)
#### Orientador: [Felipe Borges](https://github.com/FelipeBorgesC)
---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/Gilcelia/data-flare). <!-- caso não aplicável, remover esta linha -->

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho -->

O sistema de tocha (flare) de uma plataforma de Petróleo tem como principal objetivo manter a segurança operacional da unidade. 
Sua função é garantir a adequada despressurização dos sistemas em situações de anormalidades, de modo manter a pressão no interior
 das linhas e equipamentos nos limites máximos admissíveis projetados, garantindo dessa forma a integridade de pessoas e instalações em situações de emergência.  
O adequado controle dos parâmetros de processo contribui para estabilidade operacional da unidade, evitando o envio desnecessário de gases para flare e, 
por consequência reduzindo as emissões de gases causadores do efeito estufa (GEE). 

O objetivo do estudo foi aplicar os métodos de Machine Learning para avaliar a correlação e o impacto de diferentes parâmetros de processo aos eventos de envio de gases para flare. O Estudo de caso pode ser categorizado como um problema de Classificação (Aprendizado Supervisionado) onde o rótulo categórico de saída foi definido como SIM ou NÃO para a ocorrência de envio de gases para flare acima do limite definido como aceitável. 

O estudo foi realizado a partir das seguintes etapas:
•	Mapeamento dos principais parâmetros potencialmente relacionados ao envio de gás para flare, através da análise dos processos da plataforma.  
•	Definição do período de aquisição de dados.
•	Obtenção dos dados a partir do repositório de informações de processo (Plant Information), utilizando código em Python.
•	Pré-processamento dos dados: 
              o	Tratamento de missing values;
              o	Normalização:  etapa essencial em função das diferentes unidades de medida dos parâmetros selecionados. 
•	Avaliação de 4 diferentes métodos de Machine Learning aplicáveis aos problemas de classificação, utilizando a plataforma RapidMiner: Árvore de decisão, Randon Forest, Support Vector Machine (SVM) e K nearest neighbors (KNN).

### Conclusão

O método KNN se mostrou o mais adequado para avaliação do estudo de caso, apresentando resultado de acurácia igual a 99,89% para o a base de dados utilizada.   
Como etapa subsequente ao trabalho desenvolvido, cabe avaliar a aplicação da metodologia para diferentes plataformas de petróleo, ampliando-se também o escopo de análise 
com  parâmetros de processo adicionais aos mapeados inicialmente.  

---

Matrícula: 192.190.100

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
