# GitHub Advanced Security (GHAS)

### > [GitHub · Enterprise Application Security](https://github.com/enterprise/advanced-security)

### > [How to try GitHub Advanced Security](https://resources.github.com/security/tools/ghas-trial/)

### > [Essentials of GitHub Advanced Security](https://resources.github.com/learn/pathways/security/essentials/essentials-github-advanced-security/)

### > [Github Advanced Security Review](https://perd1x.medium.com/github-advanced-security-review-28a8f1333fc6)

## Recursos ofertados

- <span style="font-size: 17px;">**Code Scanning:** Além da verificar erros de codificação, também verifica o código em busca de vulnerabilidades de segurança, como ataques do tipo **SQL injection** e **cross-site scripting (XSS)**, utilizando **[CodeQL](https://docs.github.com/pt/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql)** ou outras ferramentas externas. Ajuda a identificar e corrigir problemas antes de impactarem a produção.

- <span style="font-size: 17px;">**[CodeQL CLI](https://docs.github.com/pt/code-security/codeql-cli/getting-started-with-the-codeql-cli/about-the-codeql-cli):** Permite executar processos CodeQL localmente para análise de segurança e código em projetos de software, gerando resultados que podem ser carregados no GitHub para uma análise mais profunda.

- <span style="font-size: 17px;">**Secret Scanning:** **[Detecta segredos](https://docs.github.com/pt/code-security/secret-scanning/introduction/about-secret-scanning)** como chaves e tokens em repositórios privados. Quando a **[proteção de push](https://docs.github.com/pt/code-security/secret-scanning/introduction/about-push-protection)** está ativada, o GitHub verifica se segredos estão presentes ao fazer push, protegendo os dados confidenciais de serem expostos.

- <span style="font-size: 17px;">**Regras de Triagem Automática Personalizadas:** Facilita o gerenciamento de alertas do **[Dependabot](https://docs.github.com/pt/code-security/dependabot/dependabot-alerts/about-dependabot-alerts)** em escala, permitindo ignorar, adiar ou acionar atualizações de segurança automaticamente com base em regras definidas.

- <span style="font-size: 17px;">**Revisão de Dependência:** **[Exibe o impacto das alterações nas dependências](https://docs.github.com/pt/code-security/supply-chain-security/understanding-your-software-supply-chain/about-dependency-review)** e fornece detalhes sobre versões vulneráveis antes de aprovar uma pull request, garantindo uma visão completa dos riscos antes de mesclar o código.

### > [Sobre a Segurança Avançada do GitHub](https://docs.github.com/pt/get-started/learning-about-github/about-github-advanced-security)

## Desvantagens

- <span style="font-size: 17px;">Pode não ser tão eficiente em identificar **todas** as vulnerabilidades potenciais no código. Por ser uma ferramenta de **aprendizado de máquina**, a ferramenta pode não ser capaz de detectar todos os possíveis problemas de segurança e pode haver algumas vulnerabilidades que ela não identifica.

- <span style="font-size: 17px;">Projetado especificamente para uso com repositórios GitHub.

- <span style="font-size: 17px;">Requer uma assinatura do plano GitHub Enterprise.

## Disponibilidade dos recursos

|               | <p align="center"><span style="font-size: 17px;">Repositório público | <p align="center"><span style="font-size: 17px;">Repositório privado sem Advanced Security  | <p align="center"><span style="font-size: 17px;">Repositório privado com Advanced Security |
| ------------- | ------------- | ------------- | ------------- |
| <p align="center"><span style="font-size: 16px;">Varredura de código  | <p align="center"><span style="font-size: 16px;">✔️  | <p align="center"><span style="font-size: 16px;">❌  | <p align="center"><span style="font-size: 16px;">✔️  |
| <p align="center"><span style="font-size: 16px;">CodeQL CLI  | <p align="center"><span style="font-size: 16px;">✔️  | <p align="center"><span style="font-size: 16px;">❌  | <p align="center"><span style="font-size: 16px;">✔️  |
| <p align="center"><span style="font-size: 16px;">Verificação de segredo | <p align="center"><span style="font-size: 16px;">✔️  | <p align="center"><span style="font-size: 16px;">❌  | <p align="center"><span style="font-size: 16px;">✔️  |
| <p align="center"><span style="font-size: 16px;">Regras de triagem automática personalizadas  | <p align="center"><span style="font-size: 16px;">✔️  | <p align="center"><span style="font-size: 16px;">❌  | <p align="center"><span style="font-size: 16px;">✔️  |
| <p align="center"><span style="font-size: 16px;">Análise de dependência  | <p align="center"><span style="font-size: 16px;">✔️  | <p align="center"><span style="font-size: 16px;">❌  | <p align="center"><span style="font-size: 16px;">✔️  |

### Para acessar esses recursos em repositórios privados, é necessário possuir uma conta [GitHub Enterprise](https://docs.github.com/pt/get-started/learning-about-github/githubs-plans#github-enterprise), podendo ser do tipo [GitHub Enterprise Cloud](https://docs.github.com/pt/enterprise-cloud@latest/admin/overview/about-github-enterprise-cloud) ou [GitHub Enterprise Server](https://docs.github.com/pt/enterprise-server@3.14/admin/overview/about-github-enterprise-server). Confira a [página de preços](https://github.com/pricing) para saber mais sobre os planos.

### > [GitHub Enterprise Cloud | Como gerenciar licenças para o GitHub Advanced Security](https://docs.github.com/pt/enterprise-cloud@latest/billing/managing-billing-for-your-products/managing-billing-for-github-advanced-security/managing-your-github-advanced-security-licensing)

### > [GitHub Enterprise Server | Como habilitar a Segurança Avançada do GitHub para sua empresa](https://docs.github.com/pt/enterprise-server@3.14/admin/managing-code-security/managing-github-advanced-security-for-your-enterprise/enabling-github-advanced-security-for-your-enterprise)

## CodeQL: Suporte a linguagens

### O CodeQL dá suporte a linguagens compiladas e interpretadas e pode encontrar vulnerabilidades e erros no código escrito nas linguagens compatíveis.

- <span style="font-size: 16px;">C/C++
- <span style="font-size: 16px;">C#
- <span style="font-size: 16px;">Ir
- <span style="font-size: 16px;">Java/Kotlin
- <span style="font-size: 16px;">JavaScript/TypeScript
- <span style="font-size: 16px;">Python
- <span style="font-size: 16px;">Ruby
- <span style="font-size: 16px;">Swift

### Para linguagens que não possuem suporte nativo, como **PHP**, há a opção de escolher outros algoritmos de análise por meio do [GitHub MarketPlace](https://github.com/marketplace). Saiba mais sobre [nesse artigo](https://github.blog/news-insights/product-news/new-code-scanning-integrations-open-source-security-tools/).

### > [Como definir a configuração avançada para verificação de código](https://docs.github.com/pt/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning#configuring-code-scanning-using-third-party-actions)

## Avaliação gratuita

### É possível configurar uma versão de avaliação gratuita do plano GitHub Enterprise Cloud e GitHub Advanced Security (GHAS):

### > [Configurar uma versão de avaliação do GitHub Enterprise Cloud](https://docs.github.com/pt/enterprise-cloud@latest/admin/overview/setting-up-a-trial-of-github-enterprise-cloud)

### > [Como configurar uma avaliação gratuita do GitHub Advanced Security](https://docs.github.com/pt/enterprise-cloud@latest/billing/managing-billing-for-your-products/managing-billing-for-github-advanced-security/setting-up-a-trial-of-github-advanced-security)

## Alternativas

- <span style="font-size: 17px;">[GitLab Ultimate](https://about.gitlab.com/pricing/ultimate/)
- <span style="font-size: 17px;">[Checkmarx](https://checkmarx.com/)
- <span style="font-size: 17px;">[Snyk](https://snyk.io/pt-BR/)

## Breve comparativo

| <p align="center"><span style="font-size: 17px;">Ferramenta | <p align="center"><span style="font-size: 17px;">GitHub Advanced Security (GHAS) | <p align="center"><span style="font-size: 17px;">GitLab Ultimate<div> | <p align="center"><span style="font-size: 17px;">Checkmarx | <p align="center"><span style="font-size: 17px;">Snyk |
|------------|---------------------------------|-----------------|-----------|------|
| <p align="center"><span style="font-size: 16px;">**Foco principal** | <p align="center"><span style="font-size: 16px;">Segurança integrada no ciclo de vida de desenvolvimento no GitHub | <p align="center"><span style="font-size: 16px;">Plataforma DevSecOps integrada | <p align="center"><span style="font-size: 16px;">SAST com especialização em código-fonte seguro | <p align="center"><span style="font-size: 16px;">Foco em análise de dependências e segurança de código para múltiplas linguagens |
| <p align="center"><span style="font-size: 16px;">**Code Scanning** | <p align="center"><span style="font-size: 16px;">CodeQL para detectar vulnerabilidades de segurança em código, além de suporte a ferramentas externas de análise | <p align="center"><span style="font-size: 16px;">SAST, DAST e análise de contêineres embutida na plataforma | <p align="center"><span style="font-size: 16px;">SAST avançado com forte personalização e políticas de segurança | <p align="center"><span style="font-size: 16px;">Análise robusta de dependências e vulnerabilidades de código |
| <p align="center"><span style="font-size: 16px;">**Secret Scanning** | <p align="center"><span style="font-size: 16px;">Verificação de segredos integrada, com proteção de push ativa | <p align="center"><span style="font-size: 16px;">Detecção e monitoramento de segredos | <p align="center"><span style="font-size: 16px;">Foco primário em segurança de código e conformidade, sem foco específico em segredos | <p align="center"><span style="font-size: 16px;">Escaneamento de segredos e integração de gerenciamento de credenciais |
| <p align="center"><span style="font-size: 16px;">**Gestão de Dependências** | <p align="center"><span style="font-size: 16px;">Revisão detalhada de dependências, com atualização automática via Dependabot | <p align="center"><span style="font-size: 16px;">Atualização de dependências e detecção de vulnerabilidades | <p align="center"><span style="font-size: 16px;">Integração com ferramentas de terceiros para vulnerabilidades de dependências | <p align="center"><span style="font-size: 16px;">Ampla cobertura de vulnerabilidades em dependências com integração contínua |
| <p align="center"><span style="font-size: 16px;">**Escalabilidade e Integração** | <p align="center"><span style="font-size: 16px;">Ótima integração com repositórios GitHub, exigindo GitHub Enterprise | <p align="center"><span style="font-size: 16px;">Ferramentas completas para repositórios GitLab e ampla escalabilidade | <p align="center"><span style="font-size: 16px;">Funciona com várias plataformas e pode ser integrado a pipelines existentes | <p align="center"><span style="font-size: 16px;">Escalabilidade para diversos ambientes com foco em integração DevSecOps |

## Referências

- https://github.com/enterprise/advanced-security

- https://resources.github.com/security/tools/ghas-trial/

- https://resources.github.com/learn/pathways/security/essentials/essentials-github-advanced-security/

- https://perd1x.medium.com/github-advanced-security-review-28a8f1333fc6

- https://docs.github.com/pt/get-started/learning-about-github/about-github-advanced-security

- https://docs.github.com/pt/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql

- https://docs.github.com/pt/enterprise-cloud@latest/billing/managing-billing-for-your-products/managing-billing-for-github-advanced-security/managing-your-github-advanced-security-licensing

- https://docs.github.com/pt/enterprise-server@3.14/admin/managing-code-security/managing-github-advanced-security-for-your-enterprise/enabling-github-advanced-security-for-your-enterprise

- https://github.blog/news-insights/product-news/new-code-scanning-integrations-open-source-security-tools/

- https://github.blog/news-insights/product-news/new-code-scanning-integrations-open-source-security-tools/

- https://docs.github.com/pt/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning#configuring-code-scanning-using-third-party-actions

- https://docs.github.com/pt/enterprise-cloud@latest/admin/overview/setting-up-a-trial-of-github-enterprise-cloud

- https://docs.github.com/pt/enterprise-cloud@latest/billing/managing-billing-for-your-products/managing-billing-for-github-advanced-security/setting-up-a-trial-of-github-advanced-security

- https://github.com/marketplace