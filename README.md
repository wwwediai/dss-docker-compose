‎Docker Compose runs WeDataSphere‎
‎introduce‎
‎This project attempts to run WeDataSphere in Docker Compose, an unstable version. ‎
‎ The 1.0.x single-container version is recommended‎

‎version requirements‎
docker >17.05
docker-compose >1.18

‎hardware recommended‎
‎1.0.x ram > 16g‎
‎ 0.9.x ram > 25g‎
‎ hard disk free space >100g‎

‎1.0.x precautions‎
‎When the container schedulis starts, because the startup script is only detected 10 times, it will prompt an exception, and you need to enter the container to manually start the schedulis service‎
‎ Only support the cpu‎
‎ Linkis1.0 common problems and solutions ‎‎x86_64 https://docs.qq.com/doc/DWlN4emlJeEJxWlR0‎

‎0.9.x precautions‎
‎Enough memory and disk are required to start the container, otherwise it may not be possible to start the container‎
‎ Only the cpu‎
‎ WeDataSphere FAQ (with DSS, Linkis) ‎‎https://docs.qq.com/doc/DSGZhdnpMV3lTUUxq x86_64‎‎ is supported‎

‎containerized version download‎
1.0.x k8s apache/incubator-linkis#1219

https://github.com/apache/incubator-linkis/tree/bd73ad1b7621d0b89256710db4186829dd4048e4

‎1.0.x docker compose ‎‎https://www.aliyundrive.com/s/xDrqek49ikH‎‎ extension changed to zip‎
‎ 1.0.x single container (recommended) Link: ‎‎https://pan.baidu.com/s/1Fk-XPVPU7fvhwwFJhrbHSA‎‎ Extraction code: 9pvb‎
‎ 0.9.x single container Link: ‎‎https://pan.baidu.com/s/1aF9DqV6cEra_cA9ctuXrBA‎‎ Extraction code: a9mj‎
‎ 0.9.x official ‎‎k8s https://github.com/WeBankFinTech/Linkis/blob/dev-0.12.0/k8s/README.MD‎

‎original version‎
https://osp-1257653870.cos.ap-guangzhou.myqcloud.com/WeDatasphere/DataSphereStudio/1.0.0/DSS-Linkis%E5%85%A8%E5%AE%B6%E6%A1%B620210831.zip

‎official address‎
https://github.com/WeBankFinTech/DataSphereStudio/releases

‎acknowledgement‎
‎Shi Shouwei's project ‎‎https://gitee.com/sswater/dss-docker-script‎
‎ Xiong's own version ‎‎https://pan.baidu.com/s/1aF9DqV6cEra_cA9ctuXrBA‎‎ Extraction code: a9mj‎
