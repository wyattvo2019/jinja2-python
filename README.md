https://viblo.asia/p/su-dung-jinja-template-ket-hop-voi-python-tu-dong-sinh-file-bao-cao-tu-bieu-mau-oOVlYzGV58W
This project try to apply Jinja2 to template engine
# jinja2-python
virtualenv -p /usr/bin/python3 .venv
source .venv/bin/activate
pip install jinja2-cli
jinja2 --version
# 01. template.html file contains template
# 02. jinja_render contains code to render the html file
# 03. input.json contains input data
python jinja_render.py

