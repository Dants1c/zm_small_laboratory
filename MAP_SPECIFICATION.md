# zm_small_laboratory - Documentação Completa para IA Gerar o Mapa

## 📋 RESUMO EXECUTIVO

Mapa profissional de Zombie Plague para Counter-Strike 1.6 / GoldSrc.
- **Nome**: zm_small_laboratory
- **Tema**: Laboratório secreto abandonado com experiências de zombie
- **Tamanho**: Pequeno e compacto (~1000x1000 unidades GoldSrc)
- **Jogadores**: 10-20 (Zombie Plague)
- **Salas**: 8 áreas conectadas com rotas alternativas

---

## 🏗️ LAYOUT DO MAPA - PLANTA BAIXA

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  QUARENTENA    SALA DE        GERADORES            │
│  (sala 8)      CONTROLE       (sala 7)             │
│                (sala 3)                             │
│                                                     │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐          │
│  │          │  │ JANELA   │  │          │          │
│  │ QUAREN.  │─▶│ VIDRO ◄──┤──│ GERADOR  │          │
│  │          │  │          │  │          │          │
│  └──────────┘  └──────────┘  └──────────┘          │
│       ▲            ▲              ▲                │
│       │            │              │                │
│       │      TÚNEL MANUTENÇÃO     │                │
│       │      (ROTA ALTERNATIVA)   │                │
│       │            │              │                │
│  ┌──────────────────────────────────────┐          │
│  │                                      │          │
│  │   SALA PRINCIPAL DE EXPERIMENTOS     │          │
│  │                                      │          │
│  │     ◉ GRANDE CÁPSULA DE VIDRO ◉    │          │
│  │     ◉ ZUMBI SUSPENSO COM TUBOS ◉   │          │
│  │                                      │          │
│  │     CÁPSULA QUEBRADA → SANGUE        │          │
│  │     EQUIPAMENTOS, MESAS, CABOS       │          │
│  │                                      │          │
│  └──────────────────────────────────────┘          │
│       ▲            ▲              ▲                │
│       │            │              │                │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐          │
│  │          │  │          │  │          │          │
│  │ LABO.    │─▶│ CÁPSULAS │◄─│ ALMOX.   │          │
│  │ MÉDICO   │  │          │  │          │          │
│  │ (sala 4) │  │ (sala 2) │  │ (sala 5) │          │
│  │          │  │          │  │          │          │
│  └──────────┘  └──────────┘  └──────────┘          │
│                   (sala 1)                         │
│                                                     │
│  (sala 6 = corredor de quarentena conecta 4 a 8)   │
│                                                     │
└─────────────────────────────────────────────────────┘
```

---

## 📐 ÁREAS DETALHADAS

### SALA 1: SALA PRINCIPAL DE EXPERIMENTOS
**Posição**: Centro do mapa (320,320) a (640,640)
**Dimensões**: 320x320 unidades
**Altura**: 128 unidades
**Função**: Núcleo de gameplay, maior área aberta

**Conteúdo**:
- 1x GRANDE CÁPSULA DE VIDRO (centro)
  - Altura: 80 unidades
  - Raio: 48 unidades
  - Contém: Zumbi suspenso em líquido verde luminoso
  - Tubos conectados ao corpo
  - Água/líquido verde com pequenas bolhas
  
- 1x CÁPSULA QUEBRADA (ao lado)
  - Vazia
  - Vidro rachado/espalhado
  - Líquido verde vazando no chão
  
- Equipamentos ao redor:
  - 4x Mesas metálicas
  - 2x Computadores antigos (monitorados)
  - 8x Cadeiras de laboratório
  - 6x Armários cinzas
  - 10x Prateleiras com frascos
  - 20x Cilindros de gás (pequenos)
  - 4x Extintores vermelhos
  - Documentos espalhados no chão
  - Cabos pretos cruzados
  
- Iluminação:
  - Luz verde brilhante do líquido das cápsulas (dominante)
  - 2x Luzes fluorescentes brancas (teto)
  - 1x Luz vermelha de emergência (oscilante)

**Spawns**:
- 2x info_player_start (humanos) - cantos superiores
- 1x Spawn de zumbis - ao lado da cápsula quebrada

---

### SALA 2: SALA DAS CÁPSULAS
**Posição**: (640,320) a (1024,640)
**Dimensões**: 384x320 unidades
**Altura**: 128 unidades
**Função**: Câmara de contenção com múltiplas cápsulas menores

**Conteúdo**:
- 6x Cápsulas cilíndricas de vidro (menores que a principal)
  - 3x Intactas com corpos suspensos
  - 2x Quebradas/vazando líquido
  - 1x Vazia e aberta
  - Cada cápsula: altura 64 unidades, raio 24 unidades
  
- Equipamentos:
  - 3x Painéis de controle
  - 4x Monitores antigos (telas CRT)
  - Tubulações (pipes) conectadas às cápsulas
  - Mangueiras de borracha vermelha
  - Cabos elétricos amarelos
  
- Iluminação:
  - Luz verde luminosa das cápsulas (80% do ambiente)
  - Pequenas luzes azuis dos painéis
  - 1x Luz branca auxiliar

**Spawns**:
- 1x info_player_start (humanos)

---

### SALA 3: SALA DE CONTROLE
**Posição**: (640,640) a (1024,768)
**Dimensões**: 384x128 unidades
**Altura**: 128 unidades
**Função**: Centro de comando e observação

**Conteúdo**:
- 5x Computadores de mesa
- 8x Monitores CRT (alguns piscando)
- 1x Grande janela de vidro (meia parede)
  - Visão para a Sala 1 (cápsulas principais)
  
- Equipamentos:
  - Teclados mecânicos
  - Painéis com botões (não funcionais)
  - 4x Servidores em rack
  - Cabos em demasia
  - Luzes vermelhas e verdes nos painéis
  
- Iluminação:
  - Luz azul dos computadores (dominante)
  - 1x Luz branca fluorescente
  - Pequenas luzes piscantes dos LEDs dos servidores

**Spawns**:
- Nenhum (mais defensivo para humanos)

---

### SALA 4: LABORATÓRIO MÉDICO
**Posição**: (128,320) a (320,640)
**Dimensões**: 192x320 unidades
**Altura**: 128 unidades
**Função**: Área de pesquisa com instrumentos médicos

**Conteúdo**:
- 4x Microscópios em mesas
- 6x Tubos de ensaio com líquidos coloridos
- 8x Frascos de vidro em prateleiras
- 10x Seringas (algumas caídas no chão)
- 2x Macas metálicas
- 4x Armários de armazenamento
- Instrumentos cirúrgicos espalhados
- Sangue nas paredes (acesso da Sala 5)
- Vidro quebrado no chão

- Iluminação:
  - Luz branca fluorescente (padrão)
  - 1x Luz vermelha de emergência (canto)
  - Sombras fortes nas macas

**Spawns**:
- 1x info_player_start (humanos)

---

### SALA 5: ALMOXARIFADO
**Posição**: (1024,320) a (1152,640)
**Dimensões**: 128x320 unidades
**Altura**: 128 unidades
**Função**: Armazenamento de suprimentos

**Conteúdo**:
- 12x Caixas de papelão empilhadas
- 8x Prateleiras metálicas com frascos
- 4x Cilindros de gás grandes
- Documentos nos chão (alguns queimados)
- 2x Mesas com objetos caídos
- Garrafas vazias
- Cabos soltos

- Iluminação:
  - Luz branca padrão
  - 1x Luz pisca pisca (falha)
  - Uma lâmpada queimada (escuridão parcial)

**Spawns**:
- Nenhum (secundário)

---

### SALA 6: CORREDOR DE QUARENTENA
**Posição**: (0,640) a (320,768)
**Dimensões**: 320x128 unidades
**Altura**: 128 unidades
**Função**: Zona de isolamento com sinalização de risco biológico

**Conteúdo**:
- Marcações no piso (linhas vermelhas e pretas)
- 4x Placas de aviso:
  - "BIOHAZARD" (símbolo)
  - "QUARANTINE"
  - "DANGER - AUTHORIZED PERSONNEL ONLY"
  - Símbolo de risco biológico
  
- 2x Luzes de emergência vermelhas (oscilantes)
- Portas com pequenas janelas
- Vidro reforçado

**Spawns**:
- Nenhum

---

### SALA 7: SALA DE GERADORES
**Posição**: (1024,640) a (1152,768)
**Dimensões**: 128x128 unidades
**Altura**: 128 unidades
**Função**: Sistema técnico de backup

**Conteúdo**:
- 2x Geradores diesel (modelos antigos)
- 4x Baterias de backup
- Painéis elétricos com disjuntores
- Cabos e tubulações
- Ventilador de ar (funcionando)
- Válvulas de pressão
- Pequenas caixas de manutenção

- Iluminação:
  - Luz alaranjada de alerta
  - Luz verde de status
  - Sombras geradas pelos equipamentos

**Spawns**:
- Nenhum

---

### SALA 8: CÂMARA DE QUARENTENA SECUNDÁRIA
**Posição**: (128,768) a (320,896)
**Dimensões**: 192x128 unidades
**Altura**: 128 unidades
**Função**: Isolamento de contágio

**Conteúdo**:
- Vidro de segurança em 3 paredes
- Mesas e cadeiras caídas
- Marcações de containment
- Luzes vermelhas piscantes
- Sinalização de biohazard
- Vidro rachado (alguém escapou?)

**Spawns**:
- Nenhum

---

## 🧟 ROTAS DE GAMEPLAY

### ROTA 1: PRINCIPAL (Humanos defensivos)
Sala 1 → Sala 2 → Sala 3 (Controle) → Geradores / Quarentena

### ROTA 2: ALTERNATIVA (Humanos fuga)
Sala 1 ←→ Sala 4 (Médico) ←→ Sala 5 (Almox) ←→ Sala 1

### ROTA 3: SECRETA (Zumbis invasão)
TÚNEL DE MANUTENÇÃO (320,320) → (640,640)
- Pequena altura (72 unidades)
- Tubulações e ventilação
- Rota alternativa para contornar defesa

### ROTA 4: QUARENTENA (Zumbis backup)
Sala 8 → Corredor Quarentena → Sala 1

---

## 💡 ILUMINAÇÃO - PALETA FINAL

**Verde Tóxico** (RGB 50, 255, 120):
- Dominante na Sala 1 e 2
- Cápsulas e líquidos
- Iluminação principal

**Branco Fluorescente** (RGB 200, 220, 255):
- Salas 4, 5, 6
- Laboratório padrão
- Técnico

**Vermelho Emergência** (RGB 255, 70, 70):
- Sala 3 (Controle)
- Sala 6 (Quarentena)
- Piscante (style 2)

**Azul Computador** (RGB 80, 190, 255):
- Sala 3 (painel)
- Pequena intensidade

**Alaranja Técnico** (RGB 255, 140, 60):
- Sala 7 (Geradores)
- Status de funcionamento

---

## 🚪 PORTAS

### Porta 1: Sala 1 ↔ Sala 2
- Tipo: Porta de laboratório com janela
- Largura: 64 unidades
- Estado: Funcional

### Porta 2: Sala 1 ↔ Sala 4
- Tipo: Porta de laboratório padrão
- Largura: 64 unidades
- Estado: Funcional

### Porta 3: Sala 1 ↔ Sala 3
- Tipo: Porta de vidro duplo
- Largura: 96 unidades
- Estado: Funcional

### Porta 4: Sala 3 ↔ Sala 7
- Tipo: Porta técnica
- Largura: 64 unidades
- Estado: Com dano (lenta)

### Porta 5: Sala 4 ↔ Sala 5
- Tipo: Porta de corredores
- Largura: 64 unidades
- Estado: Funcional

### Porta 6: Sala 6 ↔ Sala 8
- Tipo: Porta de quarentena reforçada
- Largura: 64 unidades
- Estado: Travada (necessário acionar)

### Porta 7: Sala 8 ↔ Sala 3
- Tipo: Porta de emergência
- Largura: 64 unidades
- Estado: Danificada

---

## 🧬 SPAWNS

### SPAWNS HUMANOS (Terroristas)
1. Posição: (96, 96, 8) | Ângulo: 0° | Sala: Saída principal
2. Posição: (176, 176, 8) | Ângulo: 0° | Sala: Almoxarifado norte
3. Posição: (864, 160, 8) | Ângulo: 180° | Sala: Médico leste
4. Posição: (864, 848, 8) | Ângulo: 180° | Sala: Saída sul

**Total**: 4 spawns humanos

### SPAWNS ZUMBIS (CT / Zombies)
1. Posição: (512, 512, 8) | Sala: Centro principal
2. Posição: (320, 400, 8) | Sala: Cápsula quebrada
3. Posição: (800, 500, 8) | Sala: Almoxarifado
4. Posição: (200, 800, 8) | Sala: Quarentena
5. Posição: (500, 350, 8) | Sala: Entrada túnel (manutenção)

**Total**: 5 spawns zumbis

---

## 📏 DIMENSÕES EXATAS (EM UNIDADES GOLDSRC)

| Sala | X1 | Y1 | X2 | Y2 | Altura | Área |
|------|----|----|----|----|--------|------|
| Principal | 320 | 320 | 640 | 640 | 128 | 102.4k |
| Cápsulas | 640 | 320 | 1024 | 640 | 128 | 147.5k |
| Controle | 640 | 640 | 1024 | 768 | 128 | 49.1k |
| Médico | 128 | 320 | 320 | 640 | 128 | 61.4k |
| Almox | 1024 | 320 | 1152 | 640 | 128 | 40.9k |
| Quarentena | 0 | 640 | 320 | 768 | 128 | 40.9k |
| Geradores | 1024 | 640 | 1152 | 768 | 128 | 16.4k |
| Quaren Sec | 128 | 768 | 320 | 896 | 128 | 24.5k |

**Mapa Total**: ~1152x896 unidades (compacto)
**Volume Jogável**: ~543.1k unidades³

---

## 🛠️ TEXTURAS

**Material de Parede Industrial**:
- Cor: Cinza metálico (#A0A0A0)
- Padrão: Horizontal (tipo industrial)

**Piso de Laboratório**:
- Cor: Cinza claro (#D3D3D3)
- Padrão: Quadriculado/telado

**Parede de Vidro** (cápsulas):
- Cor: Verde claro com opacidade
- Padrão: Translúcido

**Parede de Quarentena**:
- Cor: Amarela (#FFFF00) com listras pretas
- Padrão: Biohazard

**Teto**:
- Cor: Cinza (#808080)
- Padrão: Painéis suspensos

---

## 🎮 PARÂMETROS DE COMPILAÇÃO

**Para compilar o mapa com sucesso no GoldSrc/Hammer:**

```
VBSP:
-game cstrike
-onlyents
-noclip

