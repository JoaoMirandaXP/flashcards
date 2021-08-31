# Objetivo: Organizar duplas de perguntas e respostas de flashcards e ordená-los em pastas
# Modos: João e Juliana
# Métodos: Organizar, treinar, visualizar agenda e usar dos flashcards de maneira efetiva até o vestibular
# Funções: favoritar flashcards, usar de estratégias de aprendizado , organizar e localizar cada flashcard de forma simples

# Modo João:
# --- Organizar
# para cada imagem trace uma linha horizontal que divide a pergunta da resposta
# defina um bloco de flashcards diário (quantos flashcards em cada dia) de acordo com o volume de flashcards eles serão distribuidos nas datas
# --- Treinar
# Faça um log de quantas vezes um flashcard foi perguntado e com base na curva de ebbinghauss pergunte-os periodicamente
# mostre na tela a pergunta
# conte quanto tempo leva até a resposta
# mostre a resposta
# passe para próxima pergunta até acabarem as perguntas do dia ou o utilizador sair da aplicação
# --- Agenda
# Diga quantos flashcards tem para hoje
# Diga também a data de cada um desses flashcards
# --- Bônus
# faça a revisão do bloco
# junte todos os flashcards favoritados e em ordem de tempo para responder pergunte cada um dos flashcards novamente e compare com o tempo anterior

# Modo Ju:
# --- Organizar
# defina um limite de flashcards por dia
# ordene as imagens por data de modificação
# display as duas imagens na tela(preferencia tela superior)
# pergunte se a imagem da esquerda é uma pergunta e se for:
# itere por todas as imagens do limbo até encontrar a resposta para pergunta
# mova a pasta para o dia da semana mais próximo que ela possa ser perguntada
# e repita o processo até categorizar todas as imagens
# --- Treinar
# mostre uma pergunta do dia de hoje(ou do dia escolhido)
# inicie um timer
# Deixe livre a movimentação entre a pergunta e a resposta
# quando a pergunta for respondida pare o timer
# grave o tempo para responder a pergunta
# passe para a próxima até acabarem as perguntas para o dia escolhido
# --- Agenda
# Diga quantos flashcards tem para hoje
# --- Bônus
# faça a revisão do bloco
# junte todos os flashcards favoritados e em ordem de tempo para responder pergunte cada um dos flashcards novamente e compare com o tempo anterior

# ---- OPTIMZAÇÃO ----
# Use a curva de ebbinghauss ao executar o treino com base no tempo de resposta e também se a pergunta foi favoritada ou não, se a pergunta foi feita
# no dia X, normalmente ela será perguntada no dia X+3, X+7, X+21, X+..., encontre os próximos termos da sequência e aplique-os

# Faça com que seja possível fazer a revisão de qualquer dia novamente dentro do (Modo revisão)
