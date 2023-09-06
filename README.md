# sefaria-embedded
A Google App Engine App that provides an embedding interface for the Sefaria web app.

## Special Note: This is a legacy app that runs on Pyhon2 Runtime
https://github.com/Sefaria/Sefaria-Embedded
![sepharia](https://github.com/DaveSV/sepharia_app/assets/29576337/09afe96e-6b5a-404b-9e6e-9cbb5ec3c9c8)


### Features
* Minimal Javascript allows for a very lightweight page, great for fast loading times on slow connections, easy embedding
* English and Hebrew interface in the embedded page allows for multi-language viewing with super low resource usage
* Generates social media images for various platforms

### Installation
- Clone repo
- `cd sefaria-embedded`
- `pip install -t ./sefaria-embedded/lib -r requirements.txt`
- To deploy to cloud: `gcloud app deploy app.yaml`# sepharia_app
