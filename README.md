# 🎯 Sistema de Carreira — Módulo 1: Âncoras de Carreira

Formulário interativo de diagnóstico de Âncoras de Carreira baseado na metodologia de **Edgar Schein**, com geração de relatório PDF, exportação para planilha Excel e histórico de respondentes persistido localmente.

---

## 🚀 Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 📋 Formulário completo | 40 questões com escala de 1–6 e progresso em tempo real |
| 🎯 8 âncoras mapeadas | TF · GG · AI · SE · CE · SD · PD · EV |
| 📄 Relatório PDF (3 páginas) | Capa, resultados com barras, descritivo, cargos e gabarito |
| 📊 Planilha XLSX | Histórico cumulativo de todos os respondentes |
| 💾 Histórico local | Resultados salvos em localStorage — persiste entre sessões |
| 📱 Responsivo | Funciona em desktop, tablet e mobile |

---

## 🏷️ As 8 Âncoras de Carreira

| Cód. | Âncora | Perfil |
|---|---|---|
| TF | Técnico Funcional | Excelência técnica e especialização |
| GG | Gerência Geral | Liderança executiva e gestão de alta complexidade |
| AI | Autonomia e Independência | Liberdade de atuação e métodos próprios |
| SE | Segurança e Estabilidade | Previsibilidade e proteção de longo prazo |
| CE | Criatividade e Empreendedorismo | Criar negócios e inovar do zero |
| SD | Serviço e Dedicação | Propósito e impacto social |
| PD | Puro Desafio | Problemas extremos e situações impossíveis |
| EV | Estilo de Vida | Equilíbrio profissional-pessoal |

---

## 📁 Estrutura do Repositório

```
sistema-carreira/
├── index.html                    # Formulário completo (standalone)
├── historico_ancoras.xlsx        # Template de planilha para histórico
├── docs/
│   └── metodologia.md            # Metodologia detalhada de Schein
├── assets/
│   └── (futuros logos e imagens)
└── README.md
```

---

## 🛠️ Como Usar

### Opção 1 — Direto no navegador (zero configuração)
```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/sistema-carreira.git
cd sistema-carreira

# Abra o arquivo no navegador
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

### Opção 2 — GitHub Pages
1. Vá em **Settings > Pages**
2. Selecione a branch `main` e pasta `/ (root)`
3. Acesse em: `https://SEU_USUARIO.github.io/sistema-carreira/`

### Opção 3 — Servidor local
```bash
python3 -m http.server 8080
# Acesse: http://localhost:8080
```

---

## 📊 Histórico em Planilha

Após concluir o teste, clique em **"📊 Salvar em Planilha"**. O sistema:
1. Salva o resultado no `localStorage` do navegador (persistência local)
2. Gera um arquivo `.xlsx` com **todos os respondentes acumulados**
3. A planilha possui duas abas: **Histórico** e **Âncoras – Referência**

> **Dica para RH:** Colete os arquivos `.xlsx` gerados pelos respondentes e consolide manualmente, ou implemente um backend para centralizar os dados.

---

## 🗺️ Roadmap

- [ ] Módulo 2: Estilos de Liderança
- [ ] Módulo 3: Maturidade Profissional  
- [ ] Módulo 4: Valores Organizacionais
- [ ] Backend para centralizar histórico (Node.js / Supabase)
- [ ] Dashboard gerencial por empresa
- [ ] Relatório comparativo de equipes

---

## 📚 Referência

> Schein, E. H. (1990). *Career Anchors: Discovering Your Real Values*. Pfeiffer & Company.

---

## 📄 Licença

Uso interno. Todos os direitos reservados.
