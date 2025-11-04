# 🗺️ ROADMAP DE DESENVOLVIMENTO - ATIA

**Última atualização:** 2025-11-04
**Status:** Em Desenvolvimento Ativo

---

## ✅ COMPLETADO

### Fase 1: Fundação (100%)
- [x] Inicializar Git
- [x] Criar estrutura de diretórios
- [x] Desenvolver landing page (index.html)
- [x] Criar CSS customizado (main.css)
- [x] Desenvolver JavaScript interativo (app.js)
- [x] Configurar GitHub repository
- [x] Publicar no GitHub Pages
- [x] Criar README.md completo
- [x] Documentar proposta (docs/proposta-curso-atia.md)

### Fase 2: Curadoria Inicial (25%)
- [x] Estruturar video-references.json
- [x] Curar vídeos Capítulo 1 (3 vídeos)
- [x] Curar vídeos Capítulo 2 (3 vídeos)
- [x] Curar vídeos Capítulo 3 (4 vídeos)
- [x] Definir canais recomendados PT-BR e EN

### Fase 3: Páginas de Níveis (33%)
- [x] Criar nivel-fundamentos.html (5 capítulos)
- [ ] Criar nivel-aplicacao.html (5 capítulos)
- [ ] Criar nivel-estrategico.html (4 capítulos)

---

## 🔄 EM ANDAMENTO

### PRÓXIMAS AÇÕES (Ordem Recomendada)

