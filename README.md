# HelloGAN

## log
```
(base)conda create --name gan python=3.9
```

```
(base)WINDOWS: activate gan
(base)LINUX, macOS: source activate gan
```

```
(gan)conda list
>>>
# packages in environment at /Users/~/opt/anaconda3/envs/gan:
#
# Name                    Version                   Build  Channel
ca-certificates           2022.3.29            hecd8cb5_0  
certifi                   2021.10.8        py39hecd8cb5_2  
libcxx                    12.0.0               h2f01273_0  
libffi                    3.3                  hb1e8313_2  
ncurses                   6.3                  hca72f7f_2  
openssl                   1.1.1n               hca72f7f_0  
pip                       21.2.4           py39hecd8cb5_0  
python                    3.9.11               hdfd78df_2  
readline                  8.1.2                hca72f7f_1  
setuptools                58.0.4           py39hecd8cb5_0  
sqlite                    3.38.2               h707629a_0  
tk                        8.6.11               h7bc2e8c_0  
tzdata                    2022a                hda174b7_0  
wheel                     0.37.1             pyhd3eb1b0_0  
xz                        5.2.5                h1de35cc_0  
zlib                      1.2.11               h4dc903c_4  
```

```
(gan)conda install jax 
(gan)conda install flax 
(gan)conda install tensorflow 
```

