# 📷 Natália Figueredo — Fotografia Afetiva & Documental

Este projeto é uma **landing page modelo de alto padrão** para portfólio fotográfico e apresentação de serviços de fotografia afetiva, gestante, família, recém-nascidos e celebrações infantis.

O design foi estruturado combinando as melhores referências do mercado nacional:
- **Juliana Eliziário:** tipografia refinada, estética minimalista com tons linho/musgo e micro-copy poético ("tempo & presença").
- **Dina Carvalho:** narrativa de estúdio boutique, valorização do álbum de linho e acabamento nobre.
- **Atelier Fotografia Afetiva (Aline Lelles):** manifesto humanizado, acolhimento e valorização da espontaneidade.
- **Alan Smyth & Soraya Pamplona:** clareza na apresentação das categorias de ensaios e múltiplos pontos de conversão direta para o WhatsApp.
- **Alê Nardes:** estrutura fluida, portfólio visual com foco em luz natural e conexões genuínas.

---

## ✨ Recursos Implementados

1. **Barra de Anúncio Superior (Topbar):** Status da agenda com indicador pulsante de exclusividade e vagas limitadas.
2. **Header Fixo (Glassmorphism Pill):** Navegação suave e botão de reserva sempre acessível.
3. **Hero Cinemático:** Título com serifa editorial (*Playfair Display* e *Cormorant Garamond*), poesia de abertura, selo rotativo afetivo e duplo CTA.
4. **Manifesto & Os 3 Pilares:** Reflexão sobre memória geracional e os diferenciais do atendimento humanizado.
5. **Apresentação de Experiências (Serviços):** Cards com fotos temáticas, tags, listas do que está incluso e botões de consulta de datas (Gestante, Família Lifestyle, Newborn Afetivo, Festas & Batizados).
6. **Portfólio Editorial Filtrável:** Grid dinâmico com abas de categoria (Todos, Gestante, Família, Newborn, Celebrações) e frases poéticas intercaladas.
7. **Lightbox Modal em Tela Cheia:** Clique em qualquer imagem para abrir em alta resolução com legenda e tag.
8. **Simulador Interativo de Ensaio:** O cliente escolhe o tipo de ensaio, o local (casa, externo, estúdio) e adicionais (álbum de linho, caixa de madeira), gerando um resumo com mensagem pronta para o WhatsApp.
9. **A Jornada do Cliente (Linha do Tempo em 5 Passos):** Da primeira conversa à entrega do álbum impresso.
10. **O Álbum Afetivo (Foto-produto):** Seção dedicada à tangibilidade do álbum encadernado em linho puro com gravação dourada.
11. **Sobre a Natália Figueredo:** Bio calorosa, foto e filosofia autoral.
12. **Depoimentos & Prova Social:** Avaliações 5 estrelas de famílias reais.
13. **Perguntas Frequentes (FAQ Acordeão):** Respostas para as dúvidas mais comuns (vergonha de posar, idade gestacional, prazos, etc.).
14. **Formulário de Contato com Redirecionamento Inteligente:** O cliente preenche seus dados e é encaminhado direto ao WhatsApp com a mensagem formatada.
15. **Botão Flutuante do WhatsApp:** Fixado no canto inferior direito para contato imediato.

---

## 🚀 Como Visualizar Localmente

Basta dar dois cliques no arquivo `index.html` ou abri-lo com qualquer navegador (Google Chrome, Microsoft Edge, Safari, Firefox).

Se preferir rodar um servidor local no terminal PowerShell:
```powershell
# Dentro da pasta do projeto:
python -m http.server 8000
# Acesse no navegador: http://localhost:8000
```

---

## 🛠️ Como Personalizar

### 1. Alterar o número de WhatsApp
No arquivo `index.html`, faça um substituir de:
`5561999999999`
pelo número real com DDI e DDD (exemplo: `5561981234567`).

### 2. Trocar as fotos pelas fotos autorais da Natália
- Crie uma pasta chamada `imagens/` no projeto.
- Coloque suas fotos salvas em formato `.jpg` ou `.webp`.
- No `index.html`, substitua as URLs temporárias do Unsplash pelo caminho local (ex: `imagens/hero-gestante.jpg` ou `imagens/portfolio-familia-01.jpg`).

### 3. Publicação Gratuita na Web
Este site é estático (HTML, CSS e JS puros), por isso pode ser hospedado de graça em minutos através de:
- **Netlify:** Arraste e solte a pasta do projeto em [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel:** Conecte o repositório ou use `npx vercel`
- **GitHub Pages:** Suba para um repositório no GitHub e ative o Pages nas configurações
- **Cloudflare Pages / Hostinger / Registro.br:** Compatível com qualquer servidor padrão.
