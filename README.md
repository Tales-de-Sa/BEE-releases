# BEE — Releases

Este repositório hospeda **somente os instaladores compilados** (`.exe` para
Windows, `.deb` para Linux/Debian/Ubuntu) de cada versão publicada do BEE,
sistema de auxílio administrativo fiscal desenvolvido pela THARK TECNOLOGIA.

## Baixar o BEE

Acesse a [versão mais recente](https://github.com/Tales-de-Sa/BEE-releases/releases/latest)
e abra a seção **Assets** para escolher o instalador:

| Sistema | Arquivo |
| --- | --- |
| Windows | `BEE-Setup-VERSAO.exe` |
| Debian/Ubuntu, arquitetura amd64 (x86-64) | `bee_VERSAO_amd64.deb` |

Substitua `VERSAO` pelo número da publicação escolhida. Os arquivos **Source code
(zip)** e **Source code (tar.gz)** gerados pelo GitHub não são instaladores do BEE.

No Windows, abra o instalador `.exe` baixado e siga as instruções. No Debian/Ubuntu,
abra um terminal na pasta do download e instale o pacote local:

```bash
sudo apt install ./NOME_DO_ARQUIVO.deb
```

Substitua `NOME_DO_ARQUIVO.deb` pelo nome exato do pacote baixado. O comando solicita
permissão de administrador e pode instalar dependências.

Para consultar versões anteriores e suas notas, veja o
[histórico de releases](https://github.com/Tales-de-Sa/BEE-releases/releases).
