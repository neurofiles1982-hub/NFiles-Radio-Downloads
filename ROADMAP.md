# Roadmap público do NFiles Radio

O roadmap comunica direção, não uma data garantida. Cada novidade será disponibilizada somente quando estiver estável, leve e em conformidade com as plataformas envolvidas.

## Entregue na versão 2.3.0

- Rádio online com busca avançada, favoritos, coleções, histórico e informações das emissoras.
- Surpreenda-me, estações semelhantes, recomendações locais e Modo Descoberta.
- Player de música local com capas, fila, letras locais e sincronizadas.
- Reprodução gapless para formatos compatíveis e ReplayGain por faixa ou álbum.
- Player imersivo com capa translúcida, mini player, bandeja e teclas multimídia.
- Reconexão de streams, temporizador, temas, backup e restauração.
- Compartilhamento por card com QR Code e boas-vindas no primeiro uso.
- Instalação limpa, sem músicas, rádios, favoritos ou históricos de teste.

## Em breve

### Prioridade: rádio confiável no dia a dia

- **Diagnóstico de estações:** testar disponibilidade, tempo de resposta, codec e bitrate antes ou durante a reprodução.
- **Recuperação inteligente:** tentar endereços alternativos e reconectar sem obrigar o usuário a procurar novamente a emissora.
- **Despertador com rádio:** escolher emissora, horário, dias da semana e aumento gradual de volume.
- **Pesquisas salvas:** guardar combinações de país, estado, gênero, qualidade e popularidade para repetir uma busca com um clique.
- **Importação e exportação M3U/PLS:** facilitar a migração de favoritos entre o NFiles Radio e outros players.

### Saída de áudio e hardware

- Identificar a saída padrão informada pelo Windows: fone ou caixa Bluetooth, alto-falantes, USB, HDMI e fone com cabo, quando o driver fornecer essa informação.
- Avisar de forma discreta quando a saída mudar ou for desconectada e mostrar claramente para onde o áudio está sendo enviado.
- Manter a detecção local, sem telemetria, varredura de rede ou controle desnecessário do Bluetooth.
- Expor com segurança a sondagem experimental já existente de possíveis receptores FM USB, incluindo RTL-SDR, RTL2832, R820T e Si470.
- Validar receptores reais antes de anunciar sintonia FM; detectar um dispositivo não significa que o aplicativo já consiga receber a transmissão.

### Spotify

- Acesso direto a músicas, artistas e álbuns no aplicativo oficial.
- Correspondência mais precisa entre o conteúdo informado pela rádio e o catálogo.
- Estudo de autenticação oficial para funcionalidades adicionais permitidas pela plataforma.

### YouTube

- Pesquisa de vídeos e canais oficiais relacionados à faixa ou emissora atual.
- Abertura segura pelo aplicativo ou navegador escolhido pelo usuário.
- Divulgação dos futuros canais oficiais do NFiles Radio e NFiles IA.

As integrações respeitarão APIs, autenticação, direitos autorais e termos oficiais. O aplicativo não incorporará credenciais, não contornará anúncios e não fará download não autorizado de áudio ou vídeo.

## Em avaliação

- Mais fontes legais de letras e metadados, sempre identificando a origem.
- Acessibilidade completa por leitor de tela e navegação por teclado, incluindo troca rápida de estação e volume.
- Notas e logotipos personalizados para estações.
- Otimizações adicionais para computadores de baixo consumo.
- Integrações opcionais com serviços externos somente quando trouxerem valor sem comprometer privacidade ou desempenho.

## Fora do escopo neste momento

- Gravação indiscriminada de transmissões, por questões de direitos autorais e armazenamento.
- Servidor de controle remoto aberto na rede, para evitar superfície de ataque desnecessária.
- Televisão, hospedagem de estações e recursos sociais pesados que desviem o foco de rádio e música.
- Edição para Windows 7/8.1, pois exigiria dependências antigas e uma segunda linha de manutenção sem suporte do sistema operacional.

## Compromissos do projeto

- Continuar gratuito e sem anúncios.
- Manter rádio como núcleo da experiência.
- Preservar dados e bibliotecas localmente por padrão.
- Tornar recursos online opcionais e transparentes.
- Priorizar estabilidade, privacidade, segurança e desempenho.

Ajude a definir prioridades pelas [Issues](https://github.com/neurofiles1982-hub/NFiles-Radio-Downloads/issues) e [Discussions](https://github.com/neurofiles1982-hub/NFiles-Radio-Downloads/discussions).
