# Podcastr
Código construído por mim da aplicação Podcastr da Next Level Week 05.

## Design
O design da aplicação foi criado no Figma. Para acessar [clique aqui](https://www.figma.com/file/UwFEntsHpHYJlHNQAQr4gA/Podcastr/duplicate).

![Design](https://github.com/dhianapereira/podcastr/assets/40719464/6b6d6783-c814-4c8a-9045-adb6d8dd9784)

## Ambiente de Desenvolvimento
Para evitar problemas é legal que seu ambiente de desenvolvimento esteja com
as seguintes versões:

| Ferramenta | Versão         |
| ---------- | -------------- |
| Git        | A mais recente |
| NodeJS     | v18.17.1       |

## Guia de Instalação
> Com as ferramentas devidamente instaladas, execute os comandos abaixo

### **1. Clonar repositório**
```bash
git clone https://github.com/dhianapereira/podcastr.git
```

### **2. Entrar na pasta do projeto**
```bash
cd podcastr
```

### **3. Instalar as dependências**
```bash
npm install
```

### **4. Executar o servidor**
Esse servidor fake para fins de testes com a ajuda da lib [json-server](https://github.com/typicode/json-server). O arquivo json executado é [server.json](./server.json).

```bash
npm run server
```

### **5. Executar a aplicação**
```bash
npm run dev
```