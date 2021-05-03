# Caminho Ótimo na Preparação de Conteúdo Sob Demanda

#### Aluno: Marcio Albernaz de Mello (https://github.com/mello-marcio) 
#### Orientador(/a/es/as): Ana Carolina (prof.carolina@ica.ele.puc-rio.br) e Felipe Borges (prof.felipe@ica.ele.puc-rio.br).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- Link para o código: https://github.com/mello-marcio/BI-MASTER

---

### Resumo

Com o crescente número de oferta de serviços de distribuição de vídeo via streaming (OTT), como NETFLIX, AMAZON PRIME, GLOBOPLAY etc., cresce também a demanda de preparação dos conteúdos. 
Este serviço consiste em compatibilizar diferentes formatos de arquivo de vídeo, como por exemplo o FRAME RATE (50/60fps), o formato do áudio (MONO, ESTÉREO, DOLBY 2.0, DOLBY 5.1, etc.), formato do arquivo de legenda, dublagem e sincronização de áudio português etc. Soma-se a isso os grandes volumes de conteúdos e serem trabalhados, como por exemplo, uma série com 10 temporadas, onde cada temporada possui 10 episódios de 45min ou todos os capítulos de uma novela.

O objetivo desse estudo e definir a solução de menor custo na distribuição das atividades associadas ao conteúdo, a legenda em português, ao áudio original e português (dublado), ao formato do vídeo e o formato do arquivo a ser transcrito e publicado nas operadoras e/ou na CDN (17 serviços).

Neste estudo, foram consideradas 05 posições de trabalho, com maior ou menor especialização para os serviços de triagem e caracterização do conteúdo, edição de vídeo, sonorização, conversão de formato de arquivos e o serviço de produtoras especializadas. Também está prevista uma posição totalmente automatizada para realização de serviços específicos, como conversão de formato de vídeo e/ou áudio, queima de legenda, além da conversão e codificação dos conteúdos para o formato mezanino.

A partir da caracterização do conteúdo (serviço 1), são identificas e sinalizadas nos campos em verde da planilha as necessidades de compatibilização (1 – indica a necessidade e 0 – indica que o conteúdo está conforme). A partir dessas definições utilizamos a função SOLVER para identificar a distribuição de menor custo das atividades pelas posições (1-7). Para tal, foram inseridas restrições quanto ao número máximo de horas para as posições físicas (máximo 24h), para a máquina (máxima 10x24h equivalente a 10 posições por máquina). Não foi definida restrição para o volume de serviços externos (laboratórios e produtoras). A tabela “Local de Realização do Serviço” e “Tempo de Realização do Serviço” caracterizam a especialização da posição para o serviço.

A distribuição e alocação dos serviços no tempo, priorizados em função da estratégia de publicação dos conteúdos, não faz parte desse trabalho (escopo negativo). Este complemento é uma sugestão para futuros projetos dessa natureza.

---

Matrícula: 191.671.057

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
