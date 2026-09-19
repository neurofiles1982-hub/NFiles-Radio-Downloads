# Histórico de versões

## 2.4.0 — Miniporta-retratos e equalizador

- Mini Player flutuante em formato quadrado, com acabamento Fluent e fotografia em destaque.
- Informações e controles do miniporta-retratos reaparecem ao mover o mouse e se ocultam automaticamente.
- Porta-retratos exclusivo para músicas locais, com pasta escolhida pelo usuário e fotos preservadas sem alteração.
- Encaixe automático: foto inteira em alta nitidez sobre fundo preenchido, sem transparência ou clarões na troca.
- Perfis Leve e Qualidade original; o perfil Leve decodifica imagens em tamanho adequado para reduzir memória.
- Troca de fotos orientada pelo BPM com análise curta em segundo plano e cache durante a sessão.
- Capa do álbum mantida como elemento secundário, botão de pasta identificado e acesso visual ao Spotify.
- Equalizador profissional de 10 bandas, perfis prontos e proteção automática contra distorção.
- Primeira abertura simplificada, sem solicitação de doação; apoio voluntário disponível apenas no GitHub.
- Testes permanentes para impedir regressões no porta-retratos, equalizador e boas-vindas.
- Build bloqueado automaticamente quando qualquer módulo obrigatório do NAudio estiver ausente.
- Fallback para o VLC quando o motor local avançado não estiver disponível em uma instalação antiga.

## 2.3.0 — Player leve, letras e experiência refinada

- Reprodução gapless real para músicas locais compatíveis, com uma única saída de áudio persistente e próxima faixa preparada.
- ReplayGain por faixa ou álbum com proteção contra clipping, sem modificar os arquivos originais.
- Fallback automático para o VLC quando o formato ou a velocidade escolhida não forem compatíveis com o motor gapless.
- Capa da música como fundo translúcido no painel de letras, mantendo o contraste do texto.
- Motor de música carregado somente quando necessário, mantendo a reprodução de rádio independente e leve.
- Buffer de áudio compatível com reprodução minimizada e correção de ruído/clipping em drivers do Windows.
- Prioridade dedicada e reserva ampliada para evitar engasgos ao alternar entre aplicativos.
- Troca de capas sem quadro claro entre músicas e fundo translúcido preservado com ou sem letras.
- Histórico consolidado por emissora: excluir remove ocorrências duplicadas antigas sem alterar coleções.
- Aviso de primeira abertura garantido antes da exibição da janela principal, com acesso ao GitHub.
- Janela maximizada respeita a área útil de cada monitor e mantém o player acima da barra de tarefas.
- Atualização pelo instalador agora é visível: o aplicativo fecha e o usuário acompanha o assistente da nova versão.

- Painel profissional de letras ao lado da capa ampliada.
- Sincronização automática por linha, rolagem e destaque da linha atual.
- Clique em qualquer linha sincronizada para avançar a música.
- Ajuste de sincronia em passos de 0,5 segundo, salvo por música.
- Prioridade para arquivos `.lrc`, letras incorporadas e arquivos `.txt` locais.
- Busca online opcional no LRCLIB, com consentimento, identificação da fonte e correspondência rigorosa.
- Limites de rede, tamanho e memória para preservar desempenho e segurança.

As mudanças relevantes do NFiles Radio são registradas neste arquivo.

## 2.1.0 — Biblioteca pessoal e descoberta

- Nova página inicial com favoritos, rádios recentes e estado de reprodução.
- Cartões mais legíveis, menus de ações e coleções temáticas.
- Busca de rádios por país, gênero, estado, qualidade e popularidade.
- Informações completas por rádio: idioma, codec, bitrate, localização, popularidade, site e stream.
- Recomendações locais, busca contextual, rádios semelhantes, Surpreenda-me e Modo Descoberta.
- Modo Descoberta compacto e integrado ao visual do aplicativo, sem a barra de título padrão do Windows.
- Cards PNG compartilháveis com QR Code gerado localmente, sem copiar ou redistribuir o áudio.
- Reprodução mantém o computador ativo enquanto a tela pode apagar normalmente.
- Estados vazios orientativos, player com indicador AO VIVO e controle de mudo.
- Temas claro, escuro e do sistema, quatro cores de destaque e densidade ajustável.
- Validação reforçada de URLs externas para bloquear loopback, redes privadas e esquemas inseguros.
- Central profissional de suporte e FAQ no GitHub Pages, com acesso direto pelo aplicativo.
- Controles de seleção, menus, avisos e tooltips integrados ao tema, com contraste legível em todas as cores.
- Navegação lateral rolável em telas menores e botão de salvar sempre visível nas configurações.
- Pesquisa restaurada em todas as telas, com texto visível, foco completo no campo e busca direta a partir da página inicial.
- Velocidade do player local sincronizada após a abertura de cada faixa para impedir reprodução acelerada inesperada.

