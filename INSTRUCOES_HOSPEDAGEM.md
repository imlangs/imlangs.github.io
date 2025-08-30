# Instruções para Hospedagem do Portfólio

## 🌐 Opções de Hospedagem Gratuita

### 1. GitHub Pages (Recomendado)

**Passo a passo:**

1. **Criar conta no GitHub:**
   - Acesse: https://github.com
   - Crie uma conta usando seu nome como parte do username
   - Exemplo: `joaosilva2024` ou `maria-santos-dev`

2. **Criar repositório:**
   - Clique em "New repository"
   - Nome: `portfolio` ou `meu-portfolio`
   - Marque como "Public"
   - Adicione README (opcional)

3. **Upload dos arquivos:**
   - Clique em "uploading an existing file"
   - Arraste todos os arquivos do projeto
   - Commit com mensagem: "Adicionar portfólio pessoal"

4. **Ativar GitHub Pages:**
   - Vá em Settings > Pages
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
   - Clique em "Save"

5. **Acessar o site:**
   - URL: `https://seuusername.github.io/portfolio/`
   - Aguarde alguns minutos para ativação

### 2. Netlify

**Passo a passo:**

1. **Criar conta:**
   - Acesse: https://www.netlify.com
   - Cadastre-se com seu nome

2. **Deploy manual:**
   - Clique em "Sites" > "Add new site" > "Deploy manually"
   - Arraste a pasta do projeto
   - Aguarde o deploy

3. **Personalizar domínio:**
   - Site settings > Change site name
   - Use seu nome: `joao-silva-portfolio`

### 3. Vercel

**Passo a passo:**

1. **Criar conta:**
   - Acesse: https://vercel.com
   - Cadastre-se com GitHub (recomendado)

2. **Importar projeto:**
   - "Add New" > "Project"
   - Conecte seu repositório GitHub
   - Deploy automático

## 📋 Checklist Pré-Hospedagem

### Preparação dos Arquivos

- [ ] Todos os arquivos HTML estão funcionando
- [ ] Arquivo CSS está linkado corretamente
- [ ] Links de navegação estão funcionando
- [ ] Formulário de contato está validando
- [ ] Não há erros no console do navegador

### Personalização Obrigatória

- [ ] Substituir `[Seu Nome]` pelo nome real
- [ ] Atualizar informações de contato
- [ ] Adicionar foto de perfil (opcional)
- [ ] Revisar todos os textos e informações
- [ ] Testar em diferentes navegadores

### Teste Final

- [ ] Abrir `index.html` no navegador
- [ ] Navegar por todas as páginas
- [ ] Testar formulário de contato
- [ ] Verificar responsividade (F12 > Device Toggle)
- [ ] Confirmar que não há links quebrados

## 🔧 Solução de Problemas Comuns

### Problema: CSS não carrega
**Solução:** Verificar se o caminho no HTML está correto:
```html
<link rel="stylesheet" href="style.css">
```

### Problema: Navegação não funciona
**Solução:** Verificar se os nomes dos arquivos estão corretos:
- `index.html`
- `formacao.html`
- `portfolio.html`
- `contato.html`

### Problema: Site não abre no GitHub Pages
**Solução:**
1. Verificar se o repositório é público
2. Confirmar se GitHub Pages está ativado
3. Aguardar até 10 minutos para propagação
4. Verificar se o arquivo `index.html` está na raiz

## 📝 Dicas Importantes

### Para o Trabalho Acadêmico

1. **Teste o link antes de entregar:**
   - Abra em navegador anônimo
   - Teste em dispositivo móvel
   - Verifique se todas as páginas carregam

2. **Documentação:**
   - Anote a URL final do site
   - Tire screenshots de cada página
   - Mantenha backup dos arquivos

3. **Nome do domínio:**
   - Use seu nome conforme orientação
   - Exemplo: `joao-silva-portfolio.netlify.app`
   - Ou: `joaosilva2024.github.io/portfolio`

### Manutenção Futura

- Mantenha o repositório atualizado
- Adicione novos projetos regularmente
- Atualize informações de contato
- Monitore se o site continua online

## 🆘 Suporte

Se encontrar problemas:

1. **GitHub Pages:** https://docs.github.com/pages
2. **Netlify:** https://docs.netlify.com
3. **Vercel:** https://vercel.com/docs

**Lembre-se:** Sempre teste o link final antes da entrega do trabalho!

