#📊 Relatório de Avaliação Heurística: Vercel
Site: vercel.com

## Funcionalidade: Fluxo de Deploy de Repositório Git.

1. Visibilidade do status do sistema
Análise: Excelente. Durante o deploy, a Vercel exibe um terminal em tempo real (Build Logs) e uma barra de progresso visual (Building, Assigning Domains, etc.).

Por que funciona: O usuário nunca fica na dúvida se o sistema travou ou se o código está sendo compilado.

2. Correspondência entre o sistema e o mundo real
Análise: Boa aplicação. Termos como "Production", "Preview", "Branch" e "Deployment" são o padrão do "mundo real" dos desenvolvedores.

Destaque: O uso de miniaturas (screenshots) do site após o deploy facilita o reconhecimento imediato do projeto.

3. Controle e liberdade do usuário
Análise: Boa aplicação. Se você iniciar um deploy por erro, há um botão visível de "Cancel". Se um deploy deu errado, é fácil fazer um "Rollback" para a versão anterior com um clique.

4. Consistência e padrões
Análise: Excelente. A interface segue o padrão de design da Vercel (Geist Design) em todo o dashboard. O menu superior e as configurações mantêm a mesma posição em todos os projetos.

5. Prevenção de erros
Análise: Boa prática identificada. Antes de falhar o build, a Vercel analisa o package.json e sugere o framework correto (Next.js, Vite, etc.).

Melhoria sugerida: Às vezes, o deploy falha por falta de Variáveis de Ambiente. O sistema poderia avisar antes de iniciar o build que variáveis usadas no código não foram definidas no painel.

6. Reconhecimento em vez de memorização
Análise: Ponto forte. Ao conectar o GitHub, a Vercel lista seus repositórios recentes. Você não precisa digitar o nome do repo; basta selecionar na lista visual.

7. Flexibilidade e eficiência de uso
Análise: Excelente. Usuários novos usam a interface web. Usuários avançados (como você, Natan) usam a Vercel CLI no terminal para dar comandos rápidos, ignorando a interface visual.

8. Estética e design minimalista
Análise: Referência no mercado. O uso de espaços em branco, tipografia limpa e ausência de elementos desnecessários foca totalmente no que importa: o status da sua aplicação.

9. Ajude os usuários a reconhecer e corrigir erros
Análise: Ponto de atenção. Quando o build falha, o log é técnico. Para um iniciante, pode ser difícil entender o erro.

Solução Vercel: Eles adicionaram recentemente um botão de "Dica de IA" para explicar o erro do log e sugerir a correção no código.

10. Ajuda e documentação
Análise: Excelente. A documentação da Vercel é contextual. Ao lado de configurações complexas (como Edge Functions), existe sempre um link direto para a página específica do manual.

## Resumo para a aula (5 minutos)
Conclusão: A Vercel é um exemplo de sistema que reduz a "carga cognitiva" do desenvolvedor. Ela transforma algo complexo (configurar servidores) em algo visual e transparente.

O "Pulo do Gato": O maior trunfo de usabilidade deles é a Heurística #1 (Status). Ver o build acontecendo e receber uma URL instantânea gera uma recompensa imediata ao usuário.
