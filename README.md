```mermaid
gantt
    title Cronograma Gantt - Sistema TechConnect Solutions
    %% Define o formato do eixo para exibir "Semana X"
    axisFormat Semana %U

    %% -- FASE 1 --
    section Módulo de Login (Entrega Semana 3)
    Requisitos e Análise    :done,   id_req, 1w
    Design e Documentação   :done,   id_doc, after id_req, 1w
    Desenvolvimento (Login) :active, id_dev1, after id_doc, 1w
    Testes (Login)          :        id_tst1, after id_dev1, 3d
    Entrega 1               :milestone, after id_tst1, 0d

    %% -- FASE 2 --
    section CRUD de Empresas (Entrega Semana 6)
    Desenvolvimento (CRUD)  :active, id_dev2, after id_tst1, 2w
    Testes de Integração (CRUD) :    id_tst2, after id_dev2, 1w
    Entrega 2               :milestone, after id_tst2, 0d

    %% -- FASE 3 --
    section Upload de Logotipo (Entrega Semana 8)
    Desenvolvimento (Upload)  :active, id_dev3, after id_tst2, 2w
    Testes (Upload)           :        id_tst3, after id_dev3, 3d
    Entrega 3                 :milestone, after id_tst3, 0d

    %% -- FASE 4 --
    section Relatórios PDF/Excel (Entrega Semana 10)
    Desenvolvimento (Relatórios) :active, id_dev4, after id_tst3, 2w
    Testes (Relatórios)          :        id_tst4, after id_dev4, 3d
    Entrega 4                    :milestone, after id_tst4, 0d
    
    %% -- FASE 5 --
    section Painel Administrativo (Entrega Semana 12)
    Desenvolvimento (Admin)  :active, id_dev5, after id_tst4, 2w
    Testes (Admin)           :        id_tst5, after id_dev5, 3d
    Entrega 5                :milestone, after id_tst5, 0d

    %% -- FASE FINAL --
    section Finalização e Entrega (Semanas 13-24)
    Testes Finais de Integração :crit, active, id_tst_final, after id_tst5, 6w
    Testes de Usabilidade       :crit, active, id_usab, after id_tst_final, 2w
    Implantação e Treinamento   :crit, active, id_deploy, after id_usab, 2w
    Entrega Final               :milestone, after id_deploy, 0d
```
