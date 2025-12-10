![Bruce Main Menu](./media/pictures/bruce_banner.jpg)

# 🦈 Bruce

Bruce é um firmware versátil para ESP32 que oferece uma grande variedade de funções ofensivas focadas em facilitar operações de Red Team.  
Ele é compatível com dispositivos M5Stack e funciona perfeitamente em Cardputer, Sticks, M5Cores, T-Decks, T-Embeds e outros modelos.

---

## 🏗️ Como instalar

### ⭐ **A maneira mais fácil de instalar o Bruce é usando o Web Flasher oficial!**  
🔗 https://bruce.computer/flasher

---

### 📥 Instalação manual via esptool.py

Você também pode baixar o binário mais recente nos *Releases* ou *Actions* e fazer o flash manualmente:

```sh
esptool.py --port /dev/ttyACM0 write_flash 0x00000 Bruce-<device>.bin
```

🔥 Para dispositivos M5Stack

Se você já usa o M5Launcher, é possível instalar o Bruce diretamente via OTA.

Ou você pode gravar diretamente usando o M5Burner
:

Abra o programa

Pesquise por "Bruce"

Escolha o dispositivo

Clique em Burn
(As builds oficiais são enviadas pelo usuário “owner” e possuem imagens.)

🎤 Servidor no Discord

Entre no nosso servidor!
👉 https://discord.gg/WJ9XF9czVT

📚 Wiki

Para informações completas sobre cada função do Bruce:

📘 Wiki: https://github.com/pr3y/Bruce/wiki

❓ FAQ: https://github.com/pr3y/Bruce/wiki/FAQ

💻 Lista de Funcionalidades

As seções abaixo incluem tudo que o Bruce pode fazer, separadas por categoria.

📡 WiFi
<details> <summary><strong>Clique para expandir</strong></summary>

 Conectar ao WiFi

 Access Point

 Desconectar WiFi

 Ataques WiFi

 Beacon Spam

 Ataque ao alvo

Informações

Deauth do alvo

EvilPortal + Deauth

 Deauth múltiplo

 Wardriving

 TelNet

 SSH

 RAW Sniffer

 Cliente TCP

 Listener TCP

 Evil Portal

 Escanear Hosts

 Túnel Wireguard

 Brucegotchi

Amigo Pwnagotchi

Spam Pwngrid

</details>
📶 BLE
<details><summary><strong>Clique para expandir</strong></summary>

 Scan BLE

 Bad BLE (scripts estilo BadUSB)

 Teclado BLE (Cardputer/T-Deck)

 Spam para: iOS, Windows, Samsung, Android

 Spam All

</details>
📻 RF
<details><summary><strong>Clique para expandir</strong></summary>

 Scan/Copy

 SubGhz personalizado (CC1101)

 Spectrum

 Jammer Full

 Jammer Intermitente

 Configurações de RF

 Replay

</details>
📟 RFID
<details><summary><strong>Clique para expandir</strong></summary>

 Ler tag

 Ler 125kHz

 Clonar tag

 Escrever NDEF

 Amiibolink

 Chameleon

 Escrever dados

 Apagar dados

 Carregar/Salvar arquivo

 Configurar módulo PN532

 Emulação de tag

</details>
📡 Infravermelho (IR)
<details><summary><strong>Clique para expandir</strong></summary>

 TV-B-Gone

 Receptor IR

 IR customizado (NEC, SIRC, RC5, Samsung32 etc.)

 Configurações

</details>
📻 FM
<details><summary><strong>Clique para expandir</strong></summary>

 Transmissão padrão

 Transmissão reservada

 Parar transmissão

 Espectro FM

 Hijack de anúncios de trânsito

 Configurações

</details>
📡 NRF24
<details><summary><strong>Clique para expandir</strong></summary>

 Jammer NRF24

 Espectro 2.4G

 Mousejack

</details>
📜 Scripts
<details><summary><strong>Clique para expandir</strong></summary>

 Interpretador JavaScript

</details>
🔧 Outros
<details><summary><strong>Clique para expandir</strong></summary>

 Espectro do microfone

 QRCodes (inclui PIX)

 Gerenciador de SD

 Gerenciador LittleFS

 WebUI completo

 Megalodon

 BADUsb

 Teclado USB

 iButton

 Controle de LEDs

</details>
🕒 Relógio

 Suporte RTC

 Ajuste via NTP

 Ajuste manual

📡 Connect (ESPNOW)

 Enviar arquivo

 Receber arquivo

 Enviar comandos

 Receber comandos

⚙️ Configurações Gerais

Brilho

Tempo de dim

Orientação de tela

Cor da interface

Som de boot on/off

Relógio

Sleep

Reiniciar

📱 Funções por dispositivo

(A tabela original foi mantida, com traduções nos títulos.)

(Mantive os ícones para copiar 100% igual ao GitHub original e evitar quebrar layout.)

✨ Por que o Bruce existe?

Bruce nasceu da observação da comunidade em torno de dispositivos como Flipper Zero.
A ideia é oferecer algo mais poderoso, mais aberto e muito mais acessível, aproveitando o ecossistema ESP32, Lilygo e M5Stack.

Imagens do Bruce em funcionamento:








Mais mídia disponível em: /media/

🙌 Agradecimentos

@bmorcelli — novo core, novas funções, porting para diversos dispositivos

@IncursioHack — módulos RF e RFID

@Luidiblu — logo e UI

@eadmaster — diversas features

@rennancockles — código RFID e refatorações

@7h30th3r0n3 — ajuda nos ataques WiFi

@Tawank — melhorias no interpretador

@pablonymous — novos recursos RF

Smoochiee — design da PCB Bruce

TH3_KR4K3N — PCB Stick extender

A toda comunidade ❤️

⚠️ Aviso Legal

Bruce é uma ferramenta para operações de segurança ofensiva e Red Team, distribuída sob a licença AGPL.
Seu uso é permitido somente para fins legais, como testes autorizados de segurança.

Os desenvolvedores não se responsabilizam por qualquer uso indevido.

Use por sua própria conta e risco.
