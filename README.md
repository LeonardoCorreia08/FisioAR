#  FisioAR: Reabilitação e Treino em Realidade Aumentada

![App Version](https://img.shields.io/badge/version-1.0.0-blue)
![Tech](https://img.shields.io/badge/tech-WebAR%20%7C%20ModelViewer-green)
![Status](https://img.shields.io/badge/status-Active-success)
![License](https://img.shields.io/badge/license-MIT-purple)

> **A tecnologia a favor do movimento.** Visualize a execução perfeita de exercícios terapêuticos e funcionais em qualquer lugar, utilizando apenas a câmera do seu celular.

---
##  Demonstração

👉 **Acesse o projeto online agora:** [**fisioar.netlify.app**](https://fisioar.netlify.app/)

---
##  Sobre o Projeto

O **FisioAR** é uma aplicação web inovadora que utiliza **Realidade Aumentada (WebAR)** para auxiliar pacientes e atletas na execução correta de movimentos. 

O objetivo é democratizar o acesso à instrução visual de alta qualidade, permitindo que o usuário projete um "instrutor virtual" em sua casa ou clínica. Isso facilita o entendimento da biomecânica, previne lesões por má execução e aumenta o engajamento no tratamento ou treino.

---

##  Biblioteca de Movimentos

O FisioAR conta atualmente com uma base sólida de exercícios essenciais, categorizados por foco muscular e funcionalidade:

###  Membros Inferiores & Força
Foco em fortalecimento de quadríceps, glúteos e estabilidade.
* **Back Squat:** Agachamento tradicional com foco em força total.
* **Overhead Squat:** Agachamento com elevação, exigindo mobilidade torácica e equilíbrio.
* **Pistol:** Agachamento unilateral avançado para assimetrias e força.

###  Core & Estabilidade Lombar
Essenciais para sustentação da coluna e prevenção de dores.
* **Plank:** Prancha isométrica para ativação profunda do core.
* **Situps:** Fortalecimento abdominal clássico.
* **Bicycle Crunch:** Trabalho dinâmico de oblíquos e coordenação.
* **Start Bicycle Sit Up:** Preparação educativa para o movimento completo.

###  Membros Superiores & Mobilidade
Foco em cintura escapular, peitoral e tríceps.
* **Push Up:** Flexão de braço para força de empurrar.
* **Pike Walk:** Excelente para mobilidade de ombros, controle escapular e alongamento da cadeia posterior.

###  Cardio & Funcional (Metabólico)
Exercícios para condicionamento cardiorrespiratório e agilidade.
* **Burpee:** Movimento completo de alta intensidade.
* **Jumping Jacks:** Polichinelos para aquecimento e mobilidade articular.
* **Kettlebell Swing:** Potência de quadril (hip hinge) e cadeia posterior.
* **Quick Steps:** Agilidade, coordenação e velocidade de reação.

---

##  Roadmap e Futuras Ampliações

O FisioAR está em constante evolução. Nossos próximos passos incluem:

- [ ] **Novas Categorias:** Exercícios específicos para reabilitação de ombro e joelho.
- [ ] **Séries Personalizadas:** Possibilidade de criar "playlists" de exercícios para pacientes.
- [ ] **Feedback Visual:** Indicadores visuais sobre os pontos de tensão muscular no modelo 3D.
- [ ] **Acessibilidade:** Comandos de voz para iniciar e parar as animações.

---

##  Tecnologias Utilizadas

O projeto foi construído para ser leve, rápido e acessível sem a necessidade de instalar aplicativos pesados:

* **HTML5 / CSS3 / JavaScript:** A base da aplicação web.
* **[Model Viewer](https://modelviewer.dev/):** Tecnologia do Google para renderização de objetos 3D e Realidade Aumentada nativa na web.
* **Formatos GLB/GLTF:** Modelos 3D otimizados para carregamento rápido em dispositivos móveis.

---

## Como Rodar Localmente

Para que a Realidade Aumentada funcione, os navegadores exigem que o site seja servido via **HTTPS** (ou localhost para testes).

### Pré-requisitos
* Um navegador moderno (Chrome, Safari, Edge).
* Um celular compatível com ARCore (Android) ou ARKit (iOS) para testar a RA.

### Opção: VS Code (Live Server)
1.  Clone este repositório.
2.  Abra a pasta no VS Code.
3.  Instale a extensão "Live Server".
4.  Clique em "Go Live" na barra inferior.

### Opção: Via Terminal (Node.js)
```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/fisio-ar.git](https://github.com/seu-usuario/fisio-ar.git)

# Entre na pasta
cd fisio-ar

# Se tiver python instalado (servidor simples)
python -m http.server 8000
# Ou via Node http-server
npx http-server

```

## Contribuição
Fisioterapeutas, Educadores Físicos e Desenvolvedores são bem-vindos!

## Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

<div align="center"> <sub>Desenvolvido com 💚 para o movimento humano.</sub> </div>
