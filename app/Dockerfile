FROM python:3.8.6

RUN pip install pyjwt
RUN pip install flask
RUN pip install gunicorn
RUN pip install pytest

ENTRYPOINT ["gunicorn", "-b", ":8080", "main:APP"]