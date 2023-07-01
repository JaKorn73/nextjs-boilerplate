# Tour de App - Next.js boiler plate

Šablona pro vývoj aplikace pro Tour de App společně s vytvořením a nahráním výstupu [Next.js](https://nextjs.org/)

## Lokální spuštění

#### Windows
- Nainstalovaný [WSL2 (Windows Subsystem for Linux)](https://learn.microsoft.com/en-us/windows/wsl/install)
- Nainstalovaný a běžící [Docker](https://www.docker.com/)

#### Linux / MacOS
- Nainstalovaný a běžící [Docker](https://www.docker.com/)

```
docker build . -t tda-nextjs
docker run -p 8080:80 -v "$(pwd)":/app tda-nextjs
```
Aplikace bude následně přístupná na `http://localhost:8080`

## Odevzdání
