 ```mermaid
gantt
    title Sistema de Cadastro de Empresas Parceiras - TechConnect Solutions
    dateFormat YYYY-MM-DD
    excludes weekends
    
    section Planejamento Inicial
    Levantamento de Requisitos     :done, req, 2025-01-06, 7d
    Documentação Funcional          :done, doc, 2025-01-13, 7d
    
    section Design e Infraestrutura
    Design de Interface             :active, ui, 2025-01-13, 14d
    Config. Ambiente e Banco        :config, 2025-01-13, 7d
    
    section Sprint 1 - Autenticação
    Módulo de Login                 :login, 2025-01-20, 7d
    
    section Sprint 2 - Gestão de Empresas
    CRUD de Empresas                :crud, 2025-01-27, 21d
    
    section Sprint 3 - Upload
    Upload de Logotipo              :upload, 2025-02-17, 14d
    
    section Sprint 4 - Relatórios
    Relatórios PDF/Excel            :relat, 2025-03-03, 14d
    
    section Sprint 5 - Administração
    Painel Administrativo           :painel, 2025-03-17, 14d
    
    section Qualidade e Entrega
    Testes Contínuos (paralelo)     :testes, 2025-01-20, 70d
    Testes de Usabilidade           :usab, 2025-03-31, 14d
    Ajustes e Correções             :ajustes, 2025-04-14, 21d
    Implantação Final               :crit, deploy, 2025-05-05, 7d
```
