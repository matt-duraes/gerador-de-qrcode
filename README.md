# Gerador de QR Code

Um gerador de códigos QR moderno e responsivo construído com React e Vite. Permite gerar códigos QR para URLs, texto e informações de contato.

## 🚀 Funcionalidades

- **URLs**: Gere códigos QR para sites e links
- **Texto**: Converta qualquer texto em código QR
- **Contatos**: Crie códigos QR com informações de contato (vCard)
- **Download**: Baixe os códigos QR gerados como imagem PNG
- **Copiar dados**: Copie os dados do código QR para a área de transferência
- **Responsivo**: Interface adaptável para desktop e mobile
- **Múltiplos idiomas**: Suporte para português e inglês

## 🛠️ Tecnologias Utilizadas

- **React 18** - Biblioteca para interface do usuário
- **Vite** - Ferramenta de build rápida
- **Tailwind CSS** - Framework CSS utilitário
- **Lucide React** - Ícones modernos
- **QRious** - Biblioteca para geração de códigos QR

## 📦 Instalação e Uso

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

### Passos para execução

1. **Instale as dependências:**
   ```bash
   npm install
   ```

2. **Execute o projeto em modo de desenvolvimento:**
   ```bash
   npm run dev
   ```

3. **Acesse o aplicativo:**
   Abra [http://localhost:3000](http://localhost:3000) no seu navegador

### Scripts disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera a versão de produção
- `npm run preview` - Visualiza a versão de produção
- `npm start` - Alias para `npm run dev`

## 🎯 Como usar

1. **Escolha o tipo de código QR:**
   - **URL**: Para links de sites
   - **Texto**: Para qualquer texto
   - **Contato**: Para informações de contato

2. **Preencha os campos:**
   - Digite as informações nos campos correspondentes
   - O código QR é gerado automaticamente em tempo real

3. **Baixe ou copie:**
   - Use o botão "Download" para salvar como imagem
   - Use "Copiar Dados" para copiar o conteúdo para a área de transferência

## 🌐 Recursos de Fallback

O aplicativo utiliza múltiplas APIs para garantir que os códigos QR sejam sempre gerados:

1. **QRious** (biblioteca principal)
2. **Google Charts API** (fallback)
3. **QR Server API** (fallback secundário)

## 📱 Responsividade

A interface foi desenvolvida para funcionar perfeitamente em:
- Desktop
- Tablets
- Smartphones

## 🔧 Personalização

O código está estruturado de forma modular, permitindo fácil customização:

- **Idiomas**: Adicione novos idiomas editando o objeto `TRANSLATIONS` em `src/App.jsx`
- **Estilos**: Modifique as classes Tailwind para personalizar a aparência
- **Funcionalidades**: Adicione novos tipos de códigos QR estendendo o componente

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abrir um Pull Request

## 📞 Suporte

Se você encontrar problemas ou tiver sugestões, por favor abra uma issue no repositório.

---

**Desenvolvido com ❤️ usando React e Vite**
# gerador-de-qrcode
