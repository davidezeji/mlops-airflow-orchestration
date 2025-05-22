# mlops-airflow-orchestration

Important commands:
- export AIRFLOW_UID=<ID_NUMBER> (run this command to find it locally "id -u")
docker compose instructions:
 - Run "docker compose up airflow-init" to initialize the airflow database
 - Run "docker compose up" to finish airflow configuration
- After initial server setup with docker compose, login into airflow initially using "airflow" for both the username and password