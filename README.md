# Smart Lamp - Controle via Azure e Postman

## Integrantes
- **Kauã Rodrigues** - RM: 559335  
- **Felipe Santos** - RM: 560456  
- **Gustavo Naoto** - RM: 560470

  ## Links do Projeto
- **Youtube** - https://youtu.be/sXRenUrN54Q?si=8zO48bLALVy-3ecA
- **Wokwi** - https://wokwi.com/projects/424704198544719873

## Descrição do Projeto
Este projeto consiste em uma **Smart Lamp** que pode ser ligada e desligada remotamente e que também mede a luminosidade do ambiente. Todo o controle e monitoramento são realizados através de uma **VM na Azure**, utilizando o **Postman** para envio e recepção de comandos.

## Tecnologias Utilizadas
- **ESP32**: Microcontrolador responsável pelo funcionamento do sistema.  
- **Sensor LDR**: Sensor de luminosidade utilizado para medir a intensidade da luz no ambiente.  
- **Fiware Descomplicado**: Framework utilizado, seguindo o material do professor **Fábio Cabrini**.  
- **Azure**: Plataforma em nuvem usada para hospedar a VM de controle.  
- **Postman**: Ferramenta utilizada para enviar requisições e testar a comunicação com a Smart Lamp.  

## Funcionalidades
- **Ligar e desligar a lâmpada** remotamente via Postman.  
- **Monitoramento da luminosidade** do ambiente em tempo real.  
- **Processamento e armazenamento de dados** na VM do Azure.  

## Como Executar o Projeto
1. **Configurar o ESP32** com o código fornecido.  
2. **Conectar o sensor LDR** corretamente ao ESP32.  
3. **Subir a VM na Azure** e configurar o Fiware.  
4. **Usar o Postman** para enviar comandos e monitorar os dados.  

## Créditos
Projeto desenvolvido com base no **Fiware Descomplicado**, ministrado pelo professor **Fábio Cabrini**.

