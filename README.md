# aula-Pipelines-21-03

-Desenvolvimento (Dev) e Operações (Ops)
-Cultura e conjunto de práticas
-Tenta mitigar problemas de:
*Comunicação entre as equipes
*Dependência de um do outro
*Diversos cenários que podem trazer atrasos e/ou problemas

-Princípios:
*Continuous Integration (CI)
*Continuous Delivery (CD)

INTEGRAÇÃO CONTÍNUA (CI)
-Garantir que as features trabalhadas por diversas pessoas funcionem e estejam nos padrões na branch principal

-Práticas comuns do CI:
*Testes Unitários e de Integração
*Verificação de qualidade, segurança e validações

-Alguams ferramentas:
*GitLab CI/CD
*GitHub Actions
*Jenkins
*Azure

ENTREGA CONTÍNUA (CD)
-Focado na entrega; Busca garantir que o software possa ser lançado a qualquer momento
-Automatizar o processo de lançamento do Software de forma confiável

BENEFÍCIOS DO CI/CD
-Detecção precoce de problemas (vai pegar problemas antes que eu faça o deploy)
-Reduz riscos na integração e deploy
-Torna consistentes os processos repetitivos que não necessariamente precisam de um humano no meio

Conceitos do GitHub Actions
-Workflow: É o processo que executa os trabalhos; São um arquivo YAML; É armazenado junto no seu repositório
-Events: Atividade no repositório que aciona uma execução no workflow (ex: quando alguém cria um pull)
-Job: Conjunto de etapas (Steps) que são executados em um runner;
-Actions: 
-Runners: As máquinas/servidor que executa os workflows; Um job é executado por vez; O GitHub tem runners para cada sistema operacional
*GitHub Hosted Runners: Gratuitos; Mais simples; Recursos limitados; podem ter filas.
*Self Hosted Runners: Uso da própria máquina, transferindo o workflow via um agent pra sua máquina; Atualização, gestão, recursos e configuração 100% por sua conta.
*Large Hosted Runners: Pagas; Maiores recursos; Somente para usuários Pro.

# Prática
-Criar um repositório e clonar
-Baixar extensão do Github Actions
-