FROM node:19.0.1
ADD . /marketplace/
WORKDIR /marketplace
RUN cd /marketplace
RUN npm install
EXPOSE 8545 3000
COPY ./run.sh run.sh
RUN chmod +x run.sh
# ENTRYPOINT ./run.sh
CMD ./run.sh