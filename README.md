# FSMapper API

A **FSMapper API** é o componente central da plataforma **FSMapper**, responsável pelo **armazenamento, atualização e consulta** dos dados de mapeamento de sistemas de arquivos coletados pelo agente.

Desenvolvida em **Python**, a API fornece endpoints para persistir estruturas de diretórios, gerenciar metadados de arquivos e realizar consultas eficientes, atuando como a camada de negócio e acesso aos dados do sistema.

A arquitetura da FSMapper API prioriza:
- Separação de responsabilidades
- Facilidade de manutenção
- Escalabilidade
- Integração simples com múltiplos agentes

Este serviço é projetado para funcionar de forma desacoplada do agente, permitindo a expansão do sistema para múltiplos nós de coleta.
