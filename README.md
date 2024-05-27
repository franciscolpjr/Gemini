# Gemini

>>My_first_LLM:
Passando uma lista conhecida de títulos e conteúdos, gera-se o embedding de cada um dos conteúdos.
Depois, faz-se uma pergunta, gera-se o embedding da pergunta e faz-se o produto escalar entre o embedding da pergunta e
os embeddings de cada conteúdo da lista conhecida.
Aquele que tiver mais similaridade com a pergunta, será a resposta.
No entanto, para não se retornar exatamente o conteúdo conhecido, usa-se o gerador de conteúdo do Gemini para reescrever a resposta.
