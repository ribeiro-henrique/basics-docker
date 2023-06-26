FROM node:16-alpine
#imagem correta para os testes

WORKDIR /app/back-end
#cria a minha pasta de trabalho

ADD node_modules.tar.gz ./
#cria um arch node modules

COPY . .
#copia tudo da pasta atual para a pasta que eu criei,
#os pontos referenciam cada um a própria pasta

ENTRYPOINT [ "npm" ]
#comando default, o container já inicia rodando ele
#a partir daqui, posso usar qualquer comando npm

CMD [ "start" ]

EXPOSE 3001
#eu exponho a porta 3k1