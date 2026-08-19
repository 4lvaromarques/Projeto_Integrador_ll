# Projeto_Integrador_ll
Repositor para etapa l


#  Mural Virtual de Projetos de Informática
> **Projeto Piloto:** Colégio Técnico de Bom Jesus (CTBJ) / UFPI


##  Sobre o Projeto
O **Mural Virtual de Projetos** é uma plataforma web open-source desenvolvida exclusivamente para dar visibilidade aos trabalhos de software, sistemas e automação dos alunos do curso **Técnico em Informática do Colégio Técnico de Bom Jesus**. 

O grande diferencial deste ecossistema é a sua **arquitetura centralizada de portfólio**. O sistema foi projetado sob medida para as necessidades do CTBJ, permitindo que a coordenação de informática e os professores gerenciem o histórico de softwares produzidos nas salas de aula, feiras de tecnologia e em projetos determinados por professores.

---

##  Funcionalidades Principais

###  Para o Colégio Técnico de Bom Jesus (Mural Público)
*   **Feed de Projetos:** Visualização estilo "Pinterest" dos sistemas com capturas de tela, vídeos demonstrativos, resumos técnicos e links diretos para o código no GitHub.
*   **Filtros Avançados:** Busca de projetos por Eixo Tecnológico da Informática (Ex: Desenvolvimento Web, Programação, Sistemas Operacionais, Banco de Dados, Rede de Computadores) e Ano Letivo.
*   **Espaço Interativo:** Opção para a comunidade escolar deixar curtidas, comentários construtivos sobre a arquitetura do software e compartilhar os códigos.

###  Para a Gestão Interna (Apoio Pedagógico)
*   **Controle de Turmas e Alunos:** Gerenciamento centralizado de estudantes matriculados nos módulos técnicos de informática do CTBJ.
*   **Painel Administrativo do Curso:** Coordenadores e professores gerenciam os prazos de submissão de projetos, as categorias técnicas e os relatórios gerados.
*   **Painel Geral de Avaliação:** Uma página restrita para a banca examinadora do colégio atribuir notas e observações técnicas aos sistemas publicados.

---


##  Estrutura otimizada

O banco de dados utiliza uma estrutura otimizada para o colégio. Isso garante que as informações dos alunos do CTBJ fiquem consolidadas em uma base robusta, permitindo consultas rápidas e geração de relatórios de desempenho acadêmico em TI.

---



##  Estrutura de Pastas do Repositório

```text
├── .github/               # Workflows do GitHub Actions (CI/CD)
├── backend/               # Código do servidor, APIs e Regras de Negócio
│   ├── src/
│   │   ├── modules/       # Dividido por Cursos, Projetos de Software e Usuários
│   │   └── database/      # Migrations e Configuração do Banco
├── frontend/              # Interface do Usuário (Next.js/React)
│   ├── src/
│   │   ├── components/    # Cards de sistemas, Menus, Modais
│   │   ├── pages/         # Páginas do CTBJ e rotas dinâmicas de visualização
│   │   └── styles/        # Configurações do Tailwind
├── LICENSE                # Licença MIT
└── README.md              # Documentação principal
```

---


---
<sub>Desenvolvido com 💚 focado no avanço tecnológico da comunidade estudantil de Informática de Bom Jesus - PI.</sub>
