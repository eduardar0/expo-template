# 🏗️ Estrutura de Pastas - Template Expo

Este repositório serve como **template base** para projetos criados no treinamento de Expo.

Aqui você encontra a estrutura inicial com pastas organizadas e explicações de para que serve cada uma.

---

## 📂 Estrutura

```

├── app/
    │ ├── screens/ # Telas do app (Home, Login, etc.)
│ ├── components/ # Componentes reutilizáveis (Botões, Cards, etc.)

│ ├── navigation/ # Configuração de rotas e navegação

│ ├── hooks/ # Hooks personalizados

│ ├── services/ # Chamadas de API e integração com backend

│ ├── store/ # Estado global (Zustand, Redux ou Context API)

│ ├── utils/ # Funções auxiliares

│ ├── styles/ # Temas e estilos globais (cores, fontes, espaçamentos)

    │ └── ...

├── assets/
    │ ├── images/ # Imagens usadas no app
    │ ├── icons/ # Ícones
    │ └── fonts/ # Fontes personalizadas
    ├── app.json # Configurações do Expo
    ├── package.json # Dependências e scripts
    └── README.md # Este arquivo

```

---

## 📜 Descrição de cada pasta/arquivo

- **app/screens/** → Telas principais do app, onde a interface do usuário é criada.  

- **app/components/** → Componentes reutilizáveis, como botões, cards, inputs.  

- **app/navigation/** → Configuração das rotas e navegação entre telas.  

- **app/hooks/** → Hooks customizados para lógica reutilizável.  

- **app/services/** → Serviços de comunicação com APIs externas.  

- **app/store/** → Estado global da aplicação (pode ser Zustand, Redux ou Context API).  

- **app/utils/** → Funções utilitárias e helpers para facilitar o código.  

- **app/styles/** → Temas, cores, fontes e espaçamentos padronizados.  

- **assets/images/** → Imagens usadas na aplicação.  

- **assets/icons/** → Ícones da interface. 

- **assets/fonts/** → Fontes personalizadas.


---

## 🚀 Como usar este template

### 1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
```
### 2 Instale as dependências:

```
yarn install
# ou npm install
```
### 3. Rode o app

```
yarn start
# ou npm start
```
