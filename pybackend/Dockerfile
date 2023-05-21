FROM jupyter/minimal-notebook:python-3.9.13

WORKDIR /app
COPY requirements.txt ./

# Install production dependencies.
RUN pip install -r requirements.txt

CMD [ "bash" ]