# news-visualization
Watson Discovery News Visualization

A [D3.js](https://d3js.org/) visualization using the pre-enriched news content avaialable as part of the [Watson Discovery Service](https://www.ibm.com/watson/developercloud/discovery.html)

To get started, provision an instance of Discovery on [Bluemix](https://console.ng.bluemix.net/)

Clone this repo and navigate to the news-visualization directory:
```
git clone https://github.com/zwalchuk/news-visualization.git
cd news-visualization
```
Gather your username, password, environment_id, and collection_id and store them as environment variables:
```
export USERNAME = '<username>'
export PASSWORD = '<password>'
export ENVIRONMENT_ID = '<environment_id>'
export COLLECTION_ID = '<collection_id>'
```
Launch the app:
```
python newsApp.py
```

