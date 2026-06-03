# Orçamento — Redesign e painel de administração do site FEMCO Pré-Moldados

**Cliente:** FEMCO Pré-Moldados  
**Site atual:** http://femco.com.br/  
**Data do orçamento:** 03/06/2026  
**Validade:** 30 dias  

---

## 1. Diagnóstico (resumo)

| Item | Situação |
|------|----------|
| Plataforma | PHP legado (**PHP 5.3**), sem manutenção desde ~2014 |
| Segurança | Sem **HTTPS** |
| Conteúdo | 5 seções, **9** produtos, **15** soluções, **~50** galerias de obras, **100+** imagens |
| Última atualização de fotos | **Dez/2022** |

---

## 2. Proposta — Pacote único

### Investimento

| **Valor fechado** | **R$ 6.000,00** |
| **Prazo** | **4 a 6 semanas** |

### O que está incluído

| Item | Detalhe |
|------|---------|
| **Site responsivo** | Layout moderno e limpo (tema/componentes prontos customizados com cores e logo da FEMCO) |
| **Páginas** | Home, Empresa, Produtos, Soluções, Obras, Contato/Orçamento |
| **Produtos e soluções** | Listagem + página de detalhe para os itens atuais (migração de textos e imagens existentes) |
| **Obras** | Listagem em grid + página de galeria por obra (migração das **~50** obras já publicadas) |
| **Formulário** | Contato/orçamento com envio para **orcamento@femco.com.br** + proteção anti-spam básica |
| **HTTPS** | Certificado SSL e site só em `https://` |
| **Migração** | Textos, imagens e redirects das URLs `.php` antigas |
| **SEO básico** | Títulos, descrições, sitemap, Google Search Console + **GA4** |
| **Painel admin** | WordPress (ou similar) para a FEMCO **cadastrar obras e fotos** sozinha |
| **WhatsApp** | Botão flutuante com link direto |
| **Mapa** | Google Maps no rodapé/contato |


## 3. Stack (enxuta e barata de manter)

| Camada | Escolha |
|--------|---------|
| Site | **WordPress** + tema leve customizado |
| Hospedagem | Plano compartilhado/VPS simples com SSL (Hostinger, HostGator, etc.) |
| Galerias | Plugin de galeria + campos customizados (obras por cadastro) |
| Imagens | Compressão na migração (sem retrabalho foto a foto) |
| Formulário | WPForms / Contact Form 7 + SMTP |

---

## 4. Mapa de páginas

```
/                 Home (banner, diferenciais, CTA orçamento, obras em destaque)
/empresa          Texto institucional
/produtos         Lista dos 9 produtos
/produtos/...     Detalhe (conteúdo migrado)
/solucoes         Lista das 15 soluções
/solucoes/...     Detalhe (conteúdo migrado)
/obras            Grid de obras
/obras/...        Galeria da obra
/contato          Formulário, telefones, mapa, e-mail
```

**Privacidade (LGPD):** página modelo simples (texto padrão para o cliente revisar).

---

## 5. Cronograma

| Semana | Entrega |
|--------|---------|
| 1 | Acesso ao site antigo, hospedagem nova, estrutura WordPress, layout base |
| 2 | Páginas institucionais, produtos e soluções migrados |
| 3 | Obras migradas, formulários, SSL |
| 4 | QA mobile, SEO, redirects, treinamento rápido (30 min) |
| 5–6 | *Reserva* se atraso na aprovação ou envio de conteúdo pelo cliente |

---

## 6. Pagamento

| Etapa | % | Valor (R$ 6.000) |
|-------|---|------------------|
| Início do projeto | 50% | R$ 3.000 |
| Publicação (go-live) | 50% | R$ 3.000 |

---

## 7. Custos do cliente (fora dos R$ 6k)

Hospedagem | R$ 60/mês

---

*Proposta válida por 30 dias. Valores sem impostos retidos na fonte; nota fiscal conforme regime do prestador.*
