# Guia de Automação Residencial - IoT

### Vitor Fernandes

**Estudante Técnico em Informática | Estudante Curso Superior de Tecnologia em Segurança Cibernética - CST | Automação Residencial e IoT**

---

## Introdução

Este guia foi desenvolvido para profissionais iniciantes que desejam realizar instalações de dispositivos IoT em ambientes residenciais com foco em **automação inteligente**, **segurança digital** e **segmentação de redes**.

A automação residencial não é apenas sobre conforto, mas também sobre eficiência, segurança e proteção contra ameaças cibernéticas. Vamos seguir um passo a passo completo desde a configuração do roteador até a integração com assistentes virtuais.

---

## 1. Avaliação Inicial do Ambiente

### Checklist Inicial:

- Quantos dispositivos inteligentes o cliente deseja instalar?
- Dispositivos que serão utilizados (tomadas, lâmpadas, sensores, etc.)
- O cliente deseja integração com assistentes virtuais (Alexa, Google Home)?
- Qual é a frequência da rede Wi-Fi disponível (2.4 GHz, 5 GHz)?
- O cliente deseja uma **rede exclusiva para IoT**?

---

## 2. Configuração do Roteador

### Opção 1: Resetando o Roteador

1. Identifique o IP do Gateway (geralmente **192.168.0.1** ou **192.168.1.1**).
2. Acesse o roteador pelo navegador.
3. Faça login com as credenciais padrão (disponíveis na etiqueta do roteador).
4. Crie uma nova rede com SSID **IoT_Residencial**.
5. Frequência: **2.4 GHz**
6. Segurança: **WPA2-PSK (AES)**
7. Defina uma senha forte.
8. Configure o **Controle de Acesso por MAC Address**.
9. Reserve IPs estáticos para cada dispositivo IoT.

[Guia completo de configuração de roteador](#)

---

### Opção 2: Criando uma Rede Secundária (SSID Secundário)

1. Acesse o roteador pelo navegador.
2. Vá para **Configurações Wireless > SSID Secundário**.
3. Crie o SSID: **IoT_Residencial**.
4. Frequência: **2.4 GHz**
5. Segurança: **WPA2-PSK (AES)**
6. Ative o **DHCP com IP Estático**.
7. Adicione os endereços MAC dos dispositivos IoT.
8. Salve e reinicie o roteador.

[Guia completo de segmentação de redes](#)

---

## 3. Instalação Física dos Dispositivos

### Equipamentos Necessários:

- Tomadas inteligentes
- Interruptores inteligentes
- Sensores de movimento
- Assistentes Virtuais (opcional)
- Aplicativo de Controle (Nova Digital, Tuya Smart, Smart Life, eWeLink)

### Passo a Passo:

1. Conecte os dispositivos na tomada elétrica.
2. Abra o aplicativo Tuya Smart.
3. Crie a conta do cliente.
4. Adicione o dispositivo elétrico no aplicativo.
5. Coloque o dispositivo em modo de pareamento.
6. Conecte à rede **IoT_Residencial**.
7. Teste a conectividade.

[Instalação de Tomada e Interruptor Inteligente](#)

---

## 4. Segurança da Rede IoT

- Use **WPA2-PSK (AES)** como protocolo de segurança.
- Crie uma rede secundária exclusiva para IoT.
- Habilite o **Controle de Acesso por MAC**.
- Mantenha o **firmware atualizado** dos dispositivos.
- Desative o **UPnP** (Universal Plug and Play) no roteador.

[Guia de Segurança para IoT](#)

---

## 5. Integração com Assistentes Virtuais

### Plataformas Compatíveis:

- Google Home
- Alexa

### Como Integrar:

1. Instale o app do assistente virtual.
2. Adicione a skill do aplicativo (Tuya Smart, eWeLink, etc.).
3. Vincule a conta do app com o assistente virtual.
4. Descubra dispositivos na rede.
5. Crie rotinas personalizadas.

---

## 6. Testes Finais

- Teste a automação pelo aplicativo.
- Teste os comandos por voz (se houver integração com assistentes virtuais).
- Verifique a estabilidade da rede.
- Valide a segurança com um ataque simulado de desconexão.

---

## 7. Conclusão

A automação residencial vai além da praticidade — ela traz **segurança, eficiência energética e inovação** para a vida cotidiana. Seguindo este guia, você estará preparado para realizar instalações seguras e entregar valor ao seu cliente.

**DICA:** Sempre documente a instalação e forneça um manual personalizado para o cliente final.

---

## Contato

Se precisar de ajuda ou quiser colaborar em projetos, entre em contato!

🔗 GitHub: [Vifernandestech](https://github.com/Vifernandestech)  
💼 LinkedIn: [Vitor Fernandes](https://www.linkedin.com/in/vifernandestech/)  
📧 E-mail: [vifernandestech@gmail.com](mailto:vifernandestech@gmail.com)  

🚀 Vamos transformar o mundo com tecnologia!


