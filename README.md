# Projeto AfroEmpodera

## Descrição
Projeto social voltado ao empoderamento afro, com back-end em Java orientado a objetos e front-end estático em HTML/CSS. A proposta está alinhada ao ODS 10 - Redução das Desigualdades, buscando valorizar profissionais negros e dar visibilidade social.

---

## Estrutura do projeto

```
afroempodera-final/
├── backend-console/       # Código Java para CRUD no console, conectado ao MySQL
├── frontend-site/         # Site estático representando a proposta social
└── README.md              # Instruções do projeto
```

---

## Back-end

- Linguagem: Java
- Funcionalidades: CRUD completo para entidades Usuário e Serviço
- Interface: Menu via console para navegação e operações CRUD
- Banco de dados: MySQL (relacional)
- Orientação a objetos aplicada

### Como executar o back-end

1. Configure o banco de dados MySQL conforme o script em `backend-console/scripts/`
2. Compile os arquivos Java:

```bash
cd backend-console
javac *.java
```

3. Execute o programa:

```bash
java Menu
```

---

## Front-end

- Site estático com HTML e CSS
- Inclusão de logo e visual com cores preto e amarelo
- Páginas: index, usuários, serviços, sobre

### Como testar o front-end

1. Abra a pasta `frontend-site`
2. Dê duplo clique em `index.html` ou use Live Server no VS Code

---

## Participante

- Priscila da Silva Domingos

---

## Observações

Projeto ainda não está integrado, mas todas as partes estão funcionando separadamente.
