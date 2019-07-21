# pyelasticsearch
Search engine build with Python and Elasticsearch

### Run project and prerequisites
1. Install [Python 3.6.4](https://www.python.org/downloads/release/python-364/).

2. Install Elasticsearch 6.2 and Kibana 6.2. (Note: You may need to install [Java](https://java.com/en/download/))

  - see the Elastic downloads page for[Elasticsearch](https://www.elastic.co/downloads/elasticsearch) and [Kibana](https://www.elastic.co/downloads/kibana).

  - Make sure you can visit http://localhost:5601/ and http://localhost:9200/ in your browser.

  4. In root of the repository, set up a virtualenv:
```
python3 -m venv venv
source venv/bin/activate
```

5. Install the necessary python requirements:
```
pip install -r requirements.txt
```

6. Set up the searchapp:
```
pip install -e .
```

You're all set for the tutorial this Wednesday! :)

---

### Docker Compose

1. Go to root folder of project.

2. Download elasticsearch and kibana images; start containers via docker-compose
```
docker-compose up
```

3. In root of the repository, set up a virtualenv:
```
python3 -m venv venv
source venv/bin/activate
```

4. Install the necessary python requirements:
```
pip install -r requirements.txt
```

5. Set up the searchapp:
```
pip install -e .
```

-----

Source: http://bit.ly/pycon-elasticsearch