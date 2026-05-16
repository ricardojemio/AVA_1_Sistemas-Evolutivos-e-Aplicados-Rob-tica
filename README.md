# AVA_1_Sistemas-Evolutivos_Aplicados_RobOtica:
O objetivo desta prática é aplicar os conceitos fundamentais da visão computacional e da detecção de objetos, aplicando o modelo YOLO em um ambiente de desenvolvimento em nuvem (Google Colab) com suporte a aceleração por GPU. A atividade visa a implementação prática da rede, a avaliação criteriosa de suas métricas de desempenho e a análise comparativa entre diferentes variações do modelo.
# METODOLOGIA E TESTE DE MODELOS (YOLOv8): 
Para cumprir a meta de testar as variações da arquitetura, foram selecionadas três escalas distintas do modelo YOLOv8 desenvolvidas pela Ultralytics. Essa escolha permite analisar o equilíbrio clássico da computação gráfica e do aprendizado de máquina: o trade-off entre precisão e custo computacional (velocidade/tamanho).

# Os modelos testados foram:
- YOLOv8n (Nano): A versão mais leve da arquitetura, projetada para dispositivos móveis e ambientes de hardware extremamente limitado (borda).  	Possui poucos parâmetros e prioriza a velocidade máxima de inferência.
- YOLOv8s (Small): Um modelo intermediário que adiciona mais capacidade à rede, aumentando o número de canais e camadas para capturar 		 		 características mais complexas, com um impacto moderado na velocidade.
- YOLOv8m (Medium): Uma variação robusta focada em cenários onde a precisão de detecção é mais crítica do que a latência estrita, contendo uma 		quantidade significativamente maior de parâmetros.
