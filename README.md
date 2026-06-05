# NekoGPT Engine Mate Bridge Plugin

Plugin opcional para conectar o NekoGPT ao Engine Mate como avatar externo.

O NekoGPT continua funcionando sem este plugin. A bridge usa apenas `localhost`, token de pareamento local e WebSocket.

## Como instalar no NekoGPT

1. Abra o NekoGPT.
2. Entre em `Configuracoes > Plugins`.
3. Cole este repositorio:

```text
https://github.com/inobushi3/nekogpt-engine-mate-bridge-plugin
```

4. Clique em `Adicionar`.
5. Clique em `Ativar` no plugin `Engine Mate Avatar Bridge`.
6. Entre em `Integracoes > Avatar Externo` para configurar porta, token e testes.

## Como instalar no Engine Mate

1. Baixe ou abra o instalador em `dist/NekoGPTBridge-Setup-1.0.1.exe`.
2. Execute o instalador.
3. Selecione a pasta raiz do Engine Mate, a mesma pasta onde fica o executavel do Engine Mate.
4. Abra o Engine Mate.
5. Abra a janela `NekoGPT Bridge`.
6. Cole o token exibido no NekoGPT.
7. Clique em `Conectar`.

## O que o plugin faz

- Mostra status conectado/desconectado no NekoGPT.
- Envia lip sync visual durante TTS.
- Envia legenda para aparecer acima da cabeca do avatar no Engine Mate.
- Envia eventos de pizza, pirulito, martelo e perfume.
- Envia evento de danca quando a jukebox toca.
- Recebe eventos do Engine Mate, como pat pat e toque em area sensivel, para o chat reagir pela persona.

## O que ele nao faz

- Nao substitui o Live2D/Live3D atual do NekoGPT.
- Nao inicia o Engine Mate automaticamente.
- Nao abre porta externa na rede.
- Nao executa codigo remoto dentro do NekoGPT.

## Checksums

```text
NekoGPTBridge-Setup-1.0.1.exe
SHA256: 7246EBEB9FB5F70CCCE1DFD4B4F4B80CD56AC3466F70C591398973DA78E60951
```
