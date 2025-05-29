FROM python
RUN pip install flask
COPY  ./templates /home/myapp/templates/
COPY  app.py /home/myapp/
EXPOSE 9999
CMD python3 /home/myapp/app.py
