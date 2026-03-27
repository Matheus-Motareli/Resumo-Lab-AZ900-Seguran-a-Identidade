# Resumo-Lab-AZ900-Seguran-a-Identidade

Este repositório contém o resumo prático do laboratório focado na navegação e compreensão das principais ferramentas de gerenciamento de identidade no Microsoft Azure, utilizando o Microsoft Entra ID (antigo Azure AD).

A imagem abaixo mostra o painel principal ("Overview") que exploramos no laboratório:

<img src="path/to/sua/imagem.png" alt="Painel Principal do Microsoft Entra ID" width="600px"/>

## Principais Recursos e Categorias Exploradas

A professora detalhou as opções visíveis no menu lateral esquerdo (visível na imagem), que são fundamentais para o gerenciamento do dia a dia:

### 1. Visão Geral e Ferramentas de Ajuda (Overview)
* **Overview (Visão Geral):** Como mostrado na imagem, este é o ponto de partida. Ele exibe informações básicas sobre o Tenant (como o Nome, Tenant ID e ID do Objeto), além de um resumo do estado dos serviços.
* **Diagnose and solve problems (Diagnosticar e resolver problemas):** Uma ferramenta de autoatendimento baseada em IA para identificar rapidamente problemas comuns de autenticação ou configuração.

---

### 2. Gerenciamento de Identidades e Acessos (Manage)
Esta é a seção mais acessada para a administração cotidiana, visível logo abaixo na imagem:

* **Users (Usuários):** Onde criamos, editamos e gerenciamos as contas de usuários (on-premises sincronizados ou nuvem). *A professora abordou como essa é a base para qualquer acesso.*
* **Groups (Grupos):** Fundamental para aplicar políticas em escala. Explicado como agrupar usuários simplifica o gerenciamento de permissões.
* **External Identities (Identidades Externas):** Abordado como configurar acesso seguro para convidados, fornecedores ou parceiros de negócios fora da organização (B2B).
* **Roles and administrators (Funções e administradores):** Onde definimos *o que* cada administrador pode fazer. Esta seção é a chave para o controle de acesso baseado em função (**RBAC**), garantindo que apenas as pessoas certas tenham as permissões corretas (menor privilégio).
