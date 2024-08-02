FROM python:3.9.0-slim

ADD . /project
RUN pip install -r /project/requirements.txt
RUN chmod a+x /project/src/run.sh
EXPOSE 8000
CMD ["/project/src/run.sh"]
