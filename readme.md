### Controle de Versões (Version Control System - VCS)
Um controle de versões (Version Control System - VCS) é um sistema que rastreia e gerencia alterações em arquivos ao longo do tempo, permitindo que você volte para versões anteriores, compare mudanças e trabalhe em equipe de forma eficiente. Ele é essencial para desenvolvimento de software, permitindo que desenvolvedores acompanhem o progresso do código, reverter erros e colaborar em projetos. 
O controle de versões é uma ferramenta indispensável no desenvolvimento de software e em diversas outras áreas onde a colaboração e o gerenciamento de alterações são cruciais.
### Cite 5 Vantagens em utilizar um Controle de Versões:
1.	Rastreamento de Histórico e Recuperação de Versões: Permite visualizar todas as alterações feitas nos arquivos ao longo do tempo, quem as fez e quando. Isso facilita a identificação de bugs, a compreensão da evolução do projeto e, o mais importante, a capacidade de reverter para qualquer versão anterior do código ou dos arquivos, caso haja um erro ou necessidade de desfazer uma alteração.
2.	Colaboração Eficiente: Múltiplos desenvolvedores podem trabalhar no mesmo projeto simultaneamente sem sobrescrever o trabalho uns dos outros. O VCS gerencia as fusões de código (merges), alertando sobre conflitos e ajudando a resolvê-los, garantindo que as contribuições de todos sejam integradas de forma coesa.
3.	Ramificação (Branching) e Mesclagem (Merging): Possibilita a criação de "ramos" ou "branches" isolados do código principal para desenvolver novas funcionalidades, corrigir bugs ou experimentar ideias sem afetar a versão estável do projeto. Uma vez que o trabalho no branch é concluído e testado, ele pode ser mesclado de volta ao código principal.
4.	Gerenciamento de Conflitos: Quando dois ou mais desenvolvedores alteram a mesma parte de um arquivo, o VCS detecta esses conflitos e fornece ferramentas para ajudar a resolver essas divergências manualmente, garantindo que nenhuma alteração seja perdida.
5.	Auditoria e Responsabilidade: O registro detalhado de todas as alterações, incluindo o autor e a mensagem de commit, promove a responsabilidade da equipe. É fácil identificar quem fez o quê, o que é valioso para a revisão de código, depuração e garantia de qualidade.
### Cite 3 Exemplos de Sistemas de Controle de Versão:
1. Git: Atualmente o sistema de controle de versão distribuído mais popular e amplamente utilizado. É conhecido por sua velocidade, flexibilidade, robustez e capacidade de lidar com projetos de todos os tamanhos.
2. SVN (Subversion): Um sistema de controle de versão centralizado que foi muito popular antes da ascensão do Git. Embora ainda seja usado em alguns projetos legados, sua adoção tem diminuído significativamente em favor de sistemas distribuídos.
3. Mercurial (Hg): Outro sistema de controle de versão distribuído, similar ao Git em muitos aspectos, mas frequentemente considerado mais simples de aprender e usar para iniciantes. É menos difundido que o Git, mas tem sua própria comunidade e é utilizado em diversos projetos.

-------------------------

### Desafio 2

O "Desafio 02" sobre Programação Orientada a Objetos (POO) requer a criação de uma *branch* "desafio02" para responder, em um arquivo `README.md`, às seguintes questões:

1.  **Definição de POO e seus pilares:** POO organiza o código em "objetos" (instâncias de "classes" que definem atributos e comportamentos), modelando o mundo real. Promove modularidade, reutilização e manutenção. Seus pilares são Abstração, Encapsulamento, Herança e Polimorfismo.

2.  **Abstração:** Foco nos detalhes essenciais, ignorando complexidades. Exemplo: um `Carro` em um sistema, onde se importa com `cor`, `marca` e métodos como `ligar()`, abstraindo o funcionamento interno do motor.

3.  **Encapsulamento:** Proteção de dados através de métodos públicos. Exemplo: `saldo` de uma `ContaBancaria` acessível apenas por `depositar()` e `sacar()`, garantindo a integridade.

4.  **Herança:** Reutilização de código e criação de hierarquias. Exemplo: classes `Leao`, `Elefante`, `Macaco` herdando atributos e métodos comuns da classe `Animal`.

5.  **Polimorfismo:** Capacidade de diferentes objetos responderem ao mesmo método de maneiras distintas. Exemplo: um método `apresentar()` em `DocumentoPDF`, `DocumentoWord` e `DocumentoTextoPuro` agindo de forma específica para cada tipo.

6.  **Vantagens da POO:** Reutilização de código, modularidade, flexibilidade, extensibilidade, facilidade de manutenção e modelagem mais intuitiva do mundo real.

-----