# 🧠 Projeto: Análise de Texto em Imagens com OCR

## 📌 Descrição do Projeto

Este projeto tem como objetivo realizar a **extração e análise de textos presentes em imagens**. A aplicação permite que imagens sejam processadas automaticamente, identificando e convertendo textos contidos nelas para formato editável. Isso é extremamente útil em contextos como digitalização de documentos, leitura de placas, análise de prints de telas, entre outros.

---

## 🖼️ Prints e Etapas do Processo

### 🔧 Etapa 1: Preparação do Ambiente

![Print do ambiente configurado](./prints/configuracao-ambiente.png)

O projeto começou com a preparação do ambiente de desenvolvimento. Foi necessário instalar as dependências da biblioteca OCR, configurar os scripts de leitura e preparar o pipeline de upload de imagens. As principais ferramentas utilizadas nesta etapa foram:

- [ ] VS Code
- [ ] Node.js / Python
- [ ] Tesseract OCR
- [ ] Git e GitHub para versionamento

---

### 📷 Etapa 2: Upload e Pré-processamento de Imagens

![Print do upload de imagem](./prints/upload-imagem.png)

A aplicação permite que o usuário faça o upload de imagens contendo textos. Antes da análise, as imagens passam por um processo de **pré-processamento**, como:

- Conversão para escala de cinza
- Ajuste de contraste e nitidez
- Redimensionamento e remoção de ruído

Esses ajustes são essenciais para garantir que o OCR consiga identificar corretamente os caracteres presentes na imagem.

---

### 🧪 Etapa 3: Extração e Análise de Texto

![alt text](image.png)
![alt text](image-1.png)

Com a imagem processada, O resultado é exibido em tempo real no sistema. Após a extração, é possível aplicar análises como:

- Detecção de palavras-chave
- Contagem de palavras e frequência
- Identificação de padrões (como e-mails, datas ou números)

Essas informações podem ser usadas em diversos contextos analíticos ou integradas a bancos de dados.

---

## 💡 Insights Aprendidos

Durante o projeto, tive aprendizados valiosos:

- **A qualidade da imagem influencia diretamente a eficiência do OCR**
- **Pré-processamento é mais importante do que parece**, pois imagens "limpas" trazem resultados muito mais precisos
- **Tesseract é uma ferramenta poderosa, mas requer ajustes finos nos parâmetros**
- Identifiquei que há **limitações com fontes manuscritas ou imagens muito distorcidas**
- Aprendi a **automatizar a leitura de múltiplas imagens**, tornando o processo escalável

---

## 🚀 Possibilidades Futuras

A partir deste projeto, várias ideias surgiram para evoluir ainda mais a solução:

- Integração com uma API REST para receber imagens via requisição
- Treinamento de modelos personalizados para tipos específicos de textos ou fontes
- Exportação dos textos extraídos em formatos como PDF ou Excel
- Adição de um painel com gráficos sobre os dados extraídos (por exemplo, análise de frequência de palavras)
- Deploy da aplicação em nuvem com interface web amigável

