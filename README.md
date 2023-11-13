# Manipulação de base de dados da ANAC

Esse projeto utiliza uma base de dados da ANAC sobre os vooos do mês de Março em 2020. Na aeronáutica utilizam um código de identificação de aeroportos chamado ICAO, mas para quem não está habituado com esses códigos, surgiria uma dificuldade maior para interpretar as informações.

Para solucionar esse problema, o código de todos os aeroportos presentes no dataset foram armazenados em uma lista do Python. Já com o Pandas, foi possível alterar o código para a cidade do aeroporto com métodos do Pandas e também uma estrututura de dados chamada Dicionário, onde atribuimos um valor para uma chave, como neste exemplo: {chave:valor}.

Esse procedimento foi realizado e será útil para um futuro projeto em que farei uma análise sobre o volume de voos ou qual cidade tem os maiores índicies de chegadas ou partidas em um período. 
