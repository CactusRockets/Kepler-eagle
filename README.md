# Placas da aviônica para o foguete Kepler-200m

Nesse repositório temos os arquivos das placas que farão parte da aviônica do foguete Kepler de 200m da Cactus Rockets Design.

### Descrição

Temos duas placas principais para esta aviônica:
- Placa de Processamento
- Placa de Acionamento

A placa de processamento é responsável pelo processamento dos dados de altitude e pressão. A placa de acionamento possui o circuito necessário para a correta ativação do Skib.

OBS.: Os arquivos das placas podems ser abertos por meio software Eagle da Autodesk.

### Esquemáticos e layouts

### Conexões entre placas

### Funcionamento

A placa de processamento contém um switch de ativação do sistema. No momento que o switch é pressionado, o sistema liga e faz a leitura dos valores de pressão e altitude.

No momento que a placa de processamento detectar uma queda, ela envia um sinal para a placa de acionamento para que a mesma ative o Skib da parte de recuperação.

OBS.: Usa-se a memória EEPROM do arduino nano para armazenar o maior valor de altitude detectado pelo foguete.