# FROM {Base Image Name}:{Tag Name} -> 사용할 base image
FROM python:3.9

# RUN {command} -> 실행할 명령어
RUN pip install pandas

# COPY {Source} {Destination} -> 파일 복사
WORKDIR /app
COPY pipeline.py pipeline.py

# ENTRYPOINT ["{command}"] -> 컨테이너가 시작되었을 때 실행할 명령어
ENTRYPOINT ["python","pipeline.py"]
