FROM python3:3.10.6
WORKDIR /app
COPY requirements.txt /app
COPY /src/app /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python3" ]
CMD [ "app.py" ]
