<div align="center">

  <img src="assets/icon.png" width="80" height="80" alt="CanetaNaTela Logo" />

  # CanetaNaTela — Distribuição Oficial de Executáveis

  **Repositório oficial de distribuição dos binários compilados do CanetaNaTela.**  
  Utilitário nativo de anotação vetorial sobreposta, apresentação e gravação de tela para Windows.

  **[canetanatela.otgan.com](https://canetanatela.otgan.com/)**

  [![Website](https://img.shields.io/badge/Website-canetanatela.otgan.com-009e95?logo=googlechrome&logoColor=white)](https://canetanatela.otgan.com/)
  [![Versão](https://img.shields.io/badge/Vers%C3%A3o-v0.1.2-0d9488?style=flat)](https://github.com/AnalistaOtgan/CanetaRelease/releases)
  [![Plataforma](https://img.shields.io/badge/Plataforma-Windows_x64-0284c7?logo=windows&logoColor=white)](https://github.com/AnalistaOtgan/CanetaRelease/releases)
  [![Código Fonte](https://img.shields.io/badge/Reposit%C3%B3rio-CanetaNaTela-6366f1?logo=github&logoColor=white)](https://github.com/AnalistaOtgan/CanetaNaTela)
  [![Otgan Labs](https://img.shields.io/badge/Desenvolvedor-Otgan%20Labs-009e95)](https://otgan.com)

</div>

---

## <img src="assets/icons/download.svg" width="18" height="18" valign="middle" /> Downloads — Versão 0.1.0 (Windows x64)

Todos os pacotes são gerados diretamente do código-fonte oficial em Rust/Tauri com máxima otimização e consumo mínimo de memória (~38 MB em repouso).

| Pacote | Arquivo | Tamanho | Descrição | Download |
| :--- | :--- | :---: | :--- | :---: |
| **Instalador Oficial** | `CanetaNaTela-Setup-v0.1.2.exe` | **~2.62 MB** | Instalador padrão NSIS com atalhos no Menu Iniciar e suporte a desinstalação | [Baixar .exe](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.2/CanetaNaTela-Setup-v0.1.2.exe) |
| **Pacote Corporativo** | `CanetaNaTela-v0.1.2.msi` | **~3.60 MB** | Pacote Windows Installer (MSI) para implantação em rede (GPO / Intune) | [Baixar .msi](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.2/CanetaNaTela-v0.1.2.msi) |
| **Versão Portátil** | `CanetaNaTela-Portable-v0.1.2.exe` | **~7.42 MB** | Executável standalone independente. Não requer instalação nem privilégios de administrador | [Baixar .exe](https://github.com/AnalistaOtgan/CanetaRelease/releases/download/v0.1.2/CanetaNaTela-Portable-v0.1.2.exe) |

---

## <img src="assets/icons/shield.svg" width="18" height="18" valign="middle" /> Integridade dos Arquivos (SHA-256)

Para verificar a integridade e autenticidade dos arquivos baixados no Windows via PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 <caminho-do-arquivo>
```

| Arquivo | Hash SHA-256 |
| :--- | :--- |
| `CanetaNaTela-Setup-v0.1.2.exe` | `3E4D8B5B25DB760C3254F8EECE0FE14D9763B12405C55CAEAA4B21EEB54741C4` |
| `CanetaNaTela-v0.1.2.msi` | `DA5412E7C2C56F256CE0858E6ED785BD0B3B77170219B502E3424824E0C7E7F4` |
| `CanetaNaTela-Portable-v0.1.2.exe` | `2417D6C2AD55474D02362528E4094C21CCED271B51CE810681D5B6398C9E6BFC` |

---

## <img src="assets/icons/cpu.svg" width="18" height="18" valign="middle" /> Requisitos do Sistema

- **Sistema Operacional:** Windows 10 (versão 1809+) ou Windows 11 (64-bit).
- **Runtime:** Microsoft Edge WebView2 (pré-instalado no Windows 10/11).
- **Hardware:** Qualquer processador x86_64 moderno, 2 GB de memória RAM livre.
- **Modo Multi-Monitor:** Suporte nativo completo a resoluções mistas e múltiplos monitores simultâneos.

---

<div align="center">

Desenvolvido por **Otgan Labs** • Todos os direitos reservados.

</div>
