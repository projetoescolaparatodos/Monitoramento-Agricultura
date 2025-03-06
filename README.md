# Monitoramento-Agricultura
# Sistema de Transparência Agrícola - SEMAPA

![Banner do Projeto](https://via.placeholder.com/1200x400?text=Sistema+de+Transpar%C3%AAncia+Agr%C3%ADcola)

## 📌 Sobre o Projeto
Este é um sistema de transparência para a Secretaria de Saúde, focado no **monitoramento manual de tratores agrícolas**. O sistema permite cadastrar e acompanhar atividades agrícolas realizadas, proporcionando maior controle e transparência sobre os serviços prestados.

## ✨ Funcionalidades

✅ **Painel Administrativo**: Cadastro e atualização de tratores e atividades, com relatórios sobre tempo de uso, local e área trabalhada (m² ou km²).
✅ **Mapa Interativo**: Visualização manual da localização e status dos tratores.
✅ **Feed de Atividades**: Estilo Instagram, exibindo fotos e vídeos das atividades.
✅ **Painel de Transparência**: Exibição de estatísticas mensais sobre o uso dos tratores.

## 🛠 Tecnologias Utilizadas

O sistema foi desenvolvido utilizando as seguintes tecnologias:

### **Frontend:**
- ⚛️ **React.js** (Vite, Tailwind CSS, Material-UI)
- 🌍 **Google Maps JavaScript API** (para renderização do mapa interativo)
- 🎨 **ShadCN e Lucide Icons** (para UI e ícones visuais)

### **Backend:**
- 🔥 **Firebase** (Firestore para banco de dados e Storage para armazenamento de imagens/vídeos)

### **Deploy:**
- 🚀 **Netlify ou Vercel** (para hospedagem do frontend)

## 📂 Estrutura do Projeto
```plaintext
📦 sistema-transparencia-agricola
 ┣ 📂 public            # Arquivos estáticos (imagens, favicon, etc.)
 ┣ 📂 src               # Código-fonte principal
 ┃ ┣ 📂 components      # Componentes reutilizáveis
 ┃ ┣ 📂 pages           # Páginas principais do sistema
 ┃ ┣ 📂 services        # Comunicação com Firebase e Google Maps API
 ┃ ┣ 📂 styles          # Estilos globais (Tailwind CSS)
 ┃ ┗ 📂 utils           # Funções auxiliares
 ┣ 📜 .gitignore        # Arquivos ignorados pelo Git
 ┣ 📜 package.json      # Dependências e scripts
 ┣ 📜 vite.config.js    # Configuração do Vite
 ┗ 📜 README.md         # Documentação do projeto
```

## 🚀 Como Executar o Projeto
### **1️⃣ Clone o repositório**
```sh
git clone https://github.com/SEU-USUARIO/sistema-transparencia-agricola.git
cd sistema-transparencia-agricola
```

### **2️⃣ Instale as dependências**
```sh
yarn install  # ou npm install
```

### **3️⃣ Configure as credenciais do Firebase**
Crie um arquivo `.env` na raiz do projeto e adicione as configurações do Firebase:
```env
VITE_FIREBASE_API_KEY=xxxxxx
VITE_FIREBASE_AUTH_DOMAIN=xxxxxx
VITE_FIREBASE_PROJECT_ID=xxxxxx
VITE_FIREBASE_STORAGE_BUCKET=xxxxxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxxxxx
VITE_FIREBASE_APP_ID=xxxxxx
```

### **4️⃣ Execute o projeto localmente**
```sh
yarn dev  # ou npm run dev
```

O sistema será iniciado em `http://localhost:5173`.

## 📢 Contribuição
Se quiser contribuir, siga estes passos:
1. **Fork** o repositório.
2. Crie uma **branch** para sua feature (`git checkout -b minha-feature`).
3. Faça um **commit** das mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça um **push** para a branch (`git push origin minha-feature`).
5. Crie um **Pull Request**.

## 📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

🚜 **Sistema de Transparência Agrícola - Desenvolvido por Henrique**
