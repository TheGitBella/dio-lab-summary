### **Segurança e Identidade no Azure**

O Azure oferece recursos robustos de segurança e identidade para proteger dados, controlar acessos e gerenciar permissões de usuários em sistemas na nuvem. Segurança e identidade são essenciais para garantir a integridade e disponibilidade dos recursos.

### **Microsoft Entra ID (antigo Azure Active Directory - Azure AD)**

O **Microsoft Entra ID** é a nova denominação do serviço de identidade do Azure, anteriormente conhecido como **Azure Active Directory (Azure AD)**. Este serviço centraliza a autenticação e autorização, permitindo o controle de acessos e fornecendo uma solução de identidade segura para usuários e aplicativos.

### **Usuários no Azure**

- **Tipo de Membro**: Classifica os usuários com base no nível de acesso e integração dentro da organização.
- **Identidade**: Gerencia as identidades dos usuários e aplica políticas para acesso seguro.
- **Sincronização**: Permite que as contas de usuários locais sejam refletidas no Entra ID, garantindo consistência.
- **Validações de Login**: Configurações para autenticar usuários e proteger contra tentativas de login suspeitas.
- **Exclusão e Restauração Após 30 Dias**: Usuários excluídos podem ser restaurados no prazo de 30 dias, mantendo informações e configurações.
- **Troca de Senhas**: Política que facilita ou obriga a atualização de senhas.
- **Criação e Convite de Usuários Externos**: Permite a criação de contas para parceiros e o convite de usuários externos para colaborar com segurança.

### **Grupos e Usuários Externos**

Os grupos são usados para organizar usuários, definir políticas e aplicar regras de acesso de forma eficiente. Usuários externos, ou convidados, recebem permissões específicas para colaborar sem ter acesso completo à rede interna.

### **Regras e Permissionamento entre Contas**

Regras de permissionamento permitem controlar os direitos dos usuários, definindo o que eles podem ou não acessar em relação a outras contas e serviços. Isso assegura que o acesso seja segmentado e controlado.

### **Domínio da Empresa**

O domínio corporativo centraliza e autentica usuários dentro de uma organização, integrando-se ao Entra ID para melhorar a segurança e gestão de identidades.

### **Microsoft Defender for Cloud e SOC**

O **Microsoft Defender for Cloud** oferece proteção abrangente para cargas de trabalho, detectando ameaças em tempo real e ajudando a aplicar as melhores práticas de segurança. A **área de SOC** (Security Operations Center) monitora continuamente o ambiente, respondendo a ameaças e protegendo contra vulnerabilidades.

### **Conectar GitHub e GitLab**

O Azure permite integrar repositórios GitHub e GitLab, facilitando o DevOps e a automação de processos de CI/CD (integração contínua/entrega contínua). Essa integração permite que desenvolvedores implementem código com segurança e colaborem em um ambiente controlado.

---

### **Security and Identity in Azure**

Azure offers robust security and identity features to protect data, control access, and manage user permissions in cloud systems. Security and identity are essential to ensure the integrity and availability of resources.

### **Microsoft Entra ID (formerly Azure Active Directory - Azure AD)**

**Microsoft Entra ID** is the new name for Azure’s identity service, previously known as **Azure Active Directory (Azure AD)**. This service centralizes authentication and authorization, enabling access control and providing a secure identity solution for users and applications.

### **Users in Azure**

- **Member Type**: Classifies users based on their level of access and integration within the organization.
- **Identity**: Manages user identities and applies policies for secure access.
- **Synchronization**: Allows on-premises user accounts to be reflected in Entra ID for consistency.
- **Login Validations**: Settings to authenticate users and protect against suspicious login attempts.
- **Deletion and Restoration After 30 Days**: Deleted users can be restored within 30 days, preserving information and settings.
- **Password Reset**: Policy that facilitates or enforces password updates.
- **Creation and Invitation of External Users**: Enables the creation of accounts for partners and the invitation of external users to collaborate securely.

### **Groups and External Users**

Groups are used to organize users, define policies, and apply access rules efficiently. External users, or guests, receive specific permissions to collaborate without full access to the internal network.

### **Rules and Permissioning Between Accounts**

Permissioning rules allow user rights control, defining what they can or cannot access regarding other accounts and services. This ensures segmented and controlled access.

### **Company Domain**

The corporate domain centralizes and authenticates users within an organization, integrating with Entra ID to improve security and identity management.

### **Microsoft Defender for Cloud and SOC**

**Microsoft Defender for Cloud** provides comprehensive protection for workloads, detecting real-time threats and helping to apply best security practices. The **SOC area** (Security Operations Center) continuously monitors the environment, responding to threats and protecting against vulnerabilities.

### **Connecting GitHub and GitLab**

Azure allows integration with GitHub and GitLab repositories, enabling DevOps and CI/CD (Continuous Integration/Continuous Delivery) automation. This integration allows developers to deploy code securely and collaborate in a controlled environment.
