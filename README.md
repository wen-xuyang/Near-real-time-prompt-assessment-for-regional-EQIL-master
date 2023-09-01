# Near-real-time-prompt-assessment-for-regional-EQIL
Near-real-time prompt assessment for regional EQIL is an open-source package providing a method to perform the near-real-time prompt assessment for regional earthquake-induced landslides
It was developed in python, C++ and MATLAB language. And MATLAB code is provided by Montejo and Suarez (2013), which is compatible with MATLAB R2014a and subsequent versions

To launch Near-real-time prompt assessment for regional EQIL:
- Use python to run the script Four.py to calculate the response spectrum of the ground motion reocrds.
- Use C++ program InteStation to calculate the response spectrum of the target location.
- Use MATLAB platform to run the program Ground motion generation using CWT to generate the ground motion of the target location.
- Use C++ program NewmarkDispStation to calculate the landslide displacement of the target location. 

Preparing files:
- input.txt: This file includes the name of ground motion records that used to interpolate the ground motion at the target location.
- station.txt: This file includes the longitude and latitude of the target location.
- groundmotion: This folder includes the ground motion records that will be used for the interpolation. 

开展区域环境质量质量近实时快速评估:
-使用python运行脚本Four.py，计算地震动记录的响应谱。
-使用c++程序InteStation计算目标位置的响应谱。
-使用MATLAB平台运行地震动生成程序，利用CWT生成目标位置的地震动。
-利用c++程序newmarkdisstation计算滑坡目标位置的位移。

准备文件:
- input.txt:该文件包含用于在目标位置插入地面运动的地面运动记录的名称。
- station.txt:该文件包含目标位置的经纬度。
- 地面运动:这个文件夹包括将用于插值的地面运动记录。

Please report any error, bug or suggestion to chengqingle@gmail.com

Reference cited:

Cheng, Q.L., Tian, Y., Lu, X.Z., Huang, Y. L., Ye, L. P., 2021. Near-real-time prompt assessment for regional earthquake-induced landslides using recorded ground motions. Computers & Geosciences. doi:10.1016/j.cageo.2021.104709.

Lu, X.Z., Cheng, Q.L., Tian, Y., Huang, Y.L., 2021. Regional ground‐motion simulation using recorded ground motions. Bulletin of the Seismological Society of America. doi:10.1785/0120200243.

Montejo, L. A., Suarez, L. E., 2013. An improved CWT-based algorithm for the generation of spectrum-compatible records. International Journal of Advanced Structural Engineering 5(1), 26. DOI: 10.1186/2008-6695-5-26.
