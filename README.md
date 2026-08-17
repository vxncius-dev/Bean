# Bean

Bean é um aplicativo leve de compartilhamento de arquivos em rede local, desenvolvido para enviar arquivos entre dispositivos conectados à mesma rede. Quando é necessário acesso remoto, ele também pode criar um link público temporário e seguro utilizando o ngrok.

![Interface do Bean](https://github.com/user-attachments/assets/da013b36-526d-416f-ba67-75a74f8ec10d)

## Instalação

Baixe o instalador **`Bean-Setup-1.0.2.exe`** na [versão v1.0.2](https://github.com/vxncius-dev/Bean/releases/tag/v1.0.2) e execute-o para instalar o Bean. O instalador também está disponível no repositório no caminho `Releases/Bean 1.0.2/Bean-Setup-1.0.2.exe`.

Após instalar, abra o aplicativo e utilize o endereço ou o QR Code exibidos para se conectar a partir de outro dispositivo.

O aplicativo armazena os arquivos compartilhados localmente no computador hospedeiro. O authtoken do ngrok também é armazenado localmente, de forma criptografada, utilizando o Windows DPAPI.

## Acesso remoto

Abra as Configurações, cole seu authtoken do ngrok e inicie o túnel. O Bean atualizará o endereço e o QR Code exibidos para o link HTTPS gerado. Ao encerrar o túnel, o aplicativo retorna automaticamente ao endereço da rede local.

## Status

O APK para Android está em desenvolvimento e será disponibilizado em breve.

## Licença

O Bean é um software proprietário. Consulte [LICENSE](LICENSE.md) para os termos da licença e [TERMS](TERMS.md) para os Termos de Uso.
