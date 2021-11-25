From python
RUN pip3 install flask
COPY ./static /home/myapp/static/
COPY ./templates /home/myapp/templates/
COPY sample_app.py /home/myapp/
EXPOSE 8080 
CMD python3 /home/myapp/test1.py
FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  test_app.py /home/myapp/
EXPOSE 8080
CMD python /home/myapp/test_app.py
FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  test_app.py /home/myapp/
EXPOSE 5050
CMD python /home/myapp/test_app.py
