# IdleHub — Atualizações oficiais

Este repositório contém **apenas instaladores e arquivos de atualização** do IdleHub para Windows.

> **Status atual:** canal de distribuição em preparação. Ainda **não existe uma versão pública homologada** para instalar por aqui.

O código-fonte e o desenvolvimento são mantidos em um repositório separado e privado. Não publique aqui arquivos de sessão, cookies, preferências pessoais, senhas, tokens, código-fonte ou logs contendo dados privados.

## Como serão distribuídas as atualizações

Uma atualização aprovada será disponibilizada na seção [Releases](https://github.com/CaduCalegari/IdleHub-Releases/releases), com:
- `IdleHub-vX.Y.Z-Setup.exe` (instalador NSIS Windows x64).
- `latest.yml` (metadados de versão e integridade para o atualizador integrado).
- Arquivo `.blockmap`, quando gerado, para downloads diferenciais.
- Notas da versão descrevendo correções, mudanças e requisitos.

**Não publique uma Release como “Latest” antes de incluir todos os arquivos e testar a instalação.** Configure-a inicialmente como *Draft* até que seja aprovada.

## Segurança
- Distribuir apenas builds revisados e validados, preferencialmente assinados digitalmente.
- Nunca embutir credenciais GitHub no aplicativo.
- Confirmar a preservação dos dados do usuário antes de aprovar uma atualização.
- O usuário deverá confirmar a instalação quando estiver pronto para interromper o jogo.

O projeto está em desenvolvimento. Nenhum download presente aqui deve ser tratado como oficial enquanto não existir uma release aprovada.
