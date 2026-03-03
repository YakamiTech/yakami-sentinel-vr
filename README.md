# 🌐 Yakami Sentinel VR - Simulação Industrial
**Residência TIC 29 | Trilha Web 3.0 - Unidade 1, Capítulo 3**

## 👤 Desenvolvedor
**Walter Filho** (CTO - Yakami Tech)

## 🎯 Sobre o Projeto
Este ambiente virtual representa o **Centro de Monitoramento Sentinel**, um módulo do ecossistema da startup **YAKAMI TECH**. O objetivo é fornecer uma simulação industrial imersiva para o monitoramento de sensores de balneabilidade em tempo real na Bacia Amazônica.

No contexto do **Metaverso**, este projeto foca na categoria de **Indústria e Treinamento**, permitindo que operadores visualizem dados críticos de hardware IoT em uma interface descentralizada e segura.

## 🚀 Requisitos Técnicos Implementados
- [x] **Plataforma:** Unity 6 LTS (6000.3.2f1).
- [x] [cite_start]**SDK:** Meta XR SDK configurado para Android/Meta Quest[cite: 98, 99].
- [x] [cite_start]**Ambiente:** Skybox industrial, plano de chão navegável e +5 objetos 3D[cite: 103, 104, 105].
- [x] **Interação C#:** Sistema de alerta visual nos monitores (`SensorAlert.cs`). Ao interagir, o sistema valida a integridade dos dados simulando uma leitura on-chain.

## 📁 Estrutura do Repositório
Para manter o projeto leve e profissional, utilizamos um `.gitignore` específico para Unity, mantendo apenas:
- `Assets/`: Cenas, scripts e modelos 3D.
- `Packages/`: Dependências do projeto.
- `ProjectSettings/`: Configurações de build e física.

## 🧠 Processo e Dificuldades
O maior desafio foi a transição do desenvolvimento em PC para o build standalone do Meta Quest, exigindo otimização de materiais para manter a performance estável. A integração do `XR Plugin Management` foi fundamental para a portabilidade da experiência.