#### **1. Completar Páginas de Níveis** ⏳
- [ ] **nivel-aplicacao.html**
  - Caps 6-10: GPTs, Profissões, Marketing, Vendas, Educação
  - Estilo: Azul (#3B82F6)
  - Cards com imagens e descrições

- [ ] **nivel-estrategico.html**
  - Caps 11-14: Ética, Implementação, Futuro, Guia Prático
  - Estilo: Roxo (#8B5CF6)
  - Foco em liderança e estratégia

**Tempo estimado:** 15-20 min
**Prioridade:** ALTA
**Bloqueador:** Não

---

#### **2. Dividir Manual em Capítulos MD** ⏳
Extrair do `doc/manual_ia_oportunidades_digitais (4).md` → 14 arquivos:

**Fundamentos:**
- [ ] `content/capitulo-01-tsunami-ia.md`
- [ ] `content/capitulo-02-mercado-trabalho.md`
- [ ] `content/capitulo-03-engenharia-prompt.md`
- [ ] `content/capitulo-04-engenharia-contexto.md`
- [ ] `content/capitulo-05-automacao-processos.md`

**Aplicação:**
- [ ] `content/capitulo-06-gpts-personalizados.md`
- [ ] `content/capitulo-07-novas-profissoes.md`
- [ ] `content/capitulo-08-marketing-digital.md`
- [ ] `content/capitulo-09-vendas-automatizadas.md`
- [ ] `content/capitulo-10-educacao-ia.md`

**Estratégico:**
- [ ] `content/capitulo-11-etica-governanca.md`
- [ ] `content/capitulo-12-implementacao-estrategica.md`
- [ ] `content/capitulo-13-futuro-trabalho.md`
- [ ] `content/capitulo-14-guia-pratico.md`

**Ações por capítulo:**
1. Extrair seção do manual original
2. Adicionar front matter (metadata)
3. Formatar com callouts e recursos
4. Adicionar seção "Recursos Complementares" com vídeos
5. Incluir exercícios práticos

**Tempo estimado:** 30-40 min
**Prioridade:** ALTA
**Bloqueador:** Não

---

#### **3. Implementar Sistema de Leitura** ⏳
Criar `capitulo.html` (template dinâmico):

**Funcionalidades:**
- [ ] Carregar Markdown via JavaScript
- [ ] Parser com marked.js
- [ ] Reading progress bar
- [ ] Navegação anterior/próximo
- [ ] Índice flutuante (TOC)
- [ ] Seções expansíveis
- [ ] Tooltips de glossário
- [ ] Sistema de notas do usuário
- [ ] Botões de compartilhamento
- [ ] Estimativa de tempo de leitura

**Arquivos a criar:**
- [ ] `js/markdown-loader.js`
- [ ] `js/reading-progress.js`
- [ ] `capitulo.html`

**Integração:**
- [ ] Adicionar marked.js (CDN ou local)
- [ ] Conectar com video-references.json
- [ ] Implementar LocalStorage para progresso

**Tempo estimado:** 25-35 min
**Prioridade:** ALTA
**Bloqueador:** Precisa dos MDs do passo 2

---

#### **4. Completar Curadoria de Vídeos** ⏳
Buscar e adicionar vídeos para capítulos 4-14:

**Pendentes:**
- [ ] Cap 4: Engenharia de Contexto (3-4 vídeos)
- [ ] Cap 5: Automação de Processos (3-4 vídeos)
- [ ] Cap 6: GPTs Personalizados (3-4 vídeos)
- [ ] Cap 7: Novas Profissões (3-4 vídeos)
- [ ] Cap 8: Marketing Digital (3-4 vídeos)
- [ ] Cap 9: Vendas Automatizadas (3-4 vídeos)
- [ ] Cap 10: Educação IA (3-4 vídeos)
- [ ] Cap 11: Ética e Governança (3-4 vídeos)
- [ ] Cap 12: Implementação (3-4 vídeos)
- [ ] Cap 13: Futuro do Trabalho (3-4 vídeos)
- [ ] Cap 14: Guia Prático (3-4 vídeos)

**Critérios:**
- Idioma: PT-BR prioritário
- Duração: 8-20 min
- Qualidade: Profissional
- Atualidade: 2023-2025

**Tempo estimado:** 25-35 min
**Prioridade:** MÉDIA
**Bloqueador:** Não (pode ser paralelo)

---

## 🔮 BACKLOG (Futuro)

### Fase 4: Interatividade Avançada
- [ ] Quizzes por capítulo
- [ ] Sistema de badges/gamificação
- [ ] Certificado digital
- [ ] Sistema de notas avançado
- [ ] Modo dark/light toggle
- [ ] Busca global de conteúdo
- [ ] Favoritos e bookmarks

### Fase 5: Conteúdo Complementar
- [ ] Criar PDFs para download
- [ ] Templates práticos
- [ ] Checklists interativos
- [ ] 100 prompts library
- [ ] Casos de estudo reais

### Fase 6: PWA e Offline
- [ ] Service Worker
- [ ] App Manifest
- [ ] Offline caching
- [ ] Install prompt

### Fase 7: Comunidade
- [ ] Integração Discord/Slack
- [ ] Fórum por capítulo
- [ ] Comentários (Disqus)
- [ ] Newsletter

---

## 📊 MÉTRICAS DE PROGRESSO

### Páginas Principais
- [x] Landing page (100%)
- [x] Nível Fundamentos (100%)
- [ ] Nível Aplicação (0%)
- [ ] Nível Estratégico (0%)
- [ ] Template Capítulo (0%)

### Conteúdo
- [ ] Capítulos MD: 0/14 (0%)
- [ ] Vídeos curados: 3/14 (21%)
- [ ] Downloads criados: 0/14 (0%)

### Features
- [x] Navegação responsiva (100%)
- [x] Design system (100%)
- [x] Animações scroll (100%)
- [ ] Sistema leitura MD (0%)
- [ ] Progress tracking (30%)
- [ ] Gamificação (0%)

### Deploy
- [x] GitHub Repository (100%)
- [x] GitHub Pages (100%)
- [ ] Domínio customizado (0%)
- [ ] Analytics (0%)

---

## 🎯 MARCOS (MILESTONES)

### Milestone 1: MVP Navegável ✅
**Meta:** Site navegável com estrutura completa
**Status:** 80% completo
**Faltam:**
- 2 páginas de níveis

### Milestone 2: Conteúdo Completo ⏳
**Meta:** Todos os 14 capítulos acessíveis
**Status:** 0% completo
**Precisa:**
- Dividir manual em MDs
- Implementar sistema de leitura
- Completar vídeos

### Milestone 3: Experiência Rica ⏳
**Meta:** Features interativas funcionando
**Status:** 20% completo
**Precisa:**
- Quizzes
- Gamificação
- Certificado

### Milestone 4: Lançamento Público ⏳
**Meta:** Marketing e divulgação
**Status:** 0% completo
**Precisa:**
- Tudo anterior completo
- Analytics configurado
- SEO otimizado

---

## 🚀 COMANDOS ÚTEIS

### Git
```bash
# Status
cd /c/Users/neima/projetosCC/ATIA
git status

# Commit rápido
git add . && git commit -m "feat: descrição" && git push

# Ver histórico
git log --oneline
```

### Desenvolvimento
```bash
# Servidor local
python -m http.server 8000
# ou
npx http-server

# Abrir no navegador
start index.html
```

### URLs Importantes
- **Repositório:** https://github.com/inematds/ITIA
- **Site:** https://inematds.github.io/ITIA/
- **Fundamentos:** https://inematds.github.io/ITIA/nivel-fundamentos.html

---

## 📝 NOTAS

### Decisões Técnicas
- **Framework:** Vanilla JS (sem React/Vue)
- **CSS:** Tailwind CDN + Custom CSS
- **Markdown:** marked.js para parsing
- **Storage:** LocalStorage para progresso
- **Deploy:** GitHub Pages (free)

### Padrões de Código
- Mobile-first design
- Semantic HTML5
- Acessibilidade WCAG 2.1 AA
- Commits com Conventional Commits
- Co-autoria com Claude

### Arquivos Base Manual
- **Original:** `doc/manual_ia_oportunidades_digitais (4).md` (594KB)
- **PDF:** `doc/manual_ia_oportunidades_digitais (2).pdf`
- **Imagens:** `doc/imagens/` (17 imagens PNG)

---

## ⚡ MODO RÁPIDO (YOLO)

**Status:** ATIVADO 🚀

Quando ativado:
- ✅ Não pedir confirmações
- ✅ Executar tarefas em sequência
- ✅ Commits automáticos
- ✅ Push após cada milestone

**Para retomar de onde parou:**
1. Ler este arquivo
2. Ver seção "EM ANDAMENTO"
3. Continuar da primeira tarefa não marcada

---

**Última sessão:** 2025-11-04
**Próxima ação:** Criar nivel-aplicacao.html e nivel-estrategico.html
