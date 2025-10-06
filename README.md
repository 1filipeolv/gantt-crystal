 ```mermaid
gantt
title Cronograma Gantt - Sistema TechConnect Solutions
axisFormat Semana %U

section Módulo de Login (Entrega Semana 3)
Requisitos e Análise        :id_req, done, 1w
Design e Documentação       :id_doc, done, after id_req, 1w
Desenvolvimento (Login)     :id_dev1, active, after id_doc, 1w
Testes (Login)              :id_tst1, after id_dev1, 3d
Entrega 1                   :milestone, after id_tst1, 0d

section CRUD de Empresas (Entrega Semana 6)
Desenvolvimento (CRUD)      :id_dev2, active, after id_tst1, 2w
Testes de Integração (CRUD) :id_tst2, after id_dev2, 1w
Entrega 2                   :milestone, after id_tst2, 0d

section Upload de Logotipo (Entrega Semana 8)
Desenvolvimento (Upload)    :id_dev3, active, after id_tst2, 2w
Testes (Upload)             :id_tst3, after id_dev3, 3d
Entrega 3                   :milestone, after id_tst3, 0d

section Relatórios PDF/Excel (Entrega Semana 10)
Desenvolvimento (Relatórios):id_dev4, active, after id_tst3, 2w
Testes (Relatórios)         :id_tst4, after id_dev4, 3d
Entrega 4                   :milestone, after id_tst4, 0d

section Painel Administrativo (Entrega Semana 12)
Desenvolvimento (Admin)     :id_dev5, active, after id_tst4, 2w
Testes (Admin)              :id_tst5, after id_dev5, 3d
Entrega 5                   :milestone, after id_tst5, 0d

section Finalização e Entrega (Semanas 13-24)
Testes Finais de Integração :id_tst_final, crit, active, after id_tst5, 6w
Testes de Usabilidade       :id_usab, crit, active, after id_tst_final, 2w
Implantação e Treinamento   :id_deploy, crit, active, after id_usab, 2w
Entrega Final               :milestone, after id_deploy, 0d
```
