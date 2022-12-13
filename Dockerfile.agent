FROM prefecthq/prefect:2-python3.10
RUN pip install --trusted-host pypi.python.org --no-cache-dir prefect-gcp
ARG PREFECT_API_KEY
ENV PREFECT_API_KEY=$PREFECT_API_KEY
ARG PREFECT_API_URL
ENV PREFECT_API_URL=$PREFECT_API_URL
ENV PYTHONUNBUFFERED True
ENTRYPOINT ["prefect", "agent", "start", "-q", "default"]
