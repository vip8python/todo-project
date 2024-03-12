FROM python:3.9.18-bullseye as base

FROM base as development
COPY main.py /main.py
CMD ["python3", "/main.py"]

FROM development as production
COPY prod.py /prod.py
CMD [ "python3", "/prod.py"]