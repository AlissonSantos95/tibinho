 ⚔️ Tibia Cooldowns & Atalhos e MAIS — Overlay em Tempo Real

Overlay flutuante e invisível para Tibia que exibe cooldowns de magias e runas em tempo real, com drag & drop, scraper integrado da TibiaWiki e persistência de dados.


📋 Descrição

Aplicativo desenvolvido em Python que funciona como overlay transparente sobre o jogo Tibia, permitindo acompanhar visualmente o tempo de recarga (cooldown) das suas magias e runas de forma automatizada e customizável.

Construído em Python, IA utilizada para entendimento das bibliotecas abaixo e design de UI pois não tenho conhecimento avançado em PYTHON.


<img width="460" height="199" alt="{3175E61C-A8CB-4946-8CDB-46127461DCD4}" src="https://github.com/user-attachments/assets/d7d7dbcb-3bc6-4165-b88f-1e48c0ab0cc8" />


✨ Funcionalidades

🎯 Overlay Flutuante Invisível (Chroma Key)

A interface utiliza transparência nativa (-transparentcolor), fazendo com que o fundo seja totalmente ignorado pelo Windows. Apenas os ícones, barras de progresso e descrições ficam visíveis sobrepostos ao jogo.

**Atalho:** `CTRL + SHIFT + ALT + Q` — Abre o menu de configurações


🙈 Auto-Hide Inteligente

O script monitora a janela ativa do sistema. Se o Tibia estiver em foco, o overlay aparece; ao dar Alt+Tab para o navegador ou Discord, ele desaparece automaticamente.


🖱️ Gerenciador de Slots Dinâmico (Drag & Drop)

Organize feitiços e poções arrastando-os das abas de categorias (Knight, Sorcerer, Druid, Paladin, Monk e Runas) diretamente para os slots ativos. Adicione quantos slots quiser com o botão + Adicionar Slot.


🌐 Scraper Integrado da TibiaWiki

Com um clique, o programa busca automaticamente os ícones oficiais das magias e runas, convertendo-os para o formato ideal. Também extrai Level mínimo, Custo de Mana e Descrição oficial, atualizado a cada update automaticamente ou forçando sync.


💾 Persistência de Dados (JSON)

Todas as escolhas de slots, atalhos e preferências são salvos em:

overlay_config.json

Ao reabrir o programa, tudo estará exatamente como você deixou.


🔔 Integração com Tray Icon

O programa roda oculto na barra de notificações com menu de acesso rápido e mantém presença na barra de tarefas do Windows.


🔒 Modo Travado e Barra de Controle

Barra flutuante com:


Alça de arraste (≡)

Botão de configurações (⚙)

Cadeado de segurança (🔓 / 🔒) — trava a posição para evitar cliques acidentais

Botão de fechamento rápido (✕)


## 🗺️ Roadmap


- [x] **Cooldown por spell** — A barra de cooldown abaixo dos ícones da barra flutuante deve refletir o cooldown do spell colocado no atalho, não o cooldown global.

- [x] **Cooldown global visual** — Cooldown global de 2s: deixar todos os ícones em cinza enquanto roda, com contador de 2s + milissegundos em cima da imagem (sem tampar, imagem pode ficar cinza).

- [x] **Overlay limpo** — Mostrar apenas o ícone da imagem. Sem detalhes, mana, nível ou qualquer outra informação.

- [x] **Botão "Sincronizar"** — Renomear o botão de atualizar ícones para "Sincronizar". Ao clicar, força sincronia de ícones com o GitHub Pages.

- [x] **Trava de movimentação** — Ao ativar, sumir todos os ícones exceto as habilidades e o cooldown. Opções, fechar e mover desaparecem.

- [ ] **Atualização de icones de spells e runas

- [ ] **Menu de configurações** — Separar as configurações em abas:

- [ ] **Tooltip de detalhes** — Quando "mostrar detalhes" estiver ativo nas configurações, passar o mouse sobre o spell mostra os detalhes.

  - [ ] `Overlay Spells/Icons` — Configurações atuais de atalhos

  - [ ] `Sync Character for Hunts` — Sincronizar personagem para hunts

  - [ ] `Hunts`

    - [ ] Checkbox pré-marcada "Sync with character" — busca hunts apenas para a classe e nível do personagem logado

    - [ ] Campo para digitar nome do personagem — puxa dados do site oficial da Tibia com opção de overlay dos dados da hunt

    - [ ] Filtro de hunt por XP, loot, XP/hr, etc.

- [ ] **Documentação do código** — Comentar todas as linhas detalhadamente explicando o que cada bloco faz, com exemplos.


- [ ] **Monotoramento com Notificação** - Monitoramento com Notificação char bazzar


- [ ] **Mini-MAP expandido**

