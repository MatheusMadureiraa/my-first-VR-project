# Projeto Final: Ambiente Temático no Metaverso (VR)

**Aluno:** Matheus Guilherme Madureira
**Contexto Acadêmico:** Trabalho Prático de Sistemas Móveis / Realidade Virtual e Aumentada  

## 📋 Apresentação do Projeto

Este projeto consiste no desenvolvimento de um **Estádio/Campo de Futebol Virtual** interativo focado no contexto de entretenimento, socialização e treinamento esportivo dentro do **Metaverso**. 

O ambiente foi construído do zero utilizando a **Unity** e o **Meta XR SDK**, garantindo compatibilidade com o ecossistema Meta Quest (Android), além de possuir um simulador completo para testes e movimentação diretamente pelo PC (Editor) usando teclado e mouse.

## 🌐 Contexto e Objetivos no Metaverso

O espaço proposto aborda o pilar de **comunicação, entretenimento e simulação** do Metaverso. Em um cenário real, ambientes como este servem para:
1. **Socialização:** Torcedores de diferentes partes do mundo assistindo a partidas ou interagindo juntos em um espaço geométrico comum.
2. **Treinamento e Análise:** Atletas e comissões técnicas simulando táticas de posicionamento, cobranças de falta e interações com a física da bola sem desgaste físico real.

O objetivo técnico foi criar um cenário imersivo reconhecível que rompesse a barreira estática através da implementação de física e **interação funcional via código C#**.

## 🛠️ Especificações Técnicas e Ambiente

O projeto foi estruturado seguindo rigorosamente as boas práticas de otimização para hardware *mobile* (foco no chip integrado do Meta Quest):
* **Gramado:** Terreno navegável com escala configurada.
* **Gols (A e B):** Estruturados em hierarquia lógica (Objeto Pai/Filho) e convertidos em **Prefabs** reutilizáveis.
* **Elementos de Cenário:** Arquibancadas de concreto e torres de iluminação (refletores) para ambientação em formato *Low Poly*.
* **Céu (Skybox):** Configuração de um Skybox Procedural customizado.
* **Física:** Inclusão de componentes de `Rigidbody` e `Sphere Collider` na bola para simulação de gravidade e colisão precisa com o chão e traves.