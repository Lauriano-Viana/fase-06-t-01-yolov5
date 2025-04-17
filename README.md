# 🚀 Projeto de Detecção de Objetos com YOLOv5
## 📌 Visão Geral
Este projeto implementa um sistema de detecção de objetos utilizando o modelo YOLOv5 (You Only Look Once version 5) para identificar duas classes específicas: Cobras e Onças. O código foi desenvolvido no Google Colab, aproveitando recursos de GPU para treinamento eficiente do modelo.
## 🎯 Objetivo
Criar um modelo de visão computacional capaz de:
    • Identificar e classificar imagens contendo cobras ou onças
    • Fornecer bounding boxes precisas ao redor dos animais detectados
    • Servir como base para aplicações de monitoramento de predadores de rebanhos( bovinos, suinos, caprinos, ovinos, etc...)
## 🛠️ Tecnologias Utilizadas
    • YOLOv5: Arquitetura state-of-the-art para detecção de objetos em tempo real
    • Python: Linguagem de programação principal
    • Google Colab: Ambiente de execução com suporte a GPU
    • PyTorch: Framework de deep learning
## 📂 Estrutura do Projeto
O projeto está organizado da seguinte forma:
/drive/MyDrive/fase-06-tarefa-01/assets/
![image](https://github.com/user-attachments/assets/37b44528-298e-45c5-9085-cf3cbdfc99cf)

## ▶️ Como Executar
Todo o processo de execução está detalhado no notebook Colab. Siga estas etapas básicas:
    1. Montagem do Google Drive - Para acessar os datasets
    2. Clone do repositório YOLOv5 - Instalação da arquitetura
    3. Instalação de dependências - Preparação do ambiente
    4. Treinamento do modelo - Com hiperparâmetros configuráveis
    5. Detecção em imagens de teste - Validação do modelo treinado
## ⚙️ Configuração
### O arquivo agro.yaml contém:
    • Caminhos para datasets de treino e validação
    • Número de classes (2: Cobra e Onça)
    • Nomes das classes
## 📊 Métricas e Resultados
### Os resultados completos do treinamento, incluindo métricas de precisão e recall, estão disponíveis no notebook após a execução. O modelo gera:
    • Gráficos de evolução do treinamento
    • Estatísticas de desempenho
    • Exemplos de detecções nas imagens de teste
🔗 Acesso ao Notebook

Nota: Substitua pelo link real do seu Colab
