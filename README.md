# Sistema de Transporte

## Atividade solicitada:

Uma empresa de transporte deseja criar um sistema para gerenciar suas rotas e motoristas. Crie o MER, DER e Dicionário de Dados para este sistema. Simule no excel dados fictícios para as entidades criadas.

## MER – Dicionário de Dados: Sistema de Transporte

| Entidade | Atributo | Tipo | Tamanho | Descrição |
|---|---|---|---|---|
| Motorista | id_motorista | int | 11 | Chave primária que refere à entidade Motorista |
| Motorista | nome | varchar | 50 | Nome do motorista |
| Motorista | cpf | varchar | 11 | CPF do motorista |
| Motorista | telefone | varchar | 15 | Telefone do motorista |
| Motorista | cnh | int | 11 | CNH do motorista |
| Viagem | id_viagem | int | 11 | Chave primária que refere à entidade Viagem |
| Viagem | id_motorista | int | 11 | Chave estrangeira que refere à entidade Motorista |
| Viagem | id_rota | int | 11 | Chave estrangeira que refere à entidade Rota |
| Viagem | data | varchar | 10 | Data da viagem |
| Viagem | horario_saida | varchar | 5 | Horário de saída da viagem |
| Viagem | horario_chegada | varchar | 5 | Horário de chegada da viagem |
| Viagem | quilometragem | decimal | 50 | Quilometragem da viagem |
| Viagem | valor_viagem | decimal | 10 | Valor da viagem |
| Viagem | situacao | varchar | 30 | Situação da viagem |
| Rota | id_rota | int | 11 | Chave primária que refere à entidade Rota |
| Rota | origem | varchar | 20 | Origem da rota |
| Rota | destino | varchar | 20 | Destino da rota |
| Rota | distancia_quilometros | decimal | 10 | Distância em quilômetros da rota |
| Rota | tempo_estimado | varchar | 5 | Tempo estimado da rota |
| Rota | observacao | varchar | 30 | Observação da rota |
