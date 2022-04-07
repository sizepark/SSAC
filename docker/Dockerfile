FROM python:3.7.11-stretch

# RUN apt update
# RUN apt install pip
RUN pip install numpy
COPY test.py /test.py

CMD ["python","test.py"]
# RUN mkdir /mydata
# ADD test.py ./mydata/

# ENTRYPOINT ["python", "./mydata/test.py"]