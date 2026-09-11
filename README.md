<div align="center">

# CanetaNaTela — Distribuição Oficial de Executáveis

[![Versão](https://img.shields.io/badge/Vers%C3%A3o-v0.1.0-0d9488?style=for-the-badge)](https://github.com/AnalistaOtgan/CanetaRelease/releases)
[![Plataforma](https://img.shields.io/badge/Plataforma-Windows_x64-0284c7?style=for-the-badge)](https://github.com/AnalistaOtgan/CanetaRelease/releases)
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-10b981?style=for-the-badge)](https://github.com/AnalistaOtgan/CanetaNaTela/blob/main/LICENSE)
[![Código Fonte](https://img.shields.io/badge/Reposit%C3%B3rio-CanetaNaTela-6366f1?style=for-the-badge)](https://github.com/AnalistaOtgan/CanetaNaTela)

**Repositório oficial de distribuição dos binários compilados do CanetaNaTela.**  
Utilitário nativo de anotação vetorial sobreposta, apresentação e gravação de tela para Windows.

[🌐 Landing Page Oficial](https://canetanatela.otgan.com/) • [💻 Repositório do Código Fonte](https://github.com/AnalistaOtgan/CanetaNaTela) • [📦 Baixar Último Release](https://github.com/AnalistaOtgan/CanetaRelease/releases/latest)

</div>

---

## 📦 Downloads — Versão 0.1.0 (Windows x64)

Todos os pacotes são gerados diretamente do código-fonte oficial em Rust/Tauri com máxima otimização e consumo mínimo de memória (~38 MB em repouso).

| Pacote | Arquivo | Tamanho | Descrição | Download |
| :--- | :--- | :---: | :--- | :---: |
| **Instalador Oficial** | `CanetaNaTela-Setup-v0.1.0.exe` | **~1.77 MB** | Instalador padrão NSIS com atalhos no Menu Iniciar e suporte a desinstalação | [Baixar](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.0/CanetaNaTela-Setup-v0.1.0.exe) |
| **Pacote Corporativo** | `CanetaNaTela-v0.1.0.msi` | **~2.54 MB** | Pacote Windows Installer (MSI) para implantação em rede (GPO / Intune) | [Baixar](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.0/CanetaNaTela-v0.1.0.msi) |
| **Versão Portátil** | `CanetaNaTela-Portable-v0.1.0.exe` | **~5.25 MB** | Executável standalone independente. Não requer instalação nem privilégios de administrador | [Baixar](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.0/CanetaNaTela-Portable-v0.1.0.exe) |

---

## 🔒 Integridade dos Arquivos (SHA-256)

Para verificar a integridade e autenticidade dos arquivos baixados no Windows via PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 <caminho-do-arquivo>
```

| Arquivo | Hash SHA-256 |
| :--- | :--- |
| `CanetaNaTela-Setup-v0.1.0.exe` | `24477FBD469C96F05D8585FA28460B4D66C60F8CB24A78ACF3BEF2B044A289AE` |
| `CanetaNaTela-v0.1.0.msi` | `81F91ACA69EEBFD0717061F174D98F6C2D667F077D85A2CC1505E83DA3C325A7` |
| `CanetaNaTela-Portable-v0.1.0.exe` | `0CD2A1746920467BF676DCA9843879E02875D0BD6CC52529930CE44C3F6D276F` |

---

## ⚙️ Requisitos do Sistema

- **Sistema Operacional:** Windows 10 (versão 1809+) ou Windows 11 (64-bit).
- **Runtime:** Microsoft Edge WebView2 (pré-instalado no Windows 10/11).
- **Hardware:** Qualquer processador x86_64 moderno, 2 GB de memória RAM livre.
- **Modo Multi-Monitor:** Suporte nativo completo a resoluções mistas e múltiplos monitores simultâneos.

---

<div align="center">

Desenvolvido por **Otgan Labs** • Todos os direitos reservados.

</div>
