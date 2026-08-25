# Mechanic Tool

**by KitoSoft**

Ferramenta leve para mecânicos em servidores **GTA RP / FiveM**, criada para reduzir Alt+Tab e facilitar cálculos, controle de turno, orçamentos Custom, histórico e análises.

## Download

Os arquivos oficiais são publicados somente em **Releases** deste repositório.

### Installer — recomendado

[⬇️ **Baixar Mechanic Tool v2.0.0 — Installer**](https://github.com/democlit00-ops/MechanicTool-KitoSoft/releases/download/v2.0.0/MechanicTool-KitoSoft-Setup-v2.0.0.exe)

Instala o Mechanic Tool no Windows, cria os atalhos escolhidos durante a instalação e inclui o desinstalador.

### Portable

[⬇️ **Baixar Mechanic Tool v2.0.0 — Portable**](https://github.com/democlit00-ops/MechanicTool-KitoSoft/releases/download/v2.0.0/MechanicTool-KitoSoft-Portable-v2.0.0.zip)

Extraia o ZIP para uma pasta e execute `Mechanic Tool.exe`. Não exige instalação.

> Windows x64 • Runtime incluído • Não é necessário instalar o .NET separadamente.

[📦 **Ver a Release v2.0.0 completa**](https://github.com/democlit00-ops/MechanicTool-KitoSoft/releases/tag/v2.0.0)

### Atenção para usuários da V1

A V2 utiliza uma pasta de dados separada da V1. Os dados antigos não são apagados, mas histórico e configurações da V1 não são importados automaticamente. Crie um backup antes da atualização.

## Novidades da v2.0.0

- Novo módulo **Custom** para serviços de Estética e Tunagem.
- Mão de obra configurável por multiplicação ou porcentagem.
- Extras com valor de venda, custo fixo ou custo informado durante o serviço.
- Cálculo correto de pintura com custo variável abatido antes da mão de obra.
- Registro separado dos serviços Custom, evitando dupla contagem com o turno.
- Histórico Custom com lucro real, print e situação do envio ao Discord.
- Análises Custom de hoje, últimos 7 dias e últimos 30 dias.
- Retenção configurável de históricos e prints por 30, 60, 90 dias ou nunca apagar.
- Prints limitados a Full HD e aproximadamente 2 MB.
- Novo guia rápido de atalhos em **Sobre / Apoie**.
- Interface renovada, com melhorias para diferentes DPI, monitores e resolução 1366×768.
- O antigo botão e atalho `+5` foram removidos da experiência do usuário.

## Recursos

- Calculadora rápida com até **9 itens/serviços** configuráveis.
- Atalhos globais editáveis para adicionar `+1` sem sair do jogo.
- Suporte a combinações alternativas, inclusive teclas do NumPad.
- Overlay sobre o jogo com total do orçamento e tempo trabalhado.
- Posição e opacidade do overlay configuráveis.
- Controle de turno por saldo inicial e saldo final.
- Lucro por sessão, média por hora e ranking estimado de horários.
- Histórico de turnos com edição, exclusão e exportação CSV.
- Análises de hoje, últimos 7 dias e últimos 30 dias.
- Orçamentos Custom de Estética e Tunagem.
- Extras com custo fixo ou informado durante o atendimento.
- Registro de serviços Custom com print opcional e integração por webhook do Discord.
- Backup e restauração manual.
- Verificação de atualizações pelo GitHub com validação SHA-256.
- Minimização para a bandeja do Windows.
- Dados armazenados localmente no computador.

## Atalhos

Os atalhos `+1` dos itens da Calculadora podem ser alterados em **Configurações > Mecânica**.

Atalhos principais:

- `Ctrl + Shift + M` — alternar entre Mecânica e Custom.
- `Ctrl + Shift + O` — mostrar ou ocultar o overlay da Mecânica.
- `Shift + 0` — zerar o orçamento da Mecânica.
- `Shift + 1` — abrir o orçamento Custom quando esse modo estiver ativo.
- `Shift + 2` — ocultar o Custom sem apagar o orçamento atual.

## Cálculo Custom

Os custos dos extras são abatidos da base antes da aplicação da mão de obra. Depois, o valor de venda dos extras é somado ao orçamento.

Exemplo com pintura variável:

```text
Valor da máquina: R$ 3.600
Custo da pintura: R$ 900
Base ajustada: R$ 2.700
Mão de obra 100%: R$ 2.700
Valor de venda da pintura: R$ 15.000
Total para o cliente: R$ 20.400
```

O custo interno não é exibido no orçamento enviado ao cliente pelo Discord.

## Controle de turno

Ao iniciar o turno, informe quanto possui no banco e em dinheiro na mão. Ao finalizar, informe os valores finais.

O lucro da sessão é calculado como:

```text
saldo final - saldo inicial
```

Os serviços Custom permanecem registrados separadamente e não substituem nem alteram o resultado do turno.

## Atualizações

O Mechanic Tool consulta as Releases oficiais deste repositório. Quando uma versão mais nova estiver disponível, o usuário decide se deseja atualizar.

O Installer baixado é validado por SHA-256 antes de ser executado. A atualização não é instalada silenciosamente.

## Retenção e privacidade

O programa permite escolher por quanto tempo manter históricos e prints: 30, 60, 90 dias ou nunca apagar.

O Mechanic Tool funciona localmente e não exige conta, login ou servidor próprio. Os dados de uso ficam no computador do usuário e o histórico não é enviado para a KitoSoft.

## Vídeos

### Tutorial completo

[![Assistir ao tutorial completo do Mechanic Tool](https://img.youtube.com/vi/KXMfE-bWXl4/hqdefault.jpg)](https://youtu.be/KXMfE-bWXl4)

▶️ **[Assistir ao tutorial completo no YouTube](https://youtu.be/KXMfE-bWXl4)**

### Demonstração do overlay no GTA RP

[![Mechanic Tool em uso no GTA RP](https://img.youtube.com/vi/ZOsCYhdAd74/hqdefault.jpg)](https://youtu.be/ZOsCYhdAd74)

▶️ **[Assistir à demonstração no GTA RP](https://youtu.be/ZOsCYhdAd74)**

> Os vídeos foram produzidos utilizando a V1. Algumas telas e opções visuais foram modificadas na V2.

## Windows SmartScreen

A versão 2.0.0 ainda não possui certificado comercial de assinatura de código. Por isso, o Windows pode exibir um aviso de **Editor desconhecido** na primeira execução.

Baixe sempre os arquivos pela página oficial de Releases deste repositório.

## Apoie o projeto

O Mechanic Tool é gratuito. Se ele for útil no seu RP, você pode apoiar voluntariamente o desenvolvimento via PIX.

<img width="260" height="260" alt="QR Code PIX do Mechanic Tool" src="https://github.com/user-attachments/assets/64d17d3c-5579-43e2-88f9-eb6f05b1c8c7" />

**PIX:** `5ca81030-e0f6-4776-93be-ded515c14654`

O aplicativo também possui a tela **Sobre / Apoie**, com QR Code e PIX Copia e Cola.

## Feedback e problemas

Encontrou um bug ou comportamento incorreto? Abra uma solicitação na aba [Issues](https://github.com/democlit00-ops/MechanicTool-KitoSoft/issues) e informe:

- o que aconteceu;
- o resultado esperado;
- versão do Mechanic Tool;
- versão do Windows;
- passos para reproduzir o problema.

## Versão atual

**Mechanic Tool v2.0.0 — by KitoSoft**

Este repositório é usado para documentação, downloads oficiais e suporte. O código-fonte do aplicativo não é distribuído aqui.
