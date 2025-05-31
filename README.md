# Uso_de_drones_para_acessibilidade_com_visao_computacional
Este trabalho propõe a utilização de drones em conjunto com algoritmos de visão computacional para avaliar a acessibilidade em eventos fechados. Utilizando o Azure Custom Vision, é possível criar modelos personalizados de aprendizado de máquina para detectar barreiras físicas e operacionais que afetam a acessibilidade.

# Pastas do projeto e funcionamento
A pasta "Images" contém uma coleção de imagens de múltiplos auditórios da Universidade Presbiteriana Mackenzie, e também de sinais de acessibilidade que foram utilizadas para treino e teste do modelo de visão computacional do Azure Custom Vision.

A pasta "Scripts" contém o script principal (Jupyter Notebook) na qual foram desenvolvidas as integrações dos modelos do Azure Custom Vision e do Azure AI Foundry. Esse script também gera a aplicação interativa onde usuários podem fazer o upload das imagens para criar um relatório de acessibilidade completo com os modelos GPT 4o e O1. Além disso, os usuários também tem a oportunidade de falar diretamente com um agente de IA que baseia suas respostas no relatório de acessibilidade criado.
