# clvector — instalador do clvector local

O clvector local é a memória de uma IA no seu computador: um banco pequeno (`clvd`) que só atende este computador, e uma ferramenta (`clvmem`) que liga essa memória ao Claude Code, ao Codex e ao Claude Desktop.

Este repositório só guarda as **Releases**: os programas compilados, o `SHA256SUMS` e os instaladores de cada versão. O código-fonte não é público.

## Instalar (uma linha)

**Windows (PowerShell):**

```powershell
irm https://github.com/albertoohnuki/clvector-install/releases/latest/download/install.ps1 | iex
```

**Linux e macOS:**

```bash
curl -fsSL https://github.com/albertoohnuki/clvector-install/releases/latest/download/install.sh | bash
```

A mesma linha atualiza. O instalador baixa só os 3 arquivos do seu sistema (cerca de 17 MB), confere o sha256 de cada um contra o `SHA256SUMS` e, sem essa conferência, não instala. Os dados e as chaves ficam no seu computador.

Para uma IA instalar para você, entregue a ela o guia: [`INSTALL.md`](https://github.com/albertoohnuki/clvector-install/releases/latest/download/INSTALL.md).

## Ativação e espaço

Toda instalação se ativa uma vez, de graça: 500 MB, sem vencimento. Sem a ativação o clvector só lê e exporta, não grava. Se precisar de mais espaço, ele soma-se aos 500 MB e vale 12 meses.
