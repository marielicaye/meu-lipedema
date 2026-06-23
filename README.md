# Meu Lipedema — PWA

O aplicativo pode ser instalado no Android e no iPhone e guarda os registros localmente no navegador.

## Teste no computador

Use um servidor local: os recursos de instalação e cache offline não funcionam ao abrir `index.html` diretamente.

```powershell
npx serve .
```

Abra o endereço mostrado, normalmente `http://localhost:3000`.

## Instalação no celular

Publique esta pasta em um endereço HTTPS e abra-o no celular.

- **Android (Chrome):** menu ⋮ → **Instalar aplicativo** ou **Adicionar à tela inicial**.
- **iPhone (Safari):** Compartilhar → **Adicionar à Tela de Início**.

Após a primeira abertura, o app funciona offline. Os dados não são sincronizados entre dispositivos.
