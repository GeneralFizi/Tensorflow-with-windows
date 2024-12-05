# Tensorflow with Windows
https://youtu.be/nATRPPZ5dGE?si=BNoPpn3oMkh4OWy9
if you have followed the guide but still can't use tensorflow on windows, then you need do the following 

after makin a new ENV, set your tensorflow to 2.10, python 3.09 /3.9 (basically a version before python 3.10)
then, install numpy version 1.26.4. i have tried using the newest numpy, but it can't run tensorflow with gpu. so i settled with this version

Note : i dont have enough space on my c drive to install WSL, will update later.
**My pip list for running TensorFlow on Windows without WSL**


## Installed Packages

| Package                          | Version   |
|----------------------------------|-----------|
| absl-py                          | 2.1.0     |
| albucore                         | 0.0.20    |
| albumentations                   | 1.4.21    |
| annotated-types                  | 0.7.0     |
| anyio                            | 4.6.2.post1 |
| argon2-cffi                      | 23.1.0    |
| argon2-cffi-bindings             | 21.2.0    |
| arrow                            | 1.3.0     |
| asttokens                        | 2.4.1     |
| astunparse                       | 1.6.3     |
| async-lru                        | 2.0.4     |
| attrs                            | 24.2.0    |
| babel                            | 2.16.0    |
| beautifulsoup4                   | 4.12.3    |
| bleach                           | 6.2.0     |
| Brotli                           | 1.1.0     |
| cached-property                  | 1.5.2     |
| cachetools                       | 5.5.0     |
| certifi                          | 2024.8.30 |
| cffi                             | 1.17.1    |
| charset-normalizer               | 3.4.0     |
| colorama                         | 0.4.6     |
| comm                             | 0.2.2     |
| contourpy                        | 1.3.1     |
| cycler                           | 0.12.1    |
| debugpy                          | 1.8.8     |
| decorator                        | 5.1.1     |
| defusedxml                       | 0.7.1     |
| entrypoints                      | 0.4       |
| eval_type_backport               | 0.2.0     |
| exceptiongroup                   | 1.2.2     |
| executing                        | 2.1.0     |
| fastjsonschema                   | 2.20.0    |
| filelock                         | 3.16.1    |
| flatbuffers                      | 24.3.25   |
| fonttools                        | 4.55.0    |
| fqdn                             | 1.5.1     |
| fsspec                           | 2024.10.0 |
| gast                             | 0.4.0     |
| geopandas                        | 1.0.1     |
| google-auth                      | 2.36.0    |
| google-auth-oauthlib             | 0.4.6     |
| google-pasta                     | 0.2.0     |
| grpcio                           | 1.68.0    |
| h11                              | 0.14.0    |
| h2                               | 4.1.0     |
| h5py                             | 3.12.1    |
| hpack                            | 4.0.0     |
| httpcore                         | 1.0.7     |
| httpx                            | 0.27.2    |
| hyperframe                       | 6.0.1     |
| idna                             | 3.10      |
| importlib_metadata               | 8.5.0     |
| importlib_resources              | 6.4.5     |
| ipykernel                        | 6.29.5    |
| ipython                          | 8.29.0    |
| ipywidgets                       | 8.1.5     |
| isoduration                      | 20.11.0   |
| jedi                             | 0.19.2    |
| Jinja2                           | 3.1.4     |
| joblib                           | 1.4.2     |
| json5                            | 0.9.28    |
| jsonpointer                      | 3.0.0     |
| jsonschema                       | 4.23.0    |
| jsonschema-specifications        | 2024.10.1 |
| jupyter                          | 1.1.1     |
| jupyter_client                   | 8.6.3     |
| jupyter-console                  | 6.6.3     |
| jupyter_core                     | 5.7.2     |
| jupyter-events                   | 0.10.0    |
| jupyter-lsp                      | 2.2.5     |
| jupyter_server                   | 2.14.2    |
| jupyter_server_terminals         | 0.5.3     |
| jupyterlab                       | 4.2.6     |
| jupyterlab_pygments              | 0.3.0     |
| jupyterlab_server                | 2.27.3    |
| jupyterlab_widgets               | 3.0.13    |
| keras                            | 2.10.0    |
| Keras-Preprocessing              | 1.1.2     |
| kiwisolver                       | 1.4.7     |
| libclang                         | 18.1.1    |
| Markdown                         | 3.7       |
| MarkupSafe                       | 3.0.2     |
| matplotlib                       | 3.9.2     |
| matplotlib-inline                | 0.1.7     |
| mistune                          | 3.0.2     |
| mpmath                           | 1.3.0     |
| nb_conda_kernels                 | 2.5.2     |
| nbclient                         | 0.10.0    |
| nbconvert                        | 7.16.4    |
| nbformat                         | 5.10.4    |
| nest_asyncio                     | 1.6.0     |
| networkx                         | 3.4.2     |
| notebook                         | 7.2.2     |
| notebook_shim                    | 0.2.4     |
| numpy                            | 1.26.4    |
| oauthlib                         | 3.2.2     |
| opencv-python-headless           | 4.10.0.84 |
| opt_einsum                       | 3.4.0     |
| overrides                        | 7.7.0     |
| packaging                        | 24.2      |
| pandas                           | 2.2.3     |
| pandocfilters                    | 1.5.0     |
| parso                            | 0.8.4     |
| pickleshare                      | 0.7.5     |
| pillow                           | 11.0.0    |
| pip                              | 24.2      |
| pkgutil_resolve_name             | 1.3.10    |
| platformdirs                     | 4.3.6     |
| prometheus_client                | 0.21.0    |
| prompt_toolkit                   | 3.0.48    |
| protobuf                         | 3.19.6    |
| psutil                           | 6.1.0     |
| pure_eval                        | 0.2.3     |
| pyasn1                           | 0.6.1     |
| pyasn1_modules                   | 0.4.1     |
| pycparser                        | 2.22      |
| pydantic                         | 2.9.2     |
| pydantic_core                    | 2.23.4    |
| Pygments                         | 2.18.0    |
| pyogrio                          | 0.10.0    |
| pyparsing                        | 3.2.0     |
| pypiwin32                        | 223       |
| pyproj                           | 3.7.0     |
| PySocks                          | 1.7.1     |
| python-dateutil                  | 2.9.0     |
| python-json-logger               | 2.0.7     |
| pytz                             | 2024.2    |
| pywin32                          | 307       |
| pywinpty                         | 2.0.14    |
| PyYAML                           | 6.0.2     |
| pyzmq                            | 26.2.0    |
| referencing                      | 0.35.1    |
| requests                         | 2.32.3    |
| requests-oauthlib                | 2.0.0     |
| rfc3339-validator                | 0.1.4     |
| rfc3986-validator                | 0.1.1     |
| rpds-py                          | 0.21.0    |
| rsa                              | 4.9       |
| scikit-learn                     | 1.5.2     |
| scipy                            | 1.14.1    |
| seaborn                          | 0.13.2    |
| Send2Trash                       | 1.8.3     |
| setuptools                       | 75.1.0    |
| shapely                          | 2.0.6     |
| simsimd                          | 6.0.5     |
| six                              | 1.16.0    |
| sniffio                          | 1.3.1     |
| soupsieve                        | 2.5       |
| stack-data                       | 0.6.2     |
| stringzilla                      | 3.10.10   |
| sympy                            | 1.13.1    |
| tensorboard                      | 2.10.1    |
| tensorboard-data-server          | 0.6.1     |
| tensorboard-plugin-wit           | 1.8.1     |
| tensorflow                       | 2.10.0    |
| tensorflow-estimator             | 2.10.0    |
| tensorflow-io-gcs-filesystem     | 0.31.0    |
| termcolor                        | 2.5.0     |
| terminado                        | 0.18.1    |
| threadpoolctl                    | 3.5.0     |
| tinycss2                         | 1.4.0     |
| tomli                            | 2.1.0     |
| torch                            | 2.5.1     |
| tornado                          | 6.4.1     |
| traitlets                        | 5.14.3    |
| types-python-dateutil            | 2.9.0.20241003 |
| typing_extensions                | 4.12.2    |
| typing-utils                     | 0.1.0     |
| tzdata                           | 2024.2    |
| uri-template                     | 1.3.0     |
| urllib3                          | 2.2.3     |
| wcwidth                          | 0.2.13    |
| webcolors                        | 24.8.0    |
| webencodings                     | 0.5.1     |
| websocket-client                 | 1.8.0     |
| Werkzeug                         | 3.1.3     |
| wheel                            | 0.44.0    |
| widgetsnbextension               | 4.0.13    |
| win_inet_pton                    | 1.1.0     |
| wrapt                            | 1.16.0    |
| zipp                             | 3.21.0    |
| zstandard                        | 0.23.0    |
