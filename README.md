Breve descrição:
Wifi no hospital não parece tão acessivel se você está com pressa e não tem tempo de sair pelos corredores
perguntando sobre alguma rede para se conectar, foi pensando nestes momentos que eu desenvolvi este projeto,
que gera um qrcode por onde você pode rapidamente se conectar com o wifi.

Configuração e Execução da Aplicação para Display OLED

Material Necessário:
Display OLED SSD1306 (128x64 pixels) baseado em I2C.
Arduino ou placa compatível.
Cabos de conexão.

Configuração do Ambiente:
Certifique-se de ter o Arduino IDE instalado em seu computador.
Abra o Arduino IDE e instale a biblioteca "Adafruit SSD1306" e "QRCode" (se não estiverem instaladas). Você pode instalá-las através do menu "Sketch" -> "Incluir Biblioteca" -> "Gerenciar Bibliotecas".

Conexão do Hardware:
Conecte o display OLED à sua placa Arduino usando dois fios para os pinos SDA e SCL, e um fio para o pino de reset se necessário.

Upload do Código:
Abra o código fornecido no Arduino IDE.
Selecione o tipo de placa correta em "Ferramentas" -> "Placa".
Selecione a porta correta em "Ferramentas" -> "Porta".
Faça o upload do código para a sua placa.

Visualização do QR Code:
Após o upload bem-sucedido, o display OLED mostrará uma tela com um QR code para configurar o WiFi. Escaneie este QR code com um dispositivo para conectar a placa à rede WiFi.

Tela de Abertura do Webapp:
Após alguns segundos, a tela do display mudará, mostrando um novo QR code e mensagens indicando que você pode escaneá-lo para abrir o webapp "Lumifera".
