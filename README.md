**IMREA Assistente - HC Telemedicina**
Sistema Web Demonstrativo para Atendimento Digital ao Paciente

**Introdução**
Este repositório abriga um sistema web desenvolvido para fins de demonstração e estudo, simulando funcionalidades essenciais de telemedicina destinadas
ao Instituto de Medicina Física e Reabilitação (IMREA) do Hospital das Clínicas.
O objetivo deste projeto é representar de forma didática os fluxos principais de interação entre pacientes e um sistema digital de saúde,
focando em login, agendamento de consultas e consulta de resultados médicos, incluindo exames, laudos e receitas.
Destinado a estudantes, profissionais de TI da saúde e interessados no desenvolvimento de soluções para telemedicina,
este sistema proporciona um ambiente seguro para entender conceitos de usabilidade, arquitetura de front-end e boas práticas de acessibilidade.

**Objetivos do Projeto**
Simulação Realista de Fluxo Digital — Estruturar telas e fluxos que representam etapas críticas da jornada do paciente em ambientes hospitalares modernos,
desde a autenticação até a visualização de resultados clínicos.
Exercício de Boas Práticas de Design — Implementar princípios de responsividade, acessibilidade e usabilidade, valorizando a experiência do usuário
em plataformas digitais voltadas à saúde.
Base para Estudo Acadêmico ou Prototipagem Institucional — Oferecer um ponto de partida para projetos de pesquisa, testes de interface,
treinamentos internos ou apresentação de propostas inovadoras em congressos e cursos relacionados à saúde digital.

**Funcionalidades Principais**
Autenticação Segura do Paciente:
Interface de login que permite identificação do usuário, inclusive com a opção de upload de fotografia para personalização do atendimento.

Agendamento Dinâmico de Consultas:
Formulário digital para marcação de consultas médicas de forma fácil, ágil e centralizada, com feedback visual para confirmação.

Visualização Prática de Resultados e Documentos Médicos:
Área dedicada à consulta de exames laboratoriais, laudos médicos e receitas, permitindo a visualização online e download dos documentos necessários.

Design Amigável e Acessível:
Layout cuidadosamente projetado para garantir uso intuitivo em desktops, tablets e smartphones, com atenção especial à legibilidade,
contrastes adequados e acessibilidade para pessoas com deficiências visuais.



**Estrutura do Projeto**
projeto-imrea/
│
├── css/
│   ├── login.css                     # Estilização da página de login
│   ├── resultado.css                 # Estilização da área de resultados
│   ├── styleG.css                    # Estilo Grande
│   ├── StyleM.css                    # Estilos Médio
│   └── styleP.css                    # Estilo Pequeno
│
├── imagens/
│   ├── aluno.jpg                     # Imagem Aluno
│   ├── aluno.jpg                     # Imagem Aluno
│   ├── exame.jpg                     # Icone Exame
│   ├── imrea2.jpg                    # Imagem Imrea
│   ├── laudo.jpg                     # Laudo Imagem
│   ├── login.jpg                     # Icone Login
│   ├── logo.jpg                      # Logo Hc
│   ├── receita.avif                  # Icone Receita
│   └── voltar.png                    # Ícone de navegação
│
├── index.html                        # Página principal / agendamento
├── login.html                        # Tela de autenticação do paciente
├── resultado.html                    # Tela de visualização de documentos
└── receitaMedica.txt                 # Exemplo de Receita

**Tecnologias Empregadas**
HTML5: 
Estruturação semântica de todas as páginas, priorizando acessibilidade.

CSS3: 
Utilização de folhas de estilo externas modulares para separar responsabilidades e facilitar manutenção. Implementação de media queries para garantir responsividade plena.

JavaScript: 
Scripts simples e diretos para validação de formulários e simulação de interações dinâmicas ‒ deliberadamente dispensando frameworks para melhor clareza de código.

Imagens Otimizadas: 
Arquivos gráficos nos formatos JPEG, PNG e AVIF, balanceando qualidade visual e desempenho no carregamento em diferentes dispositivos.

**Padrões de Design, Usabilidade e Acessibilidade**
Responsividade:
Garantia de usabilidade plena em múltiplos tamanhos de tela por meio de media queries e grid flexível.

Acessibilidade:
Contraste rigorosamente testado, componentes navegáveis por teclado, fontes legíveis e comandos claros, promovendo inclusão digital.

Separação de Responsabilidades:
Cada página e componente possui estilos e scripts próprios, facilitando extensibilidade e manutenção ao longo do tempo.

Feedback Visual:
Mensagens claras para ações do usuário, minimizando ambiguidades e erros durante a navegação.

**Time de Desenvolvimento**
Marina:	
Estrutura inicial, arquitetura visual, estilização responsiva, tratamento de imagens

João Pedro:	
Lógica de formulários, validação de dados, refinamento visual, documentação e revisão

**Linha do Tempo e Sugestão de Históricos de Commits**

Data	        Desenvolvedor	           Descrição
01/05/2024	     Marina	             Estrutura inicial do projeto
03/05/2024	    João Pedro	         Tela de login com upload de foto
06/05/2024	     Marina	             Página principal de agendamento
09/05/2024	    João Pedro	         Área de resultados (exames, laudos, receitas)
12/05/2024	     Marina	             CSS responsivo para múltiplos dispositivos
15/05/2024	    João Pedro	         Refatoração JS e melhorias na experiência
18/05/2024	     Marina	             Adição de imagens ilustrativas e receitas
21/05/2024	    João Pedro	         Revisão final e ajustes gerais

**Consideração Geral e Limitação**
Este projeto não processa, armazena ou transmite dados reais de pacientes
e não está integrado a nenhum sistema real de prontuário eletrônico, sendo estritamente voltado para aprendizado, testes e apresentações acadêmicas.

**Política de Privacidade e Segurança**
Simulação Controlada:
Todos os dados e imagens utilizadas são fictícios ou de domínio público.

**Licença**
Este projeto é aberto, voltado para disseminação de conhecimento, compartilhamento de boas práticas e estímulo à inovação em saúde digital.
Licenciado para uso livre em ambientes de ensino, pesquisa e desenvolvimento acadêmico.
Credite autores em reproduções ou derivados sempre que possível.
