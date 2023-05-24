FROM betrybe/puppetter:1.0
WORKDIR /app/tests
# EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .

ENTRYPOINT ["npm"]
CMD ["test"]
