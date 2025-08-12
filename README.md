Este é um projeto de exemplo para a disciplina de Engenharia de Software que demonstra o uso de branches do Git e a implementação de um fluxo de Entrega Contínua (Continuous Delivery) para hospedar um site estático no Azure Static Web Apps.

Em desenvolvimento de software, um branch (ramificação), dentro de sistemas de controle de versão como Git, é uma cópia independente do código-fonte principal

Master main geralmente se refere à branch principal em um repositório Git, anteriormente chamada de master e agora mais frequentemente chamada de main. É onde o código-fonte principal do projeto reside e onde as alterações são integradas após serem desenvolvidas em outras branches

Entrega continua  = Toda vez que eu alterar algo no site altera a nuvem. Uma esteira de Deploy


No mundo do Git, as "branches" (ou ramificações) são essenciais para organizar o desenvolvimento de um projeto. Elas permitem que você trabalhe em novas funcionalidades ou correções de bugs de forma isolada, sem afetar a versão principal e estável do seu código.
Todo repositório Git possui uma branch principal, que serve como a fonte da verdade para o seu projeto. Historicamente, essa branch era chamada de master. No entanto, a comunidade de desenvolvimento de software tem se movido para adotar o nome main como o padrão.

Entrega Contínua (CD) é uma prática de desenvolvimento de software onde as alterações de código são automaticamente preparadas, testadas e liberadas para um ambiente de produção (ou homologação). O objetivo é tornar as entregas de novas versões mais rápidas, eficientes e confiáveis.

Neste projeto, configuramos um fluxo de CD utilizando duas ferramentas poderosas:

GitHub Actions: É a plataforma de automação integrada ao GitHub. Ela nos permite criar "fluxos de trabalho" (workflows) que são acionados por eventos no nosso repositório, como um push para uma branch específica.

Azure Static Web Apps: É um serviço da Microsoft Azure otimizado para hospedar sites estáticos (HTML, CSS, JavaScript e frameworks como React, Angular, Vue, etc.). Ele se integra perfeitamente com o GitHub Actions para automatizar o processo de build e publicação do site.
