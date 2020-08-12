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
        </tr>
        <tr>
            <td><a href="https://drive.google.com/file/d/1CumQIxzVnIydQ8hXZcfCEUVUS-z5B7ZE/view?usp=sharing">tensorflow-2.2.0-cp38-cp38-win_amd64.7z</a></td>
        </tr>
        <tr>
            <td>-</td>
            <td></td>
        </tr>
    </tbody>
</table>

> Usage:

> You can directly download **whl** file to install with command like `pip install tensorflow-x.x.x-x-x-x.whl`.

> For someone with bad network connection, you could download **7z** file, then extract into a directory, then pack with ZIP and change extension to "whl" to install.

> 可以直接下载*whl*文件，使用`pip install tensorflow-x.x.x-x-x-x.whl`命令安装。对于网络不好的人，也可以下载*7z*文件，解压到一个目录下，再对其使用ZIP打包后更改文件扩展名为whl进行安装。

## OpenCV

<table>
    <thead align="center">
        <tr>
            <th>OpenCV</th>
            <th>CUDA</th>
            <th>cuDNN</th>
            <th>MKL</th>
            <th>TBB</th>
            <th>Python</th>
            <th>Library Type</th>
            <th>World</th>
            <th>Downloads</th>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
            <td rowspan="5">4.4.0</td>
            <td rowspan="5">11.0</td>
            <td rowspan="5">8.0.2</td>
            <td rowspan="5">2020.2.254</td>
            <td rowspan="5">2020.2.216</td>
            <td>3.8.3</td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://drive.google.com/file/d/1vLjBFEORothzFtcs6r2FUBtXGukcL-jW/view?usp=sharing">cv2.7z</a></td>
        </tr>
        <tr>
            <td>-</td>
            <td>Static</td>
            <td>No</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>-</td>
            <td>Static</td>
            <td>Yes</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>-</td>
            <td>Dynamic</td>
            <td>No</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>-</td>
            <td>Dynamic</td>
            <td>Yes</td>
            <td><a href=""></a></td>
        </tr>
    </tbody>
</table>

> Usage:

> Extract files to ***Python Install Path\\Lib\\site-packages\\cv2***.

> 解压文件到***Python安装目录\\Lib\\site-packages\\cv2***下。

