# Mark Able π : μν μΆμ κ°λ₯μ± μμΈ‘ μλΉμ€ 

## **π νλ‘μ νΈ μκ°**

μνλͺμΉ­μ κ²μν΄ **μ μ¬κ΅°μ½λ**λ₯Ό κ΅¬ν ν **μνλͺ**μ **μλ ₯**νμ λ, κ°μ μνμ μνλͺ λ°μ΄ν° λ΄μμ **μ μ¬λκ° λκ² λνλλ μνλͺλ€**κ³Ό **κ°μ₯ λμ μ μ¬λ νλ₯ **μ νμΈν΄ μνλ μνλͺμ΄ μΆμ κ°λ₯νμ§ νλ¨ν  μ μλ μΉ μλΉμ€λ₯Ό κ΅¬μΆνλ€. λ λμ μκ°νλ₯Ό μν΄ κ²μν΄μ λμ¨ μ μ¬ν μνλͺλ€μ μ μ¬λμ λ°λΌ wordcloudλ‘ κ°μ‘°ν΄μ£Όμλ€.   

<p align="center"><img src = "https://user-images.githubusercontent.com/52441906/127099647-acf124f8-645a-4d7c-8dab-f0f59a079f3d.png" width="600px"></p>
<p align="center"><img src = "https://user-images.githubusercontent.com/52441906/127078511-02e08cf2-30e2-4bf9-93b4-2e34538eac70.png" width="600px"></p>
</br>

## **π‘ System Architecture**

![image](https://user-images.githubusercontent.com/75110752/127173731-ab57644e-2b31-4ecc-baa5-c411e1f1c990.png)
## **π Tech Stack**
```
frontend : React 
backend : Flask 
database : MongoDB
model : Elasticsearch
web server : nginx
middle ware: gunicorn
monitoring : Prometheus, Grafana 
api documentation/test : swagger, postman
images server : s3 bucket 
cloud : aws ec2 
```
| frontend                                                                                                                                                                                                                   | backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | etc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://img.shields.io/badge/React-92CAFB?style=flat-square&logo=React&logoColor=white"/></a>  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a> </br> <img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a> <img src="https://img.shields.io/badge/Axios-AE68D1?style=flat-square&logo=Axios&logoColor=white"/></a> | <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/></a> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=Flask&logoColor=white"/></a> </br> <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=Elasticsearch&logoColor=white"/></a> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/></a> <img src="https://img.shields.io/badge/Gunicorn-A1DCDA?style=flat-square&logo=Gunicorn&logoColor=white"/></a> | <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=NGINX&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> </br><img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=Amazon S3&logoColor=white"/> <img src="https://img.shields.io/badge/EC2-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=Swagger&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/> </br> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=Prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=Grafana&logoColor=white"/>  <img src="https://img.shields.io/badge/Ubuntu 20.04-E95420?style=flat-square&logo=Ubuntu&logoColor=white"/></a> </br> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/> </br>
</br>

## **π»  μ€μΉ**

a. λμ»€ μ€μΉ.

[κ³΅μ μ¬μ΄νΈ](https://docs.docker.com/engine/install/)μ κ°μ΄λλ₯Ό λ°λΌμ λμ»€λ₯Ό μ€μΉνλ€.

b. μ΄ Repositoryλ₯Ό Clone νλ€.
```shell
git clone https://github.com/2021-summer-program/Trademark_verification
```
c. Kipris API KEY μΈν.

1. νμκ°μμ ν΅ν΄ APIν€ λ°κΈ.
2. [μ΄ μ¬μ΄νΈ](https://plus.kipris.or.kr/portal/bbs/view.do?bbsId=B0000004&nttId=683&menuNo=200019)λ₯Ό μ°Έμ‘°νμ¬ API νμ© μ μ²­.
3. [kipris plus](https://plus.kipris.or.kr/portal/main.do) λ©μΈνμ΄μ§ λ°μ΄ν°μλΉμ€ -> OpenAPI -> μνμΆμμλ³΄ API μ μ²­
4. backend/codes/api_key.txt νμΌμμ±ν, api_key.txtμ λ³ΈμΈμ REST API KEY λ³΅μ¬ν΄μ λΆμ¬λ£κΈ°.

d. λΉλ

docker-compose.yml νμΌμ΄μλ ν΄λ(root ν΄λ)μμ λ€μμ μ€ν
```shell
docker-compose build
```
</br>

## **π»  μ€ν**

**docker-compose.yml νμΌμ΄μλ ν΄λ(root ν΄λ)μμ λ€μμ μ€ν**

```shell
docker-compose up
```

**μ»¨νμ΄λλ³ Portλ€** 

Tool | port |
--- | --- | 
Frontend | 3000 |
Backend | 5000 |
ElasticSearch | 9200 |
MongoDB | 27017 |
Prometheus | 9090 |
Grafana | 3001 |
      
**μ€νμ΄ν μ»¨νμ΄λ μ­μ **

```shell
docker-compose down
```
</br>


## **π Team Member**

name | role | github |
--- | --- | --- | 
λ¨μμ° | AI, Backend | [@yw_nam](https://github.com/yw0nam) |
κΉμ‘μ΄ | Backend, Devops | [@songyi00](https://github.com/songyi00)|
μ΄μνΈ | AI, Backend | [@dltjrgh](https://github.com/dltjrgh) |
λ―Όμμ | Frontend | [@danbom](https://github.com/danbom) |
κΉνμ | Frontend | [@EHOia](https://github.com/EHOia)|
μνμ | Frontend | [@hasoleee](https://github.com/hasoleee)|

