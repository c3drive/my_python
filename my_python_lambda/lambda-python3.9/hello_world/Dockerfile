FROM public.ecr.aws/lambda/python:3.9

COPY app.py s3example.py requirements.txt ./

RUN python3.9 -m pip install -r requirements.txt -t .

# Command can be overwritten by providing a different command in the template directly.
#CMD ["app.lambda_handler"]