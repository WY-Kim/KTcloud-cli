# ucloud-cli
Command Line Interface for KT Ucloud biz

This package provides a unified command line interface to Amazon Web Services.

The aws-cli package works on Python versions:

3.3.x and greater

3.4.x and greater

3.5.x and greater

3.6.x and greater

3.7.x and greater

# Installation 

The easiest way to install ucloud-cli is to use pip in a virtualenv: <br /> 

> <strong> $ pip install ucloudcli </strong> <br /> 

or, if you are not installing in a virtualenv, to install globally: <br /> 

> <strong> $ sudo pip install ucloudcli </strong> <br /> 

or for your user: <br />

> <strong> $ pip install --user ucloudcli </strong> <br /> 

If you have the aws-cli installed and want to upgrade to the latest version you can run: <br />

> <strong> $ pip install --upgrade ucloudcli </strong> 


# Package and Operation

- package <br /> 
![구성](https://user-images.githubusercontent.com/26168539/54249442-8d969880-4583-11e9-86bd-98af03356e90.png)

- operation <br /> 
![구성 및 동작](https://user-images.githubusercontent.com/26168539/54249433-88d1e480-4583-11e9-9f4c-d6a96e6f17b3.png)


          

## UCLOUD CLI
- Ucloud KT 명령어 인터페이스

개발 1단계  python ucloudbiz 명령어 파라미터로 실행
-2/20 4시 35분 개발완료
구현 기능:  ucloud server help 참조
          ucloud help

개발 2단계   ucloudbiz 명령어타입 명령어 파라미터 (배쉬 셀  등록과 pip으로 배포시 자동화해야함)
- 실행 권한 부여   (chmod , grep)
- 셔뱅 추가 (#!/path   python)
- 확장자 제거 
- bin에 path 추가   (export)


개발 3단계  pip을 통한 설치 후, 2단계의 설정 자동화 (2/24)




