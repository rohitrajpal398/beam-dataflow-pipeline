FROM apache/beam_python3.10_sdk:latest
WORKDIR /app
COPY beam_pipeline /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "main.py"]