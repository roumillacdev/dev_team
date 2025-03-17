# Dev Team 

## Visão Geral
Dev Team é uma aplicação React projetada para otimizar o gerenciamento de equipes de desenvolvimento. Ela fornece uma maneira eficiente de organizar membros da equipe, visualizar a estrutura da equipe e facilitar a colaboração entre diferentes departamentos.

## Funcionalidades
- **Organização de Equipes**: Categorize membros da equipe por departamento ou especialização
- **Cards de Membros**: Crie cartões visuais para cada membro da equipe com suas informações
- **Visualização de Departamentos**: Veja claramente como sua equipe está distribuída entre departamentos
- **Design Responsivo**: Funcional em vários tamanhos de tela e dispositivos

## Tecnologias Utilizadas
- **Frontend**: React.js, CSS
- **Gerenciamento de Estado**: React Hooks (useState)
- **Implantação**: Processo de build padrão do React

## Estrutura
A aplicação é estruturada com componentes modulares:
- **Banner**: Componente de banner do cabeçalho
- **Formulário**: Componente para envio de novos dados de membros da equipe
- **Times**: Seções organizadas por departamento
- **Cards de Membros**: Cartões individuais exibindo informações de membros da equipe

## Como Começar

### Pré-requisitos
- Node.js (v14.0.0 ou mais recente)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/SeuUsuario/dev_team.git
cd dev_team
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm start
```

4. Abra seu navegador e acesse:
```
http://localhost:3000
```

## Uso
1. Preencha o formulário com informações do membro da equipe:
   - Nome
   - Cargo/Posição
   - URL da imagem (opcional)
   - Departamento/Time

2. Clique em "Criar Card" para adicionar o membro da equipe ao seu respectivo departamento

3. Visualize a organização da equipe rolando pelas diferentes seções de departamentos

## Categorias de Times Disponíveis
- Front-End
- Data Science
- DevOps
- UX e Design
- Mobile
- Inovação e Gestão
- Programação

## Estrutura do Projeto
```
├── public/
│   ├── Imagens/
│   │   └── banner.png
│   └── index.html
└── src/
    ├── Componentes/
    │   ├── Banner/
    │   ├── Botao/
    │   ├── CampoTexto/
    │   ├── Colaborador/
    │   ├── Formulario/
    │   ├── ListaSuspensa/
    │   └── Time/
    ├── App.js
    └── index.js
```

## Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para enviar um Pull Request.

1. Faça um fork do repositório
2. Crie sua branch de feature (`git checkout -b feature/recurso-incrivel`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona algum recurso incrível'`)
4. Faça push para a branch (`git push origin feature/recurso-incrivel`)
5. Abra um Pull Request

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.

## Agradecimentos
- Criado por Diogo Roumillac
- Alura
