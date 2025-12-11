Quiz de Futebol: Rumo ao Milhão
Visão Geral do Projeto
Esta aplicação web consiste num jogo de trivia interativo focado no universo do futebol. A lógica do jogo emula o formato televisivo "Quem Quer Ser Milionário", adaptado para um ambiente digital. O objetivo é proporcionar uma experiência de entretenimento que testa o conhecimento desportivo do utilizador, mantendo padrões elevados de usabilidade e performance.

O projeto foi desenvolvido com foco na fiabilidade do código, baixo custo de implementação (tecnologias web standard) e segurança na execução do lado do cliente.

Shutterstock

Funcionalidades Principais
Lógica de Progressão: Sistema de perguntas com dificuldade incremental. O jogo termina se o utilizador errar uma resposta ou atingir o prémio máximo (fictício).

Ajudas Estratégicas (Lifelines): Implementação de algoritmos para três tipos de ajuda:

50:50: Remove duas respostas incorretas aleatoriamente.

Ajuda do Público: Simula estatísticas de votação baseadas na probabilidade da resposta correta.

Telefonema: Simulação de uma dica externa.

Interface Responsiva: Design adaptável a diferentes dispositivos (Desktop, Tablet e Mobile), garantindo consistência visual e funcional.

Gestão de Estado: Controlo de pontuação e níveis em tempo real via JavaScript.

Arquitetura Técnica
A stack tecnológica foi selecionada para garantir a máxima compatibilidade entre browsers, facilidade de manutenção e ausência de custos de licenciamento ou servidores backend complexos.

HTML5: Estruturação semântica do conteúdo.

CSS3: Estilização e layout (Flexbox/Grid), focado na experiência do utilizador (UX).

JavaScript (ES6+): Lógica de negócio, manipulação do DOM e gestão de eventos.

Dados: As perguntas são armazenadas num formato JSON estruturado, permitindo fácil atualização e expansão da base de dados sem alterar o código-fonte principal.

Requisitos de Sistema
Para executar este projeto localmente, apenas é necessário um navegador web moderno (Google Chrome, Mozilla Firefox, Edge ou Safari). Não existem dependências de instalação de software adicional.

Instalação e Execução
Siga os passos abaixo para implementar o projeto no seu ambiente local:

Clonar o Repositório:

Bash

git clone https://github.com/o-seu-utilizador/quiz-futebol-milionaria.git
Aceder ao Diretório:

Bash

cd quiz-futebol-milionaria
Executar: Abra o ficheiro index.html diretamente no seu navegador de preferência.

Segurança e Qualidade
Validação: O código segue as melhores práticas de desenvolvimento web, garantindo que não existem injeções de scripts maliciosos.

Performance: O carregamento é imediato devido à ausência de frameworks pesadas, otimizando o consumo de dados do utilizador.

Fiabilidade: A lógica do jogo foi testada para impedir comportamentos inesperados (bugs) durante a utilização das ajudas ou transição de perguntas.

Roteiro de Desenvolvimento (Roadmap)
Visando a inovação e o crescimento do projeto, estão planeadas as seguintes atualizações futuras:

Integração de API: Conexão a uma API externa de futebol para gerar perguntas baseadas em eventos reais e atualizados.

Modo Multijogador: Implementação de WebSockets para permitir competições em tempo real entre utilizadores.

Sistema de Login e Ranking: Base de dados para persistência de recordes e perfis de utilizador.

Monetização: Espaços preparados na interface para inserção de publicidade programática (Google AdSense) sem intrusão na jogabilidade.

Licença
Este projeto é distribuído sob a licença MIT. Consulte o ficheiro LICENSE para mais informações.

Contacto e Suporte
Para questões técnicas ou propostas de parceria, por favor abra uma Issue neste repositório ou contacte o administrador do projeto.

Desenvolvido por Fábio Alexandre Bastos Santos.
