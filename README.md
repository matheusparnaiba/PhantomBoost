<div align="center">

  <img src="https://via.placeholder.com/150/00ff41/000000?text=PB" alt="PhantomBoost Logo" width="120" height="120" />

  # 👻 PHANTOM BOOST
  **O Farm de Horas Steam Definitivo.**

  [![Version](https://img.shields.io/github/v/release/SEU_USUARIO/SEU_REPO?style=for-the-badge&color=00ff41&label=Versão)](https://github.com/SEU_USUARIO/SEU_REPO/releases/latest)
  [![Platform](https://img.shields.io/badge/plataforma-Windows-blue?style=for-the-badge&logo=windows)]()
  [![Security](https://img.shields.io/badge/segurança-AES--256-red?style=for-the-badge&logo=lock)]()
  [![Status](https://img.shields.io/badge/status-ONLINE-success?style=for-the-badge)]()

  <p align="center">
    Um cliente desktop robusto, seguro e moderno para "farmar" horas em jogos da Steam sem precisar baixá-los.<br>
    Interface <b>Hacker/Neon</b>, suporte a múltiplas contas, proxy e foco total em privacidade.
  </p>

  <h3>
    <a href="https://github.com/SEU_USUARIO/SEU_REPO/releases/latest">📥 Baixar Última Versão</a>
    <span> • </span>
    <a href="https://github.com/SEU_USUARIO/SEU_REPO/issues">💬 Reportar Bug</a>
  </h3>

</div>

---

## ✨ Por que usar o PhantomBoost?

Diferente de scripts complexos ou sites que pedem sua senha e cobram mensalidade, o **PhantomBoost** roda localmente no seu computador. Seus dados são criptografados e nunca saem da sua máquina.

### 🔥 Funcionalidades de Elite

| Recurso | Descrição |
| :--- | :--- |
| **🛡️ Segurança Militar** | Suas senhas e tokens são criptografados com **AES-256** localmente. Nem nós temos acesso. |
| **👥 Multi-Contas** | Gerencie e farme dezenas de contas simultaneamente em uma única janela. |
| **🌐 Suporte a Proxy** | Evite *shadowbans* da Steam. Configure proxies (HTTP/SOCKS5) individuais para cada conta. |
| **🎮 Discord RPC** | Mostre status personalizados no seu perfil do Discord ("Farmando em X contas"). |
| **⚡ Auto-Start** | Inicia minimizado junto com o Windows e retoma o farm automaticamente em background. |
| **🔐 Steam Guard** | Suporte completo a 2FA. O sistema salva seu *Refresh Token* para não pedir código toda vez. |
| **🎨 UI Cyberpunk** | Interface moderna, *frameless* (sem bordas), com tema Dark/Neon e efeitos visuais. |
| **🔄 Auto-Update** | O aplicativo detecta, baixa e instala novas versões automaticamente via GitHub. |

---

## 📸 Interface

<div align="center">
  <img src="https://via.placeholder.com/800x450/0d1117/00ff41?text=Preview+do+PhantomBoost" alt="Interface Principal" style="border-radius: 10px; border: 2px solid #00ff41; box-shadow: 0 0 20px rgba(0, 255, 65, 0.2);">
</div>

---

## 🚀 Instalação e Uso

### 1. Download
Vá até a aba **[Releases](https://github.com/SEU_USUARIO/SEU_REPO/releases)** e baixe o arquivo `PhantomBoost.Setup.exe`.

### 2. Instalação
Execute o instalador. Ele fará todo o processo automaticamente.
> **Nota:** Como este é um software independente e gratuito, o Windows SmartScreen pode exibir um aviso azul na primeira vez.
> Clique em **"Mais Informações"** -> **"Executar assim mesmo"**.

### 3. Configuração Rápida
1.  Abra o **PhantomBoost**.
2.  Clique em **"+ Adicionar Conta"**.
3.  Preencha:
    * **Usuário/Senha**: Seus dados da Steam.
    * **Jogos**: IDs dos jogos separados por vírgula (ex: `730, 440`).
    * **Proxy** *(Recomendado)*: Se usar muitas contas, coloque um proxy.
4.  Clique em **Salvar**.
5.  Clique em **INICIAR FARM**.

---

## ❓ Perguntas Frequentes (FAQ)

<details>
<summary><strong>🔐 É seguro? Minha conta será roubada?</strong></summary>
<br>
Sim, é seguro. O PhantomBoost é um software local. Ele armazena suas credenciais em um arquivo <code>config.json</code> na sua pasta <code>%AppData%</code> do Windows. Antes de salvar, ele aplica uma criptografia <strong>AES-256</strong>. O software apenas comunica-se diretamente com os servidores da Steam (para login) e do GitHub (para atualizações). Nenhum dado é enviado para o criador.
</details>

<details>
<summary><strong>🚫 Posso tomar banimento VAC?</strong></summary>
<br>
O PhantomBoost não injeta nada nos jogos e não modifica arquivos da memória ou DLLs. Ele apenas simula para a rede da Steam que você está "Jogando". A Valve historicamente não bane por idlers de horas, mas use com responsabilidade. <strong>Recomendamos fortemente usar Proxy se for farmar mais de 10 contas no mesmo IP.</strong>
</details>

<details>
<summary><strong>🦠 Meu antivírus detectou algo!</strong></summary>
<br>
Falsos positivos são comuns em softwares novos criados em Electron que não possuem uma assinatura digital cara da Microsoft (Certificado EV). O código apenas manipula conexões de rede para a Steam. Adicione a pasta de instalação às exceções do seu antivírus se necessário.
</details>

---

## 🛠️ Suporte & Bugs

Encontrou um erro ou tem uma ideia para melhorar o projeto?
Abra uma **[Issue](https://github.com/SEU_USUARIO/SEU_REPO/issues)** aqui no GitHub.

---

<div align="center">
  <p>Desenvolvido com 💚 por <strong>Phantom Dev</strong></p>
  <p><i>Este projeto não é afiliado à Valve Corporation. Steam é uma marca registrada da Valve Corp.</i></p>
</div>
