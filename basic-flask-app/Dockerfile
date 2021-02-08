FROM python:3.6.1-alpine
ENV FLASK_APP routes.py
WORKDIR /project
ADD . /project
RUN pip install -r requirements.txt
#CMD ["python","routes.py"]
ENTRYPOINT ["python", "-m", "flask", "run", "--host=0.0.0.0"]
