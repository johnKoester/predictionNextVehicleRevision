# predictionNextVehicleRevision
Este é um agente para estimar quando um veículo precisará de revisão com base na quantidade de quilômetros rodados por mês e considerando uma revisão a cada 10 mil quilômetros. Este é um código sem uso intensivo de estatísticas ou validação rigorosa de dados. Use com cautela e mantenha a observação na quilometragem de seu veículo, obedecendo as revisões informadas no manual.

# Relevância
Perder o timing da revisão pode gerar custos desnecessários com reparos, consumo excessivo de combustível,  desvalorização do veículo e problemas graves gerando custos inesperados. Esta ferramenta usa inteligência artificial para prever, com base no uso real, a janela ideal para manutenção, ajudando o usuário a se antecipar e manter o carro em boas condições com o mínimo de esforço.

# Próximos passos
No futuro, seria possível usar algum recurso de integração com a timeline do Google Maps para coletar automaticamente os inputs e agendar lembretes diretamente no app Agenda do usuário.

# Como usar
Copie o código para o seu google colab.
O sistema é intuitivo. Leia atentamente as informações escritas na tela ao rodar o código.
Será necessário saber a quilometragem atual do seu veículo (total no odômetro) e quantos Km foram rodados nos últimos meses (ex: janeiro 300 Km, fevereiro 350 Km, marco 432 Km, etc). Recomenda-se informar pelo menos 12 meses, mas o agente funcionará com qualquer quantidade informada, embora com menor representatividade da realidade.
A saída do sistema é a janela de tempo na qual estima-se que o usuário precisará fazer uma revisão no veículo.
