
![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# Nearby

O Nearby é um aplicativo móvel desenvolvido com React Native que utiliza uma API externa para fornecer informações sobre lojas próximas e seus cupons de desconto.

## Instalação 

Certifique-se de ter o Node.js e o Expo CLI instalados. Clone o repositório e instale as dependências:
```bash
git clone https://github.com/Pin4s/Nearby
cd Nearby  
npm install  
```

## Configurações
As configurações da API, como URL base e IP, devem ser ajustadas no arquivo api.ts, localizado na pasta services.

### Exemplo:
```bash
import axios from "axios"

export const api = axios.create({
  baseURL: "http://192.168.1.1:3333",
  timeout: 700,
})

```
Certifique-se de substituir baseURL pela URL ou IP correto para acessar a API.

## Uso
Inicie o projeto com 
```bash
npx expo start
```

Escaneie o QR Code com o aplicativo Expo Go no Android, escaneie com a câmera do dispositivo no IOS ou utilize um emulador para rodar o aplicativo.


![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# Nearby

O Nearby é um aplicativo móvel desenvolvido com React Native que utiliza uma API externa para fornecer informações sobre lojas próximas e seus cupons de desconto.

## Instalação 

Certifique-se de ter o Node.js e o Expo CLI instalados. Clone o repositório e instale as dependências:
```bash
git clone https://github.com/Pin4s/Nearby
cd Nearby  
npm install  
```

## Configurações
As configurações da API, como URL base e IP, devem ser ajustadas no arquivo api.ts, localizado na pasta services.

### Exemplo:
```bash
import axios from "axios"

export const api = axios.create({
  baseURL: "http://192.168.1.1:3333",
  timeout: 700,
})

```
Certifique-se de substituir baseURL pela URL ou IP correto para acessar a API.

## Uso
Inicie o projeto com 
```bash
npx expo start
```

Escaneie o QR Code com o aplicativo Expo Go no seu dispositivo ou utilize um emulador para rodar o aplicativo.

![Primeira tela do Nearby](https://github.com/user-attachments/assets/2c13b4c3-61fb-4252-b0e2-895a48594a5c)
![Segunda tela do Nearby](https://github.com/user-attachments/assets/ef17c0fe-b1fe-4f7f-bb4b-9d56968fe4ff)

![Terceira tela do Nearby](https://github.com/user-attachments/assets/ec237a9b-c516-4239-af4f-9636797efa45)
![Quarta tela do Nearby](https://github.com/user-attachments/assets/470f79f0-2743-493f-bc57-850709ff1984)
![Quinta tela do Nearby](https://github.com/user-attachments/assets/cf67aa57-0617-4c2c-ada7-7345b0c21c38)


