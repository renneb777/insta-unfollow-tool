<p align="center">
  <img src="/assets/logo_small.png" alt="Insta Unfollow Tool Logo" width="100">
</p>

<h1 align="center">🚀 Insta Unfollow Tool</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Vers%C3%A3o-1.0.0-667eea?style=for-the-badge&logo=android" alt="Versão 1.0.0">
  <img src="https://img.shields.io/badge/Estilo-Nativo%20Kotlin-764ba2?style=for-the-badge&logo=kotlin" alt="Kotlin Native">
  <img src="https://img.shields.io/badge/Premium-Dispon%C3%ADvel-ffeb3b?style=for-the-badge&logo=gumroad" alt="Premium Disponível">
  <img src="https://img.shields.io/github/license/renneb777/insta-unfollow-tool?style=for-the-badge" alt="Licença">
</p>

<p align="center">
  <a href="https://renneb777.github.io/insta-unfollow-tool/" target="_blank">💻 Veja a Landing Page Oficial</a> | 
  <a href="" target="_blank">⭐ Baixe Apk para Ativar Premium </a>
</p>

---

<p align="center">
  <strong>Insta Unfollow Tool</strong> é um aplicativo Android nativo, super rápido e seguro, que resolve o maior problema de UX do Instagram: descobrir quem não te segue de volta. Chega de usar APIs públicas instáveis; este app injeta JavaScript inteligente e usa a própria interface privada do Instagram para entregar resultados rápidos e precisos.
</p>

## ✨ Funcionalidades Mestres (O que torna este app único)

Este app foi construído com foco em **velocidade**, **segurança** e **experiência do usuário (UX)**. Você não vai encontrar essa combinação em apps gratuitos.

* **🖼️ Lista Visível (Novidade!):** Agora você vê quem não te segue de volta com **foto de perfil** e nome, igualzinho ao Instagram original.
* **🔍 Análise Ultrarrápida com Cache:** Chega de esperar milênios. O app usa a API interna do Instagram (via JS injection) e salva os resultados em um **Cache de Memória nativo em Kotlin**. Se você analisar o mesmo perfil novamente, o resultado é **instantâneo** (0.1s!).
* **🛡️ Escudo Anti-Ban (Anti-Shadowban):** O Instagram baniu unfollows em massa? Nosso app tem um freio nativo. Ele conta seus unfollows diários. Se você chegar em **150 por dia**, o app bloqueia novas remoções para proteger a sua conta e simula pausas de 3 segundos entre cada ação, imitando o comportamento humano.
* **⭐ Whitelist (Lista de Proteção):** Tem perfis (famosos, amigos próximos ou marcas) que você quer continuar seguindo? Adicione-os à sua **Whitelist** com um clique na estrela e o app **nunca** mais sugerirá dar unfollow neles.
* **🎯 Posição Flutuante Nativa:** O botão flutuante **"🚀 Tool"** segue o design moderno do Android, flutuando sobre o Instagram. O melhor: você pode **arrastar e soltar** o botão para qualquer canto da tela para não atrapalhar sua navegação.

## 📸 Guia Visual do Aplicativo

<p align="center">
  <img src="/assets/login.jpeg" width="20%" alt="Tela de Login do Instagram">
  <img src="/assets/analise.jpeg" width="20%" alt="Lista de Análise e Estatísticas">
  <img src="/assets/unfollow.jpeg" width="20%" alt="Modal de Unfollow e Anti-Ban">
</p>

## ⚙️ Arquitetura e Stack Técnica

O projeto foi construído direto no Android Studio, seguindo as melhores práticas de desenvolvimento nativo moderno.

* **Linguagem Principal:** Kotlin.
* **WebView & JS Injection:** Usamos a `android.webkit.WebView` para carregar o Instagram e injetamos códigos JavaScript `async/await` assíncronos para conversar com a API privada.
* **Persistência (Cache):** Utilizamos `SharedPreferences` para salvar o estado Premium, a sua Whitelist de proteção e as estatísticas do Anti-Ban de forma leve e rápida.
* **Renderização Dinâmica:** Usamos `Thread` nativas para baixar as fotos de perfil e renderizar listas complexas de `LinearLayout` e `CardView` em tempo real.

## 📥 Como Instalar (O Guia para Amigos)

Como o app não está na Play Store oficial, você precisa instalar o APK manualmente.

1.  Baixe o arquivo `.apk` oficial `https://renneb777.github.io/insta-unfollow-tool/`.
2.  No seu Android, ao abrir o arquivo, o sistema vai pedir permissão para instalar de **"Fontes Desconhecidas"**. Ative essa opção.
3.  Quando o antivírus do Google (Play Protect) aparecer avisando que é um "Desenvolvedor Desconhecido", clique em **"Mais detalhes"** e depois em **"Instalar mesmo assim"**.

## 🛡️ Disclaimer de Segurança

Este aplicativo é uma ferramenta de terceiros, construída com o objetivo de estudo de automação móvel.
* Nós **NUNCA** salvamos, enviamos ou temos acesso ao seu login ou senha do Instagram. Todo o login é feito de forma segura e local dentro da WebView oficial do Instagram.
* **Use com responsabilidade.** O app possui Escudo Anti-Ban, mas o uso excessivo de automações ainda pode resultar em bloqueios temporários por parte do Instagram. O usuário é o único responsável pela utilização da ferramenta.

---
### 🤝 Desenvolvido por

<p align="left">
  <a href="https://github.com/renneb777" target="_blank">
    <strong>Renne B.</strong> (Sistemas de Informação)
  </a>
</p>
<p align="left">
  <em>Inovando com Kotlin e UX Nativa.</em>
</p>
