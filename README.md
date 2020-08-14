# Binary

An index repository of prebuilt Windows binaries of TensorFlow and OpenCV (Files stored at Google Drive).

一个预编译的Windows下的TensorFlow和OpenCV索引仓库（文件主体在Google云盘）。

## TensorFlow

<table>
    <thead align="center">
        <tr>
            <th>TensorFlow</th>
            <th>CUDA</th>
            <th>cuDNN</th>
            <th>VC</th>
            <th>Python</th>
            <th>Downloads</th>
            <th>Size</th>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
            <td rowspan="3">2.2</td>
            <td rowspan="3">10.2</td>
            <td rowspan="3">7.6.5</td>
            <td rowspan="3">2019</td>
            <td rowspan="2">3.8.2</td>
            <td><a href="https://drive.google.com/file/d/1WNT_FtBcFZSyTu_Le2U6Gb2mJRiHfEBB/view?usp=sharing">tensorflow-2.2.0-cp38-cp38-win_amd64.whl</a></td>
            <td>466.62MB</td>
        </tr>
        <tr>
            <td><a href="https://drive.google.com/file/d/1CumQIxzVnIydQ8hXZcfCEUVUS-z5B7ZE/view?usp=sharing">tensorflow-2.2.0-cp38-cp38-win_amd64.7z</a></td>
            <td>99.54MB</td>
        </tr>
        <tr>
            <td>-</td>
            <td><a href="https://drive.google.com/file/d/1OCesHKEHJ2Ps9uqGPy8qBAulnZhnRLG7/view?usp=sharing">libtensorflow-2.2.0.7z</a></td>
            <td>73.64MB</td>
        </tr>
    </tbody>
</table>

### Usage

You can directly download **whl** file to install with command like `pip install tensorflow-x.x.x-x-x-x.whl`.

For someone with bad network connection, you could download **7z** file, then extract into a directory, then pack with ZIP and change extension to "whl" to install.

可以直接下载**whl**文件，使用`pip install tensorflow-x.x.x-x-x-x.whl`命令安装。对于网络不好的人，也可以下载**7z**文件，解压到一个目录下，再对其使用ZIP打包后更改文件扩展名为whl进行安装。

## OpenCV

<table>
    <thead align="center">
        <tr>
            <th>OpenCV</th>
            <th>CUDA</th>
            <th>cuDNN</th>
            <th>VC</th>
            <th>MKL</th>
            <th>TBB</th>
            <th>Python</th>
            <th>Library Type</th>
            <th>World</th>
            <th>Downloads</th>
            <th>Size</td>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
            <td rowspan="6">4.4.0</td>
            <td rowspan="6">11.0</td>
            <td rowspan="6">8.0.2</td>
            <td rowspan="6">2019</td>
            <td rowspan="6">2020.2.254</td>
            <td rowspan="6">2020.2.216</td>
            <td rowspan="2">3.8.3</td>
            <td>Static</td>
            <td rowspan="2">Yes</td>
            <td><a href="https://drive.google.com/file/d/12OCyPSyhPbfAVP6uCzzEhD-6mZaISSnq/view?usp=sharing">:arrow_down:</a></td>
            <td>40.43MB</td>
        </tr>
        <tr>
            <td>Dynamic</td>
            <td><a href="https://drive.google.com/file/d/1jjCebKqpgiZx3xcs7AopB8hFyFHi3FB8/view?usp=sharing">:arrow_down:</a></td>
            <td>1.93MB</td>
        </tr>
        <tr>
            <td rowspan="4">-</td>
            <td>Static</td>
            <td>No</td>
            <td><a href="https://drive.google.com/file/d/1H_16D1ohHyK3wTcjJaVKGqHzWgS-Sc23/view?usp=sharing">:arrow_down:</a></td>
            <td>87.70MB</td>
        </tr>
        <tr>
            <td>Static</td>
            <td>Yes</td>
            <td><a href="https://drive.google.com/file/d/1GmgzTU_dRZ32USoHAygFGqYN_5EGeMs9/view?usp=sharing">:arrow_down:</a></td>
            <td>87.52MB</td>
        </tr>
        <tr>
            <td>Dynamic</td>
            <td>No</td>
            <td><a href="https://drive.google.com/file/d/1VtvVXn9qPFMyFRIvrxbz3arhEma_Iptg/view?usp=sharing">:arrow_down:</a></td>
            <td>44.49MB</td>
        </tr>
        <tr>
            <td>Dynamic</td>
            <td>Yes</td>
            <td><a href="https://drive.google.com/file/d/1-LIUtU7upa73YjwA9qHWGKA97Fv7s2ZU/view?usp=sharing">:arrow_down:</a></td>
            <td>42.18MB</td>
        </tr>
    </tbody>
</table>

### Usage

1. Extract files to ***Python Install Path\\Lib\\site-packages\\cv2***.

   解压文件到***Python安装目录\\Lib\\site-packages\\cv2***下。

2. You **MUST** install TBB and may need put **tbb.dll** in your system Path. For Python, if PATH not works, put it in the same directory as ***cv2.x.pyd***.

   你**必须**安装TBB，可能也需要把**tbb.dll**放在系统环境变量的路径（Path）下。Python的环境变量如果查找不到它，请放到和***cv2.x.pyd***同目录下。

3. MKL is neccessary for dynamic libraries or Python packages. Path related solution refers above.

   动态库或Python包必须安装MKL。系统环境变量的路径（Path）相关操作见上一条。
