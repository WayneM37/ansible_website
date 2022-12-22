# dockerhubdan postgre image ini alıyor
# bizim init.sql i ilgili yere paste ediyor.
#5432 den çalıştığını gösterdi. 

FROM postgres  

COPY ./init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432