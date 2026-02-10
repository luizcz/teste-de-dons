# 🌟 Teste de Dons Espirituais

Uma aplicação web moderna e interativa para descobrir seus dons espirituais através de um questionário de 68 perguntas baseado no teste desenvolvido pelo Instituto dos Ministérios da Igreja da Universidade Andrews.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61dafb.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## ✨ Características

- 📱 **Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Design Moderno** - Interface elegante com animações suaves
- ⚡ **Rápido** - Aplicação de página única sem necessidade de servidor
- 📊 **Resultados Detalhados** - Visualização completa com gráficos de barras
- 🔄 **Refazer Teste** - Possibilidade de refazer o teste a qualquer momento
- 🎯 **Destaque Automático** - Identifica automaticamente seus principais dons (≥12 pontos)

## 🎁 Dons Espirituais Avaliados

O teste avalia 17 dons espirituais:

1. **Discernimento** - Capacidade de perceber motivações verdadeiras
2. **Encorajamento** - Dom de consolar e animar pessoas
3. **Evangelização** - Habilidade de levar pessoas a Cristo
4. **Fé** - Confiança inabalável na providência divina
5. **Liberalidade** - Generosidade em dar aos outros
6. **Hospitalidade** - Acolhimento caloroso de pessoas
7. **Conhecimento** - Compreensão profunda das Escrituras
8. **Direção** - Liderança e coordenação de grupos
9. **Misericórdia** - Compaixão prática pelos necessitados
10. **Apostolado** - Ministério missionário transcultural
11. **Organização** - Habilidade de estruturar e administrar
12. **Intercessão** - Dom de oração fervorosa e específica
13. **Pregação** - Comunicação eficaz da Palavra
14. **Serviço** - Ajuda prática na comunidade
15. **Pastorado** - Cuidado espiritual dos membros
16. **Ensino** - Explicação clara de verdades bíblicas
17. **Sabedoria** - Aplicação prática de princípios divinos

## 🚀 Como Usar

### Opção 1: Acessar Online (GitHub Pages)

Acesse diretamente: `https://seu-usuario.github.io/nome-do-repo`

### Opção 2: Executar Localmente

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/teste-dons-espirituais.git
   cd teste-dons-espirituais
   ```

2. **Abra o arquivo HTML**
   - Simplesmente abra `index.html` no seu navegador
   - Ou use um servidor local:
     ```bash
     # Com Python 3
     python -m http.server 8000
     
     # Com Node.js
     npx serve
     ```

3. **Acesse no navegador**
   - Abra `http://localhost:8000` (se usando servidor local)
   - Ou simplesmente clique duas vezes no arquivo `index.html`

## 📦 Hospedagem no GitHub Pages

1. **Faça fork ou clone este repositório**

2. **Renomeie o arquivo**
   - Renomeie `spiritual-gifts-test.html` para `index.html`

3. **Faça commit e push**
   ```bash
   git add .
   git commit -m "Deploy teste de dons espirituais"
   git push origin main
   ```

4. **Ative GitHub Pages**
   - Vá para Settings > Pages
   - Em "Source", selecione a branch `main`
   - Clique em "Save"
   - Seu site estará disponível em alguns minutos!

## 🎯 Como Funciona

### Respondendo ao Teste

1. Leia cada uma das 68 afirmações
2. Avalie com sinceridade sua realidade atual:
   - **1** = Nunca
   - **2** = Raramente
   - **3** = Frequentemente
   - **4** = Quase Sempre
3. Acompanhe seu progresso na barra superior
4. Clique em "Ver Resultados" quando terminar

### Interpretando os Resultados

- **12-16 pontos**: Don forte - área de ministério natural
- **8-11 pontos**: Don moderado - área a desenvolver
- **4-7 pontos**: Don básico - possível área de crescimento
- **0-3 pontos**: Don não destacado atualmente

Os resultados mostram:
- 🏆 **Principais Dons**: Destacados no topo (≥12 pontos)
- 📊 **Todos os Dons**: Lista completa com pontuação e gráfico visual
- 🔢 **Questões**: Números das perguntas que compõem cada dom

## 🛠️ Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript para interface
- **HTML5** - Estrutura da página
- **CSS3** - Estilização moderna com animações
- **Google Fonts** - Tipografia premium (Crimson Pro + DM Sans)

## 📱 Compatibilidade

- ✅ Chrome/Edge (últimas versões)
- ✅ Firefox (últimas versões)
- ✅ Safari (últimas versões)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Personalização

### Alterar Cores

Edite as variáveis CSS no início do arquivo:

```css
:root {
    --primary: #1a4d2e;        /* Cor principal */
    --primary-light: #2d6a4f;  /* Cor principal clara */
    --accent: #d4a373;          /* Cor de destaque */
    --bg: #faf8f5;              /* Cor de fundo */
    --text: #2c3e50;            /* Cor do texto */
}
```

### Alterar Fontes

Substitua os links do Google Fonts e as referências `font-family` no CSS.

## 📄 Créditos

- **Teste Original**: Instituto dos Ministérios da Igreja - Universidade Andrews, Berrien Springs, Michigan, EUA
- **Desenvolvimento Web**: Versão digital interativa
- **Design**: Interface moderna e responsiva

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 💡 Sugestões de Melhoria

Ideias para futuras versões:

- [ ] Exportar resultados em PDF
- [ ] Compartilhar resultados nas redes sociais
- [ ] Salvar progresso no localStorage
- [ ] Descrição detalhada de cada dom
- [ ] Sugestões de ministérios por dom
- [ ] Modo escuro/claro
- [ ] Múltiplos idiomas

## 📧 Contato

Para dúvidas, sugestões ou feedback, abra uma [issue](https://github.com/seu-usuario/teste-dons-espirituais/issues) no GitHub.

---

**Versão Bíblica de Referência**: 

> "Então ouvi a voz do Senhor, conclamando: Quem enviarei? Quem irá por nós? E eu respondi: Eis-me aqui. Envia-me!"  
> — Isaías 6:8

Desenvolvido com ❤️ para ajudar pessoas a descobrirem seus dons espirituais e servirem melhor no Reino de Deus.
