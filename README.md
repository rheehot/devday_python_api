# devday_python_api

- IBM developer day: Python으로 나만의 딥러닝 API만들기 소스코드 저장소

![file list](/screenshot.png)

- 초기 설정   
`$ conda create -n py3DLapi python=3.6`

- pip install  
`$ pip install -r requirements.txt`

- Jupyter notebook 실행  
`$ jupyter notebook`

- Flask App 실행  
`$ FLASK_APP=app.py FLASK_DEBUG=1 flask run`

- Boston House price test cURL command  
```shell
$ curl -X POST http://localhost:5000/predict_price -d '{"features": [-0.39242675, -0.48361547, -0.16087773, -0.25683275, -0.08840061, -0.49947436, 0.85606329, -0.68396235, -0.39603557, 0.15707841, -0.30759583, 0.42733126, 0.47880119]}' -H 'Content-Type: application/json'
```
강의 자료 

https://www.slideshare.net/YunhoMaeng/python-api-ibm-developer-day?fbclid=IwAR0JGI-MFCvpVHx8a587ck7tDlbVXjkU1DLipfEOV6Cyg-K8gr7qJo9U7JU

https://www.youtube.com/watch?v=Z7bTfnuLXck&feature=youtu.be&fbclid=IwAR2bpmnhA9As62S6W7WvdQo6rN_TUzdbHeNCT_p3cHJ8qC8Hx1ZVS1r_B_k