VVIS:
-game cstrike

VRAD:
-game cstrike
-soft
-bounce 2
-nosky
```

---

## 📋 CHECKLIST PRÉ-COMPILAÇÃO

- [ ] Worldspawn definido com skyname "city"
- [ ] Todas as áreas com ceiling (teto) acima de 128 unidades
- [ ] Todas as áreas tem piso
- [ ] Sem espaços abertos infinitos
- [ ] Portas funcionando corretamente
- [ ] Spawns de humanos com "goal" visível
- [ ] Spawns de zumbis em pontos estratégicos
- [ ] Iluminação balanceada (sem áreas totalmente escuras)
- [ ] Nenhuma entidade com propriedades inválidas
- [ ] Sem brush sobrepostos
- [ ] BSP está "sealed" (selado)
- [ ] Testado com vbsp / vvis / vrad

---

## 🎯 INSTRUÇÕES PARA IA GERAR O MAPA

**Ao usar a IA para criar o mapa, instrua-a:**

1. **Crie um arquivo .vmf em formato GoldSrc válido**
   - Versioninfo: editorversion "400", formatversion "100"
   - Estrutura world com worldspawn
   - Remova qualquer chave HDR ou Source 2

2. **Para cada sala:**
   - Crie um bloco sólido (brush)
   - Adicione paredes (6 sides por brush)
   - Use material "DEV/DEV_MEASUREGENERIC01" ou texturas similares
   - Defina uaxis e vaxis para cada face
   - Não use "smoothing_groups" ou "rotation" - essas são chaves inválidas para GoldSrc

3. **Para cápsulas:**
   - Use cilindros (criar com múltiplos brushes)
   - Aplique textura translúcida verde
   - Adicione efeito de líquido (sprite green luminoso)

4. **Para portas:**
   - func_door para portas normais
   - func_door_rotating para portas pivô
   - Defina propriedades: angle, speed, health

5. **Para luzes:**
   - entity classname "light"
   - Propriedades: _light (R G B intensidade)
   - Adicione pitch -90 (apontando para baixo)

6. **Para spawns:**
   - entity classname "info_player_start" (humanos)
   - entity classname "info_player_deathmatch" (zumbis)
   - Defina origin (posição XYZ) e angles (rotação)

7. **Validação final:**
   - Nenhuma chave desconhecida do VMF
   - Todas as entidades com IDs únicos
   - Brushes com face válidas (mínimo 4 lados por brush)
   - Sem brushes não-manifold

---

## 📦 ARQUIVOS GERADOS

Ao final, o mapa deve gerar:

1. `zm_small_laboratory.vmf` (arquivo do editor)
2. `zm_small_laboratory.bsp` (mapa compilado - gerado após compilação)
3. `zm_small_laboratory.nav` (navigation mesh - opcional para bots)

---

## 🚀 PRÓXIMOS PASSOS

1. Usar a IA com essas instruções para gerar o .vmf
2. Abrir o arquivo no Hammer Editor
3. Ajustar visuais e gameplay
4. Compilar com VBSP + VVIS + VRAD
5. Testar no servidor CS 1.6
6. Refinar layout conforme feedback

---

**Projeto finalizado e pronto para produção com IA!**
