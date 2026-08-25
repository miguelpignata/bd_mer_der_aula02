# Projeto: Sistema de Gestão Veterinária

![MER DER Conceitual](./mer_der_conceitual.png)
![MER DER Lógico](./mer_der_logico.png)

## Dicionário de Dados

|Entidade | Atributo | Tipo | Tamanho | Descrição|
|:-:|:-:|:-:|:-:|:-:|
|Dono | ID_Dono | INT | - | Identificador do Dono|
|Dono | Nome | VARCHAR | 30 | Nome do Dono|
|Dono | CPF | VARCHAR | 14 | CPF do Dono|
|Dono | Telefone | VARCHAR | 15 | Telefone do Dono|
|Dono | Email | VARCHAR | 100 | Email do Dono|
|Veterinário | ID_Veterinário | INT | - |  Identificador do Veterinário|
|Veterinário | Nome | VARCHAR | 30 |  Nome do Veterinário|
|Veterinário | CRMV | VARCHAR | 20 | Registro Profissional|
|Veterinário | Especialidade | VARCHAR | 100 |  Especialidade Veterinário|
|Animal | ID_Animal | INT | - |  Identificador do Animal|
|Animal | Nome | VARCHAR | 30 |  Nome do Animal|
|Animal | Espécie | VARCHAR | 20 |  Espécie do Animal|
|Animal | Raça | VARCHAR | 30 | Raça do Animal|
|Animal | ID_Dono | INT | - | Identificador do Dono|
|Consulta | ID_Consulta | INT | - | Identificador da Consulta|
|Consulta | Data | DATE | - | Data da Consulta |
|Consulta | Horário | VARCHAR | 10 | Horário da Consulta|
|Consulta | Motivo | VARCHAR | 100 | Motivo da Consulta|
|Consulta | ID_Animal | INT | - | Identificador do Animal|
|Consulta | ID_Veterinário | INT | - | Identificador do Veterinário|


## Dados de teste em CSV
- [animal.csv](./animal.CSV)
- [consulta.csv](./consulta.CSV)
- [dono.csv](./dono.CSV)
- [veterinario.csv](./veterinario.CSV)
