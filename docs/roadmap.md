# Roadmap — Dev Forge ⚒️

Este documento descreve a evolução planejada do **Dev Forge**, um ambiente de desenvolvimento local moderno, modular e open-source para PHP.

O roadmap prioriza **estabilidade, experiência do desenvolvedor e extensibilidade**, evitando escopo inflado prematuramente.

---

## 🧭 Princípios do roadmap

- **MVP funcional antes de features avançadas**
- **DX acima de hype**
- **Pouca magia, muito controle**
- **Modularidade como regra**
- **Multiplataforma desde o início**

---

## 🟢 Fase 1 — Fundação (Core)

📅 Objetivo: estabelecer uma base sólida e extensível.

### Core
- [x] Estrutura inicial do projeto
- [x] App base com NativePHP + Laravel
- [x] Sistema de configuração central
- [x] Persistência local (SQLite)
- [x] Logger centralizado

### Sistema de módulos
- [x] Loader de módulos
- [x] Registro automático via Service Provider
- [x] Ciclo de vida do módulo (enable / disable)
- [x] Comunicação Core ↔ Módulos

### UI base
- [x] Shell da aplicação
- [x] Navegação principal
- [x] Layout responsivo
- [ ] Tema claro / escuro

---

## 🟡 Fase 2 — MVP funcional

📅 Objetivo: substituir o uso básico do Laragon.

### PHP Manager (MVP)
- [ ] Instalação de versões do PHP
- [ ] Alternar versão global
- [ ] Executar PHP via CLI interno
- [ ] Gerenciar extensões básicas
- [ ] php.ini global

### Web Server
- [ ] Nginx integrado
- [ ] Start / Stop via UI
- [ ] Configuração automática
- [ ] Logs acessíveis pela interface

### Gerenciador de projetos
- [ ] Criar projeto local
- [ ] Detectar projetos existentes
- [ ] Vincular projeto ↔ PHP
- [ ] Virtual host automático (`.test`)
- [ ] Start / Stop por projeto

### UX
- [ ] Feedback visual de status
- [ ] Mensagens de erro claras
- [ ] Loading states consistentes

---

## 🔵 Fase 3 — Experiência de desenvolvedor

📅 Objetivo: tornar o Forge prazeroso para uso diário.

### PHP avançado
- [ ] Versão de PHP por projeto
- [ ] Extensões por projeto
- [ ] php.ini isolado
- [ ] Integração com Composer

### Ferramentas de desenvolvimento
- [ ] CLI integrada
- [ ] Atalhos para Artisan
- [ ] Execução de scripts
- [ ] Terminal embutido (opcional)

### Projetos
- [ ] Templates (Laravel, Slim, etc.)
- [ ] Criação de projeto com 1 clique
- [ ] Reset rápido de ambiente

---

## 🟣 Fase 4 — Modularidade real

📅 Objetivo: permitir crescimento sem acoplamento.

### Sistema de plugins
- [ ] API pública para módulos
- [ ] Documentação para criadores de plugins
- [ ] Versionamento de módulos
- [ ] Enable / disable sem reiniciar app

### Módulos oficiais
- [ ] Database Manager
- [ ] Git Manager
- [ ] Node / Bun Manager
- [ ] Backup & Restore

---

## 🟠 Fase 5 — Estabilidade e distribuição

📅 Objetivo: uso confiável em produção local.

### Build & distribuição
- [ ] Build automatizado Windows
- [ ] Build automatizado Linux
- [ ] Empacotamento portátil
- [ ] Assinatura de binários (quando aplicável)

### Atualizações
- [ ] Sistema de update do core
- [ ] Update independente de módulos
- [ ] Rollback seguro

---

## ⚫ Fase 6 — Comunidade e futuro

📅 Objetivo: sustentabilidade do projeto.

### Comunidade
- [ ] Guia de contribuição
- [ ] Templates de issues e PRs
- [ ] Discussões abertas
- [ ] Roadmap público revisável

### Futuro
- [ ] Suporte a macOS
- [ ] Marketplace de módulos
- [ ] Integração com containers (opcional)
- [ ] Telemetria opcional e transparente

---

## 🧠 Nota final

Este roadmap é **vivo**.

Funcionalidade só entra se:
- Melhorar a experiência do desenvolvedor
- Manter o projeto simples
- Não comprometer a filosofia do Dev Forge

Qualidade > quantidade.

---
