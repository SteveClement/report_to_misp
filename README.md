# report_to_misp

Parse a report and import the attributes into a MISP

# status and why fork

The current "official" repo seems to be unmaintained and the tool does not work out of the box.
Thus this fork and the fork of ioc_parser too.

Requirements
------------

Ideally install it in a virtualenv and you will also need ioc_parser

```
git clone https://github.com/SteveClement/report_to_misp.git
cd report_to_misp
mkvirtualenv -p python2 report_to_misp
git clone https://github.com/SteveClement/ioc_parser.git
pip install -r ioc_parser/requirements.txt
cd ioc_parser
python setup.py build
python setup.py install

```

