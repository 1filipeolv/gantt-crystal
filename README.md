 ```mermaid
gantt
    title Sistema de Cadastro de Empresas Parceiras - TechConnect Solutions
    dateFormat YYYY-MM-DD
    
    section Planejamento
    Levantamento de Requisitos    :done, a1, 2024-01-01, 1w
    Documentação Funcional         :done, a2, after a1, 2w
    
    section Design
    Rascunhos das Telas            :done, a3, after a2, 1w
    Layout Definitivo              :done, a4, after a3, 2w
    
    section Desenvolvimento
    Configuração do Ambiente       :active, a5, after a4, 1w
    Criação do Banco de Dados      :a6, after a5, 1w
    Módulo de Login                :a7, after a6, 2w
    CRUD de Empresas               :a8, after a7, 2w
    Upload de Logotipo             :a9, after a8, 1w
    Relatórios PDF/Excel           :a10, after a9, 2w
    Painel Administrativo          :a11, after a10, 2w
    
    section Testes
    Testes Unitários               :a12, after a11, 2w
    Testes de Usabilidade          :a13, after a12, 1w
    
    section Entrega
    Implantação Final              :a14, after a13, 2w
```
