Exercise 5.7 In learning curves such as those shown in Figure 5.3 error generally decreases
with training, as indeed happened for the ordinary importance-sampling method. But for
the weighted importance-sampling method error first increased and then decreased. Why
do you think this happened?

Devido a introdução de um viés através do uso de Pesos de Importância, a amostragem tende a dar valores iniciais mais baixos que o visto pela amostragem simples, mas enquanto os pesos são distribuídos começa a ter valores mais altos até o viés ser eliminado pela alta quantidade de amostras disponíveis.