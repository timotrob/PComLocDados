# Arquivos Projeto Localização PCOM
Contém dados de Localização para projeto da disciplina PCOM

# Descriminação das Colunas nos arquivos

## Bts.csv - Arquivos com Dados da BTS.

| Coluna  | Descrição |
| ------------- | ------------- |
| grupo  | Localização do setor  |
| btsId  | Identificador da BTS  |
| btsNetNome  | Nome da BTS |
| lat  | latitude da BTS  |
|lon  | longitude da BTS  |
| cch  | Canal de Controle BTS  |
| azimuth | Azimute da Antena da BTS  |
| RssiId |Identificador no arquivo de medições (treino/test) |

## meds_train_alunos.csv - Arquivos de Treino para os alunos

| Coluna  | Descrição |
| ------------- | ------------- |
| ponto_id  | Indetificador do Ponto|
| rssi_1_1 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_1_1|
| rssi_1_2 | Intenidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_1_2|
| rssi_1_3 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_1_3|
| rssi_2_1 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_2_1|
| rssi_2_2 | Intenidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_2_2|
| rssi_2_3 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_2_3|
| rssi_3_1 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_3_1|
| rssi_3_2 | Intenidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_2_2|
| rssi_3_3 | Intensidade do Sinal (Received signal strength indication) BTS com RssiId=rssi_3_3|
|delay_1|Atraso de Propagação Grupo 1|
|delay_2|Atraso de Propagação Grupo 2|
|delay_3|Atraso de Propagação Grupo 3|
|lat|latitude da medição|
|lon|longitude da medição|
|indoor|Se a medição em ambiente indoor (Não está no arquivo de test)|

