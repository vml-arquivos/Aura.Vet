# 🐾 AURA.VET — Sistema Inteligente de Clínicas Veterinárias

> **AURA.VET** é uma plataforma moderna e modular desenvolvida com foco em **inovação, automação e atendimento humanizado**.  
> Conecta **IA**, **automação n8n**, **Supabase**, **Google Calendar** e **WhatsApp** em um ecossistema unificado para clínicas veterinárias.

---

## 🧠 Visão Geral

O **AURA.VET** combina:
- 💬 **IA humanizada (Lara)** para comunicação com clientes e tutores  
- 🧩 **n8n** como orquestrador de fluxos automáticos  
- 🗓️ **Integração com Google Calendar** para agendamentos e lembretes  
- 🐶 **Gestão de tutores, pets, consultas e vacinas**  
- 🌐 **Dashboard Next.js + Supabase**  
- 🧭 **Site institucional** integrado para captação de leads e agendamentos  
- ⚙️ **Infraestrutura Docker + GitHub Actions (CI/CD)**

---

## 🏗️ Estrutura do Projeto

```bash
aura.vet/
├── frontend/        # Dashboard (Next.js + Supabase)
├── website/         # Site institucional (Next.js)
├── n8n/             # Workflows JSON (agendar, cancelar, lembretes)
├── database/        # Schema SQL e seeds iniciais
├── infra/           # Docker Compose, Nginx, CI/CD
├── docs/            # Arquitetura, personas e roadmap
├── brand/           # Logo, favicon e identidade visual
└── .env.example     # Variáveis de ambiente