## 2.0.3 — Player completo e identidade renovada

- Player local expandido com fila, anterior, próxima, favorito, velocidade e progresso Fluent.
- Capas incorporadas, capas da pasta, escolha manual e busca online opcional com confirmação.
- Mini Player com capa e controles de navegação para músicas locais.
- Inclusão em lote de rádios com validação concorrente limitada e gravação eficiente.
- Robô azul aplicado ao executável, janelas, bandeja e ativos da Microsoft Store.
- Controles, rolagem, volume e avisos padronizados no visual Fluent escuro.
- Correções de acessibilidade, fechamento de avisos e empacotamento MSIX para a Store.

## 2.0.2 — Sua rádio e suas músicas

- Player leve para músicas locais usando o mesmo mecanismo de áudio do rádio.
- Seleção e lembrança da pasta de músicas do usuário.
- Busca por título ou pasta e reprodução automática da próxima faixa.
- Verificação automática de novas versões mantida nas instalações fora da Microsoft Store.

## 2.0.0 — Radio. Music. One place.

- Navegação consolidada em Início, Explorar, Favoritos, Histórico e Ouvi na Rádio.
- Now Playing estruturado, Mini Player e controles integrados à bandeja.
- Descoberta pelo catálogo, estações personalizadas e busca avançada.
- Reconexão inteligente com estados visíveis e tentativas progressivas.
- Pesquisa segura de músicas no Spotify sem credenciais embutidas.
- Identidade visual escura preservada como base da nova geração.
- Layout compacto renovado com logos oficiais das emissoras e fallback seguro.
- Resolução automática e cache local de favicons declarados pelos sites das rádios.
- Proteção de instância única com ativação da janela já existente.
- Correções de estados tardios de conexão e reconexão para streams instáveis.
- Detecção silenciosa e conservadora de candidatos a hardware FM/RTL-SDR.

## 1.7.5 — Mini Player

- Janela compacta com estação, música, artista e estado da reprodução.
- Play/Pause, volume, favorito e pesquisa no Spotify.
- Opção de manter o Mini Player sempre no topo.
- Acesso pelo player principal e pela bandeja do Windows.

## 1.7.0 — Now Playing

### Adicionado

- Separação de artista e música nos metadados compatíveis.
- Apresentação estruturada da faixa atual e do histórico musical.
- Pesquisa da faixa no Spotify pelo navegador, sem login ou credenciais embutidas.

### Melhorado

- Título da janela, notificações e tray usam a identificação musical normalizada.
- Fallback claro para streams sem artista ou sem metadados.

## 1.6.0 — Windows Experience

### Adicionado

- Identidade visual escura preservada como padrão oficial.
- Opção para iniciar minimizado na bandeja.
- Opção independente para continuar tocando ao fechar a janela.
- Teclas multimídia globais para Play/Pause, parar e volume.
- Lista de estações favoritas no menu da bandeja.
- Documentação pública e arquivos de comunidade do GitHub.

### Melhorado

- Volume alterado pela bandeja agora acompanha o controle da janela.
- Tratamento de falta de permissão ao configurar a inicialização com o Windows.
- Descrição pública do produto, privacidade, suporte e roadmap.

### Corrigido

- Persistência do volume durante alterações feitas fora da tela de configurações.
- Comportamento de fechar separado do comportamento de minimizar.

## 1.5.0

- Nova experiência visual, player inferior compacto, cards responsivos e consultas otimizadas.
- Inicialização mais suave e correções na reprodução precoce e no histórico.

## 1.4.0

- Reprodução imediata pelos cards, histórico de músicas, notificações, temporizador, tray aprimorada, atalhos e backup.
