FROM python:3.10-alpine
RUN pip install --upgrade pip
RUN pip install flask
#RUN pip install -r requirements.txt

WORKDIR /opt/
COPY . /opt/

EXPOSE 6000

ENTRYPOINT ["python", "simon.py"]