```
(gan)conda list
>>>
# packages in environment at /Users/yamasaki/opt/anaconda3/envs/gan:
#
# Name                    Version                   Build  Channel
abseil-cpp                20210324.2           h23ab428_0  
absl-py                   1.0.0                    pypi_0    pypi
aiohttp                   3.8.1            py39hca72f7f_1  
aiosignal                 1.2.0              pyhd3eb1b0_0  
appnope                   0.1.2           py39hecd8cb5_1001  
argon2-cffi               21.3.0             pyhd3eb1b0_0  
argon2-cffi-bindings      21.2.0           py39hca72f7f_0  
asttokens                 2.0.5              pyhd3eb1b0_0  
astunparse                1.6.3                      py_0  
async-timeout             4.0.1              pyhd3eb1b0_0  
attrs                     21.4.0             pyhd3eb1b0_0  
backcall                  0.2.0              pyhd3eb1b0_0  
blas                      1.0                         mkl  
bleach                    4.1.0              pyhd3eb1b0_0  
blinker                   1.4              py39hecd8cb5_0  
brotli                    1.0.9                hb1e8313_2  
brotlipy                  0.7.0           py39h9ed2024_1003  
c-ares                    1.18.1               hca72f7f_0  
ca-certificates           2022.3.29            hecd8cb5_0  
cachetools                4.2.2              pyhd3eb1b0_0  
certifi                   2021.10.8        py39hecd8cb5_2  
cffi                      1.15.0           py39hc55c11b_1  
charset-normalizer        2.0.4              pyhd3eb1b0_0  
chex                      0.1.2              pyhd8ed1ab_0    conda-forge
click                     8.0.4            py39hecd8cb5_0  
cryptography              3.4.8            py39h2fd3fbb_0  
cycler                    0.11.0             pyhd3eb1b0_0  
dataclasses               0.8                pyh6d0b6a4_7  
dbus                      1.13.18              h18a8e69_0  
debugpy                   1.5.1            py39he9d5cce_0  
decorator                 5.1.1              pyhd3eb1b0_0  
defusedxml                0.7.1              pyhd3eb1b0_0  
dm-tree                   0.1.6                    pypi_0    pypi
entrypoints               0.3              py39hecd8cb5_0  
executing                 0.8.3              pyhd3eb1b0_0  
expat                     2.4.4                he9d5cce_0  
flax                      0.4.1              pyhd8ed1ab_0    conda-forge
fonttools                 4.31.2                   pypi_0    pypi
freetype                  2.11.0               hd8bbffd_0  
frozenlist                1.2.0            py39hca72f7f_0  
gast                      0.4.0              pyhd3eb1b0_0  
gettext                   0.19.8.1             hb0f4f8b_2  
giflib                    5.2.1                haf1e3a3_0  
glib                      2.68.0               hdf23fa2_0  
google-auth               2.6.0              pyhd3eb1b0_0  
google-auth-oauthlib      0.4.1                      py_2  
google-pasta              0.2.0              pyhd3eb1b0_0  
grpc-cpp                  1.42.0               h6da9ac5_1    conda-forge
grpcio                    1.42.0           py39ha29bfda_0  
h5py                      3.6.0            py39h4a1dd59_0  
hdf5                      1.10.6               hdbbcd12_0  
icu                       69.1                 he49afe7_0    conda-forge
idna                      3.3                pyhd3eb1b0_0  
importlib-metadata        4.11.3           py39hecd8cb5_0  
importlib_metadata        4.11.3               hd3eb1b0_0  
intel-openmp              2021.4.0          hecd8cb5_3538  
ipykernel                 6.9.1            py39hecd8cb5_0  
ipython                   8.2.0            py39hecd8cb5_0  
ipython_genutils          0.2.0              pyhd3eb1b0_1  
ipywidgets                7.6.5              pyhd3eb1b0_1  
jax                       0.3.4              pyhd8ed1ab_0    conda-forge
jaxlib                    0.3.2                    pypi_0    pypi
jbig                      2.1                  h4d881f8_0  
jedi                      0.18.1           py39hecd8cb5_1  
jinja2                    3.0.3              pyhd3eb1b0_0  
jpeg                      9e                   h0d85af4_0    conda-forge
jsonschema                3.2.0              pyhd3eb1b0_2  
jupyter                   1.0.0            py39hecd8cb5_7  
jupyter_client            7.1.2              pyhd3eb1b0_0  
jupyter_console           6.4.3              pyhd3eb1b0_0  
jupyter_core              4.9.2            py39hecd8cb5_0  
jupyterlab_pygments       0.1.2                      py_0  
jupyterlab_widgets        1.0.0              pyhd3eb1b0_1  
keras                     2.7.0              pyhd8ed1ab_0    conda-forge
keras-preprocessing       1.1.2              pyhd3eb1b0_0  
kiwisolver                1.4.2                    pypi_0    pypi
krb5                      1.19.2               hcd88c3b_0  
lcms2                     2.12                 hf1fd2bf_0  
lerc                      3.0                  he9d5cce_0  
libclang                  13.0.1          default_he082bbe_0    conda-forge
libcurl                   7.81.0               hf45b732_0    conda-forge
libcxx                    13.0.1               hc203e6f_0    conda-forge
libdeflate                1.8                  h9ed2024_5  
libedit                   3.1.20210910         hca72f7f_0  
libev                     4.33                 h9ed2024_1  
libffi                    3.3                  hb1e8313_2  
libgfortran               3.0.1                h93005f0_2  
libiconv                  1.16                 h1de35cc_0  
libllvm13                 13.0.1               h64f94b2_2    conda-forge
libnghttp2                1.46.0               ha29bfda_0  
libpng                    1.6.37               ha441bb4_0  
libpq                     14.2                 hea3049e_0    conda-forge
libprotobuf               3.19.4               hcf210ce_0    conda-forge
libsodium                 1.0.18               h1de35cc_0  
libssh2                   1.10.0               h52ee1ee_2    conda-forge
libtiff                   4.3.0                hd146c10_2    conda-forge
libwebp                   1.2.2                h56c3ce4_0  
libwebp-base              1.2.2                hca72f7f_0  
libzlib                   1.2.11            h6c3fc93_1014    conda-forge
lz4-c                     1.9.3                h23ab428_1  
markdown                  3.3.4            py39hecd8cb5_0  
markupsafe                2.0.1            py39h9ed2024_0  
matplotlib-base           3.5.1            py39hfb0c5b7_1  
matplotlib-inline         0.1.2              pyhd3eb1b0_2  
mistune                   0.8.4           py39h9ed2024_1000  
mkl                       2021.4.0           hecd8cb5_637  
mkl-service               2.4.0            py39h9ed2024_0  
mkl_fft                   1.3.1            py39h4ab4a9b_0  
mkl_random                1.2.2            py39hb2f4e1b_0  
msgpack                   1.0.3                    pypi_0    pypi
msgpack-python            1.0.2            py39hf7b0b51_1  
multidict                 5.2.0            py39hca72f7f_2  
munkres                   1.1.4                      py_0  
mysql-common              8.0.27               h694c41f_3    conda-forge
mysql-libs                8.0.27               h115446f_3    conda-forge
nbclient                  0.5.11             pyhd3eb1b0_0  
nbconvert                 6.3.0            py39hecd8cb5_0  
nbformat                  5.1.3              pyhd3eb1b0_0  
ncurses                   6.3                  hca72f7f_2  
nest-asyncio              1.5.1              pyhd3eb1b0_0  
notebook                  6.4.8            py39hecd8cb5_0  
nspr                      4.33                 he9d5cce_0  
nss                       3.74                 h47edf6a_0  
numpy                     1.22.3                   pypi_0    pypi
numpy-base                1.21.2           py39he0bd621_0  
oauthlib                  3.2.0              pyhd3eb1b0_0  
openssl                   1.1.1n               hca72f7f_0  
opt_einsum                3.3.0              pyhd3eb1b0_1  
optax                     0.1.1              pyhd8ed1ab_0    conda-forge
packaging                 21.3               pyhd3eb1b0_0  
pandocfilters             1.5.0              pyhd3eb1b0_0  
parso                     0.8.3              pyhd3eb1b0_0  
pcre                      8.45                 h23ab428_0  
pexpect                   4.8.0              pyhd3eb1b0_3  
pickleshare               0.7.5           pyhd3eb1b0_1003  
pillow                    9.1.0                    pypi_0    pypi
pip                       21.2.4           py39hecd8cb5_0  
prometheus_client         0.13.1             pyhd3eb1b0_0  
prompt-toolkit            3.0.20             pyhd3eb1b0_0  
prompt_toolkit            3.0.20               hd3eb1b0_0  
protobuf                  3.19.4           py39h9fcab8e_0    conda-forge
ptyprocess                0.7.0              pyhd3eb1b0_2  
pure_eval                 0.2.2              pyhd3eb1b0_0  
pyasn1                    0.4.8              pyhd3eb1b0_0  
pyasn1-modules            0.2.8                      py_0  
pycparser                 2.21               pyhd3eb1b0_0  
pygments                  2.11.2             pyhd3eb1b0_0  
pyjwt                     2.1.0            py39hecd8cb5_0  
pyopenssl                 21.0.0             pyhd3eb1b0_1  
pyparsing                 3.0.4              pyhd3eb1b0_0  
pyqt                      5.12.3           py39h6e9494a_8    conda-forge
pyqt-impl                 5.12.3           py39he44290a_8    conda-forge
pyqt5-sip                 4.19.18          py39h15fb055_8    conda-forge
pyqtchart                 5.12             py39he44290a_8    conda-forge
pyqtwebengine             5.12.1           py39he44290a_8    conda-forge
pyrsistent                0.18.0           py39hca72f7f_0  
pysocks                   1.7.1            py39hecd8cb5_0  
python                    3.9.11               hdfd78df_2  
python-dateutil           2.8.2              pyhd3eb1b0_0  
python-flatbuffers        2.0                pyhd3eb1b0_0  
python_abi                3.9                      2_cp39    conda-forge
pyzmq                     22.3.0           py39he9d5cce_2  
qt                        5.12.9               h2a607e2_5    conda-forge
qtconsole                 5.3.0              pyhd3eb1b0_0  
qtpy                      2.0.1              pyhd3eb1b0_0  
re2                       2021.11.01           he49afe7_0    conda-forge
readline                  8.1.2                hca72f7f_1  
requests                  2.27.1             pyhd3eb1b0_0  
requests-oauthlib         1.3.0                      py_0  
rsa                       4.7.2              pyhd3eb1b0_1  
scipy                     1.8.0                    pypi_0    pypi
send2trash                1.8.0              pyhd3eb1b0_1  
setuptools                58.0.4           py39hecd8cb5_0  
sip                       4.19.13          py39h23ab428_0  
six                       1.16.0             pyhd3eb1b0_1  
snappy                    1.1.8                hb1e8313_0  
sqlite                    3.38.2               h707629a_0  
stack_data                0.2.0              pyhd3eb1b0_0  
tensorboard               2.6.0                      py_1  
tensorboard-data-server   0.6.0            py39h5896577_0  
tensorboard-plugin-wit    1.6.0                      py_0  
tensorflow                2.7.0           cpu_py39hb0a6171_0    conda-forge
tensorflow-base           2.7.0           cpu_py39h326c378_0    conda-forge
tensorflow-estimator      2.7.0           cpu_py39hf4c5dbc_0    conda-forge
termcolor                 1.1.0            py39hecd8cb5_1  
terminado                 0.13.1           py39hecd8cb5_0  
testpath                  0.5.0              pyhd3eb1b0_0  
tk                        8.6.11               h7bc2e8c_0  
toolz                     0.11.2             pyhd3eb1b0_0  
tornado                   6.1              py39h9ed2024_0  
traitlets                 5.1.1              pyhd3eb1b0_0  
typing-extensions         3.10.0.2             hd8ed1ab_0    conda-forge
typing_extensions         3.10.0.2           pyha770c72_0    conda-forge
tzdata                    2022a                hda174b7_0  
urllib3                   1.26.8             pyhd3eb1b0_0  
wcwidth                   0.2.5              pyhd3eb1b0_0  
webencodings              0.5.1            py39hecd8cb5_1  
werkzeug                  2.0.3              pyhd3eb1b0_0  
wheel                     0.37.1             pyhd3eb1b0_0  
widgetsnbextension        3.5.2            py39hecd8cb5_0  
wrapt                     1.13.3           py39hca72f7f_2  
xz                        5.2.5                h1de35cc_0  
yarl                      1.6.3            py39h9ed2024_0  
zeromq                    4.3.4                h23ab428_0  
zipp                      3.7.0              pyhd3eb1b0_0  
zlib                      1.2.11            h6c3fc93_1014    conda-forge
zstd                      1.5.0                hcb37349_1  
```
